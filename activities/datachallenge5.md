#  FLS 6397 - Introdução à Programação e Ferramentas Computacionais para as Ciências Sociais

- Responsável: Leonardo S. Barone e Jonathan Phillips

## Desafio 5

## Instruções para Entrega

Data: 02/07

Formato: arquivo .pdf ou .html produzido com RMarkdown, acompanhado de script em formato .R

Via: e-mail com título "[FLS6397] - D5".

__OBS: VOCÊ PODE FAZER ESTA ATIVIDADE SOZINH@ OU EM GRUPO DE ATÉ 3 PESSOAS__

## Instruções para a atividade

Siga as instruções abaixo. Faça no arquivo de RMarkdown uma síntese de sua atividade e apresente apenas o essencial do código (você deve julgar o que é essencial).

Documente __TODOS__ os seus passos no arquivo de script. Comente no seu script __TODOS__ os seus passos e explique a si mesm@ suas escolhas e estratégias.

As primeiras linhas do seu script devem conter suas informações pessoais como comentário, tal qual o modelo abaixo:

```{r}
### nome <- "Fulano da Silva Sauro"
### programa <- "Mestrado em Paleontologia"
### n_usp <- 32165498
### data_entrega: "29/02/2017"
```

### Parte 1 - Coletando um "corpus" com webscrapping

Coletar um conjunto de textos da internet. Você pode coletar notícias de jornal, registros administrativos ou textos de qualquer natureza, desde que contenham um número relevantes de caracteres cada (pelo menos 2 parágrafos) e sejam "discursivos", ou seja, não contenham exclusivamente informações técnicas.

### Parte 2 - Pré-processamento + nuvem de palavras

Utilizando o pacote _tm_, crie um objeto da classe "Corpus" e faça o pré-processamento do texto. Construa uma nuvem de palavras com o resultado.

### Parte 3 - Pré-processamento + nuvem de palavras

Utilizando o pacote _tidytext_, construa um gráfico de barras dos temos mais frequêntes. Repita o mesmo procedimento para "bigrams".

### Fim
