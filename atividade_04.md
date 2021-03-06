PROJETO INTEGRADOR - Exercício 04
================
Prof. Neylson Crepalde
2018, March, 19 - 23

Olá, pessoal. Este é o quarto exercício do nosso Projeto Integrador
deste semestre. Vamos continuar trabalhando com o banco de dados do
Enade 2014. Para leitura dos dados, use:

``` r
library(readr)
enade14 <- read_csv2("https://raw.githubusercontent.com/neylsoncrepalde/introducao_ao_r/master/dados/enade_2014_amostra.csv")
```

## Exercícios:

1.  Extraia a média, a mediana, mínimo, máximo, variância e desvio
    padrão da idade para todos os alunos da nossa amostra aleatória.

2.  Elabore uma tabela de frequência da quantidade de alunos por sexo.
    Corrija a variável caso alguma categoria esteja “sobrando”.

3.  Agora extraia a média, a mediana, mínimo, máximo, variância e desvio
    padrão da idade para cada categoria de sexo. Exiba os mesmos
    resultados com um gráfico.

4.  Agora extraia a média, a mediana, mínimo, máximo, variância e desvio
    padrão da idade para cada categoria de cor/raça. Exiba os mesmos
    resultados com um gráfico.

5.  Verifique a distribuição de alunos por região do país. Exiba uma
    tabela de frequências e um gráfico.

6.  Vamos investigar a associação entre a renda e a cor. Faça uma tabela
    cruzada entre essas duas variáveis.

# Desafios:

1.  Guarde a tabela que vc programou no **exercício 6** num objeto.
    Existe algum teste estatístico para sabermos se existe associação
    entre essas variáveis? Rode o teste e apresente os resultados.
    (nível *easy*)

2.  Comente os resultados (nível *medium*)

3.  Verifique a variável categoria administrativa da IES no dicionário
    de variáveis. Recategorize a variável em uma binária: “Pública e
    Privada”. Crie uma nova variável para armezenar esses dados. (nível
    *hard*)

4.  Você consegue descobrir qual foi a média da nota geral dos alunos de
    pedagogia do Izabela Hendrix no Enade 2014? (nível *Chuck Norris*)
