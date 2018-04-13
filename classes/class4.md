#  FLS 6397 - Introdução à Programação e Ferramentas Computacionais para as Ciências Sociais

- Responsáveis: Jonathan Phillips
- Data: 06/04/2017

## Aula 4 - Primeiros passos no tidyverse

### Objetivos Gerais

Nas três primeiras aulas aprendemos bastante sobre o básico da linguagem R. Ainda falta ver alguns dos aspectos básicos da linguagem. Ainda falta um bocado, mas é hora de avançar e começar um dos tópicos mais importantes do curso: a manipulação de bases de dados com o pacote _dplyr_. Além de aprender a fazer operações de linha e coluna, vamos também ver pela primeira vez dados relacionais, ou seja, que estão em mais de um _data frame_ e que podem ser combinados pela existência de uma variável em comum.

O curso começa a ficar mais complexo a partir de hoje, seja pelo fato de que vocês começarão a produzir código, quanto pela grau de sofisticação dos tópicos. Se você tem pendências com o curso -- tutoriais não acabados ou leitura atrasada -- esse é o momento adequado para eliminá-las.

Para quem nunca trabalhou com bases de dados relacionais, essa aula pode ser um pouco mais difícil. Não se preocupe se não entender logo de cara. Há uma leitura bastante boa (Capítulo 10 do livro _R for Data Science_), indicada abaixo.

### Roteiro para a aula

0 - Se você teve dúvidas ou problemas para resolver o Desafio 1, aprensentado da semana anterior, o começo da aula é um bom momento para conversarmos.

1- Comece o Tutorial 6 assim que chegar em sala de aula [versão github](https://github.com/leobarone/FLS6397_2018/blob/master/tutorials/tutorial06.Rmd) ou [versão RPubs](https://github.com/leobarone/FLS6397_2018/blob/master/tutorials/tutorial6.pdf). Este tutorial trata da manipulação de dados com as funções do pacote _dplyr_.

2- A seguir, faça o Tutorial 7 [versão github](https://github.com/leobarone/FLS6397_2018/blob/master/tutorials/tutorial07.Rmd) ou [versão RPubs](https://github.com/leobarone/FLS6397_2018/blob/master/tutorials/tutorial7.pdf), sobre bases de dados relacionais.

### Roteiro pós-aula

Vamos seguir com a leitura do livro _R for Data Science_. Na semana passada indicamos a leitura da parte _I Explore_. Você pode avançar agora para a parte _II Wrangle_, [aqui](http://r4ds.had.co.nz/wrangle-intro.html), que vai do capítulo 9 ao 16. Se for muita leitura para a sua semana, priorize os 10 a 13.

Veremos nos tutoriais desta aula um símbolo novo, `r %>%`, que altera o estilo do código. O capítulo 18, [aqui](http://r4ds.had.co.nz/pipes.html), trata do assunto. 

### Recurso para auto-estudo

Recomendo como material de suporte a leitura da página [Introduction to dplyr](https://cran.r-project.org/web/packages/dplyr/vignettes/introduction.html). Outro recurso bem legal para trabalhar com _dplyr_ e _readr_ são as ["colinhas" ("cheatsheets") da RStudio](https://www.rstudio.com/resources/cheatsheets/).