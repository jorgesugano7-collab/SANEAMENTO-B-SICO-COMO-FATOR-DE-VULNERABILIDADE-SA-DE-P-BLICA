# SANEAMENTO-B-SICO-COMO-FATOR-DE-VULNERABILIDADE-SA-DE-P-BLICA
O grupo desenvolveu um programa em Python, utilizando as bibliotecas Pandas, Matplotlib e Seaborn, para facilitar a análise comparativa entre dados de saneamento e informações sobre a COVID-19 em municípios específicos, para anos selecionados entre 2020 e 2022. 

Como Funciona? 

Seleção de Ano: O usuário inicia o programa escolhendo um ano entre 2020, 2021 ou 2022. Na seleção de arquivos o usuário deve inserir todos os arquivos que estão presentes no repositório. 

Carregamento de Dados: Com base no ano escolhido, o programa carrega dois conjuntos de dados em formato Excel:  

Dados de Saneamento: Contendo informações como a 'Eficiência (%)' do sistema de saneamento dos municípios. 

Dados de COVID-19: Incluindo a 'Casos Acumulados / População %', que representa a proporção de casos acumulados de COVID-19 em relação à população total do município. 

Seleção de Município: Em seguida, o usuário insere o nome de um município para o qual deseja realizar a análise. 

Filtragem e Exibição: O programa filtra os dados de saneamento e COVID-19 para o município selecionado, extraindo os valores das métricas de interesse ('Eficiência (%)' e 'Casos Acumulados / População %'). 

Visualização Gráfica: Para facilitar a compreensão, um gráfico de barras é gerado, comparando visualmente a eficiência do saneamento e a taxa de casos de COVID-19 por população no município e ano escolhidos. As porcentagens exatas são exibidas diretamente nas barras do gráfico. 
