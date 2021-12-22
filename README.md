# MAC0499 - TCC - Análise Exploratória de Dados para os testes feitos nos jogos tccTD and tccSS (2021)

### Autor:
 - Daniel Hotta
 - Rafael Silva
 - Ricardo Tanaka


## Descrição

Repósitório parte do Trabalho de Conclusão de Curso do BCC IME-USP 2021: [Algoritmo Genético para Geração de Ondas de Inimigos em Jogos)](https://www.linux.ime.usp.br/~raktanaka/mac0499/)

Contém dados sobre os testes referentes aos algoritmos genéticos nos jogos [tccTD](https://github.com/raktanaka/tccTD) e [tccSS](https://github.com/RGPRafael/godot) em cada diretório correspondente, 'Fitness Tests' com os testes de cada fitness v1, v2 e v3 , e Jupyter Notebooks contendo a Análise Exploratória de Dados para a monografia.

Necessita das bibliotecas Numpy, Pandas e Matplotlib.

- dados
  - Arquivos .txt contendo a lista dos inimigos em cada onda e o dano total causado nela. São pelo menos 10 resultados (300 ondas) para os testes uniformes no tccTD e 30 (900 ondas) nos outros;
  - Os Notebooks garantem que são utilizadas somente 10 ou 30 ondas.

- analysis.ipynb
  - Rascunho, utiliza os arquivos da IA e Random dos jogos para produzir imagens contendo a moda das ondas.

- statistics.ipynb
  - Rascunho, utiliza os arquivos da IA e Random dos jogos para calcular média, desvio padrão e o Boxplot das ondas.

- fitness.ipynb
  - Utiliza os arquivos da IA e Random em Fitness Tests para gerar imagens das ondas, calcular as estatísticas, obter os boxplots, tabela de dados necessários, e os dados por i-ésima onda para gerar o gráfico de dano médio em conjunto com a regressão polinomial dela, para todas as versões de fitness em cada jogo.

- averages.ipynb
  - Utiliza o restante das ondas (todos os testes exceto da IA e Random) para produzir as estatísticas necessárias das ondas.

Os dados e tabelas são apresentados diretamente no Notebook, as imagens são salvas em arquivos .png na raiz.