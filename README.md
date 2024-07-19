EDA Corrida Rio Antigo
Sobre o Projeto
Este projeto realiza uma Análise Exploratória de Dados (EDA) sobre a Corrida Rio Antigo, organizada pela De Castilho Sports e realizada no dia 09/06/2024. Esta análise visa explorar e entender os dados dos participantes dessa corrida, com foco em diversas características, incluindo posições, tempos, categorias, e muito mais.

Sobre o DataSet
O Dataset contém dados da Corrida Rio Antigo de 10 km e possui 11 colunas:

Pos: Posição geral que a pessoa chegou.
Num: Número na camisa da pessoa.
Nome: Nome completo da pessoa.
Equipe: Equipe que o corredor faz parte.
Sx: Sexo da pessoa (Masculino ou Feminino).
Cat: Categoria em que a pessoa se encontra.
Por categoria: Posição da pessoa na categoria.
PC: Tempo que a pessoa chegou no ponto de controle (a corrida teve apenas 1 ponto de controle).
Tempo: Tempo decorrido da pessoa do momento que passa pela linha de partida até a linha de chegada.
Tempo Bruto: Tempo decorrido da pessoa do momento que a prova começa até a linha de chegada.
Vel. Média: Velocidade média do corredor na prova.
Observações:
O Tempo Bruto e o Tempo podem ser ligeiramente diferentes de acordo com a posição da saída do atleta; quanto mais longe ele estiver da linha de partida, maior será essa diferença.
Usaremos a Vel. Média como nosso indicador de desempenho, pois todos os que completaram a prova se deslocaram 10 km de forma idêntica, variando apenas o tempo necessário para esse deslocamento.
Estrutura do Projeto
O projeto está organizado da seguinte forma:

Distribuição Geral dos Dados:

Distribuição de Participantes por Categoria: Quantos corredores há em cada categoria (por exemplo, faixa etária, gênero)?
Distribuição de Participantes por Equipe: Quantos corredores há em cada equipe?
Análise Específica por Gênero:

Distribuição geral por gênero, com insights sobre a participação de homens e mulheres na corrida.
Análise de Desempenho:

Análise detalhada do desempenho dos corredores, incluindo a velocidade média, tempos de conclusão, e comparações entre diferentes categorias e gêneros.
Ferramentas Utilizadas
Python: Linguagem de programação principal.
Pandas: Biblioteca para manipulação e análise de dados.
Plotly: Biblioteca gráfica para criar visualizações interativas.
Seaborn: Biblioteca gráfica para criar visualizações estatísticas.
Como Executar o Projeto
Clone o repositório para a sua máquina local.
Instale as dependências necessárias usando pip install -r requirements.txt.
Abra o arquivo Jupyter Notebook EDA_Corrida_Rio_Antigo.ipynb.
Execute as células do notebook para reproduzir a análise.
Contribuições
Sinta-se à vontade para contribuir com este projeto. Para isso, faça um fork do repositório, crie uma nova branch para a sua funcionalidade ou correção, e envie um pull request.

Licença
Este projeto está licenciado sob a licença MIT.

Agradecimentos
Agradeço à De Castilho Sports pela organização da Corrida Rio Antigo e por fornecer os dados para esta análise.
