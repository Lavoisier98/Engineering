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











