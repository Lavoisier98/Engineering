DOCUMENTOS DE APOIO DO TCC PRODUÇÃO DE ANIDRIDO FTÁLICO/2025

1.TCC.XLSM

Arquivo com dados das linhas utilizadas no processo produtivo, assim como os principais equipamentos das operações unitárias do processo. Segue abaixo as segmentações do documento e pontos de inserções de dados para testes de métodos e compatibilidade de valores e unidades de medida. Vale lembrar que a primeira linha fica sempre reservada às unidades, para facilitar as buscas nas atualizações necessárias do material de apoio, e que a primeira coluna fica reservada aos números das linhas, não possuindo nenhuma informação relevante abaixo da última linha, número 27.

1.1 BALANÇO DE MASSA

Nas linhas da Sheet 'Linhas', temos os números das linhas do processo (podem ser conferidas com auxílio do P&ID). Nas colunas de B até J, temos as vazões (total e separada por elemento constituinte do fluido que passa pela tubulação). As vazões foram estabelecidas em kg/h de acordo com princípios de estequiometria, equivalências, cálculos de reações e análises feitas com a ferramenta 'Atingir meta' (equivalente à funcionalidade do Solver). Os exemplos mais claros são as células verdes F8 e B16, onde a partir de tentativa e erro chegou-se a valores compatíveis com as correspondências necessárias, porém feito de forma a facilitar esta parte do cálculo. As células preenchidas com números tiveram seus valores oriundos desta ferramenta, enquanto que todo o restante das células permanece em função dos resultados das outras linhas, a fim de agilizar possíveis futuros processos de correções de erros pontuais de cálculos. Tabela utilizada no TCC de modo a segregar reagentes de produtos na apresentação.

1.2 CONDIÇÕES PADRÃO DE OPERAÇÃO

Além da vasão na coluna B, temos a temperatura na coluna L e a pressão absoluta na coluna M, além da vasão volumétrica na coluna R e da vazão escolhida pelo professor Flávio Nelson Pereira, de 520 toneladas diárias de anidrido ftálico a 99,8% de pureza. A maior parte dos valores foram obtidos através do cálculo dos equipamentos, enquanto as condições restantes adotadas de forma arbitrária através de tentativa e erro com as planilhas dos equipamentos foram utilizadas nessas a fim de obter os dados dos equipamentos e não quebrar a continuidade dos cálculos consecutivos aos dimensionamentos, reduzindo margens de erros e fazendo com que os cálculos "conversem" entre si e que façam sentido.

1.3 PROPRIEDADES FÍSICO-QUÍMICAS

Constantemente utilizadas nas planilhas de apoio de cálculo de compressor, trocadores de calor e colunas de destilação, as propriedades principais (condutividade térmica, massa específica, viscosidade e calor específico) compõem as colunas N a X (com exceção da vazão volumétrica), e suas fórmulas estabelecidas nos livros de Kern e Perry se devem ao fato de seus números alternarem em função das condições de operação e da maior parte das linhas possuir misturas, sendo necessário assim a média ponderada através da tabela de balanço de massa.

1.4 DIMENSIONAMENTO DAS TUBULAÇÕES

Nas colunas de Z a AF, temos o roteiro de cálculo do dimensionamento das tubulações, seguidos a partir da tabela de velocidades recomendadas do livro Processos Químicos e Petroquímicos, também do professor Flávio Nelson Pereira. Com a tabela de diâmetros nominais obtidos através da adoção de um valor médio de velocidade que esteja dentro das recomendações, obtemos as velocidades reais de cada linha.

1.5 DIMENSIONAMENTO DAS BOMBAS

Funcionais apenas para as linhas que estão ligadas à sucção ou recalque de determinada bomba centrífuga, o cálculo também segue o roteiro estabelecido pelo livro Processos Químicos e Petroquímicos, partindo da obtenção do Reynolds e Prandt para em seguida obter o fator de Darcy que será utilizado no cálculo de perda de carga para que possa chegar ao Pbomba, para que este seja utilizado na continuidade do cálculo que está na outra Sheet (Equipamentos). Toda a parte do cálculo que está separada entre sucção e recalque está na Sheet Linhas, para que posteriormente sejam referenciadas pelo restante do cálculo.

1.6 EQUIPAMENTOS

A tabela de dados da Sheet Equipamentos refere-se aos cálculos utilizados nos roteiros de cálculo dos dimensionamentos. A fim de agilizar o cálculo, utiliza-se na tabela inteira a vasão obtida na linha que está conectada à entrada do equipamento em questão. Até a CL-02, linha 19, as colunas de C a F referem-se a valores de Diâmetro, Altura, Calor recebido e LMDT, enquanto que a partir da B-01, na linha 21, os cabeçalhos são os da linha 20, que compõem o roteiro do cálculo de dimensionamento das bombas na parte onde já não há separação entre sucção e recalque. Para os cálculos de dimensionamento de bombas, utiliza-se as tabelas auxiliares nas fotos que estão ao lado, para determinação de Motor nominal e rendimento.



2. COLUNA CL-01.XLSM E COLUNA CL-02.XLSM

Planilha de apoio utilizada no cálculo de dimensionamento das colunas de destilação CL-01 e CL-02 utilizadas no processo, através do método de FUGK (Fenske: Número mínimo de estágios teóricos; Underwood: Rmín do refluxo;  Gilliland: Número real de estágios teóricos; Kirkbride: Posição do prato de alimentação).

2.1 INSERÇÃO DE DADOS

Aqui, o usuário precisa preencher o percentual mássico de cada componente, separado por Resíduo (fundo da coluna), Feed (entrada de alimentação da coluna) e destilado (topo da coluna). Além disso, é necessário preencher o restante das células brancas, como as da coluna N, a pressão na coluna L e o q na coluna M. Não é necessário preencher todos os valores de F, D e B na coluna N, exceto caso já tenha um valor a ser obedecido.

2.2 SOLVER

O solver inicialmente modificará o valor da temperatura de fundo da coluna (célula O2) até que os valores da pressão interna do fundo (obtidos em função dos valores de pressão e parâmetros de Antoine) equivalham à pressão fornecida na célula L2 (a pressão precisa ser absoluta e seguir a unidade especificada). Após achar o valor, repetirá o procedimento para achar a temperatura da alimentação e do topo. Em seguida, alterará o parâmetro teta de Underwood até que a soma dos parâmetros teta individualizados nos elementos esteja menor que dois. Com o parâmetro definido, continua-se o roteiro de cálculo segundo método de FUGK.



3. COMPRESSOR-C-01.XLSM

O compressor segue o roteiro de cálculo da apostila 2 de operações unitárias, a fim de obter os dados técnicos do equipamento como head politrópico, rotação, diâmetro específico, velocidade específica e parâmetros mais básicos como temperatura de saída e BHP

3.1 INSERÇÃO DE DADOS

A planilha tem adaptação a vários casos, pois foi feita para ser utilizada em todo exercício de compressor que pudesse ter em provas. As células a serem preenchidas pelo usuário equivalem às brancas que estão entre as colunas B e G e estão entre as linhas 2 e 28. Não altere as células em azul claro, pois são todas calculadas. Caso haja uma mistura com um único valor, aplicar no composto Z[Restante] ao invés de aplicar nas células brancas a partir da linha 5. As células laranjas da linha G também podem ser preenchidas.

3.2 CONDIÇÕES DE PROCESSO

Nas colunas H e I, linhas de 3 a 19, são calculadas as condições de operação recomendadas para esse compressor, como a temperatura de saída.

3.4 TABELA DE VISCOSIDADE DINÂMICA E DIÂMETRO TABELADOS

No cálculo manual, faz-se uso da vazão para determinar valores mínimos e máximos de viscosidade dinâmica e diâmetro. A célula B39 recebe a vasão das condições de operação e utiliza para te fornecer os resultados para o usuário obtenha os valores de velocidade específica e diâmetro específico.

3.5 DIMENSIONAMENTO DO COMPRESSOR

A partir da linha 20 das colunas H e I, todas as células em azul clara são destinadas aos cálculos básicos de dimensionamento do compressor.



4. TROCADOR DE CALOR TC/CS

Através do método Kern, estima-se os coeficientes de película dos trocadores, área de troca térmica e perda de carga de casco e tubo.

4.1 INSERÇÃO DE DADOS

Os dados entre as colunas K e S determinam as condições de operação que serão utilizadas na obtenção dos parâmetros e propriedades técnicas dos trocadores que devem ser adotadas. Não é necessário que todos os dados estejam preenchidos na linha 6, porém quanto mais dados já tiverem sido pré-estabelecidos, menos margem de erro o cálculo terá. É possível fazer tentativa e erro com os valores desconhecidos para estudos de caso a partir dos resultados obtidos (para este projeto, alguns dos parâmetros adotados vieram de bons números obtidos através de estudos de tentativa e erro).

4.2 HOMOGENEIZAÇÃO DOS DADOS

A planilha utiliza as linhas 6 e 7 até a coluna I para calcular os dados que o usuário não preencheu através do balanço de energia (Q=m.Cp.dT).

4.3 DIMENSIONAMENTO DO TROCADOR

Aqui, estabelece-se as propriedades do trocador ideal às condições operacionais, calculando área de troca térmica, número de tubos, número de passes, diâmetro de casco, Uc e Rd.

4.4 RATING DO TROCADOR

As propriedades que podem afetar o processo, como as perdas de carga, Reynolds, Prandt e coeficientes de película.

