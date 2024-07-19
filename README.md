# EDA Corrida Rio Antigo
![Projeto Concluído](https://img.shields.io/badge/Projeto-Concluído-green) ![GitHub last commit](https://img.shields.io/github/last-commit/silvaaraujo98/eda-corrida-rio-antigo)
![Maintenance](https://img.shields.io/maintenance/yes/2024) ![100% do Projeto](https://img.shields.io/badge/Projeto-100%25-blue)

## Sobre o Projeto
![Corrida Rio Antigo](images/corrida_rio_antigo.png)
![Eu Com Medalha](images/Eu.jpeg)
Este projeto realiza uma Análise Exploratória de Dados (EDA) sobre a Corrida Rio Antigo, organizada pela De Castilho Sports e realizada no dia 09/06/2024. Esta análise visa explorar e entender os dados dos participantes dessa corrida, com foco em diversas características, incluindo posições, tempos, categorias, e muito mais.

## Sobre o DataSet

O Dataset contém dados da Corrida Rio Antigo de 10 km e possui 11 colunas:

1. **Pos**: Posição geral que a pessoa chegou.
2. **Num**: Número na camisa da pessoa.
3. **Nome**: Nome completo da pessoa.
4. **Equipe**: Equipe que o corredor faz parte.
5. **Sx**: Sexo da pessoa (Masculino ou Feminino).
6. **Cat**: Categoria em que a pessoa se encontra.
7. **Por categoria**: Posição da pessoa na categoria.
8. **PC**: Tempo que a pessoa chegou no ponto de controle (a corrida teve apenas 1 ponto de controle).
9. **Tempo**: Tempo decorrido da pessoa do momento que passa pela linha de partida até a linha de chegada.
10. **Tempo Bruto**: Tempo decorrido da pessoa do momento que a prova começa até a linha de chegada.
11. **Vel. Média**: Velocidade média do corredor na prova.

### Observações:

- O Tempo Bruto e o Tempo podem ser ligeiramente diferentes de acordo com a posição da saída do atleta; quanto mais longe ele estiver da linha de partida, maior será essa diferença.
- Usaremos a Vel. Média como nosso indicador de desempenho, pois todos os que completaram a prova se deslocaram 10 km de forma idêntica, variando apenas o tempo necessário para esse deslocamento.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

1. **Distribuição Geral dos Dados**:
    - **Distribuição de Participantes por Categoria**: Quantos corredores há em cada categoria (por exemplo, faixa etária, gênero)?
    - **Distribuição de Participantes por Equipe**: Quantos corredores há em cada equipe?

2. **Análise Específica por Gênero**:
    - Distribuição geral por gênero, com insights sobre a participação de homens e mulheres na corrida.

3. **Análise de Desempenho**:
    - Análise detalhada do desempenho dos corredores, incluindo a velocidade média, tempos de conclusão, e comparações entre diferentes categorias e gêneros.

## Ferramentas Utilizadas

- **Python**: Linguagem de programação principal.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Seaborn**: Biblioteca gráfica para criar visualizações estatísticas.

## Como Executar o Projeto

1. Clone o repositório para a sua máquina local.
2. Instale as dependências necessárias usando `pip install -r requirements.txt`.
3. Abra o arquivo Jupyter Notebook `EDA_Corrida_Rio_Antigo.ipynb`.
4. Execute as células do notebook para reproduzir a análise.

## Contribuições

Sinta-se à vontade para contribuir com este projeto. Para isso, faça um fork do repositório, crie uma nova branch para a sua funcionalidade ou correção, e envie um pull request.

## Licença

Este projeto está licenciado sob a licença MIT.

## Agradecimentos

Agradeço à De Castilho Sports pela organização da Corrida Rio Antigo e por fornecer os dados para esta análise.
