# Insegurança Alimentar no Brasil: um estudo sob o viés dos dados de morbidades nutricionais do SUS
Este repositório tem como objetivo armazenar e informar de maneira resumida a respeito do artigo INSEGURANÇA ALIMENTAR NO BRASIL: UM ESTUDO SOB O VIÉS DOS DADOS DE MORBIDADES NUTRICIONAIS DO SUS elaborado por Rodrigo Santos e Rafael Gino, alunos do curso de Inteligência e Análise de dados do Senai São Paulo. 

Projeto de análise de dados que investiga a relação entre a insegurança alimentar severa no Brasil, medida pela FAO, e as internações por morbidades nutricionais registradas no SUS (DATASUS), no período de 2014 a 2024.

O trabalho cruza séries temporais da FAO (insegurança alimentar severa, em milhões de pessoas por triênio) com dados do DATASUS sobre internações por desnutrição (CID-10 E40–E46), agregados em médias trienais para tornar os indicadores comparáveis. O foco é entender o que aconteceu durante os anos da pandemia de COVID-19, quando o Brasil voltou ao “Mapa da Fome” ao mesmo tempo em que os registros clínicos de desnutrição caíram.

## PERGUNTA DE PESQUISA

“Como a evolução da insegurança alimentar severa no Brasil, reportada pela FAO, se relaciona com as internações por desnutrição registradas no SUS entre 2014 e 2024, especialmente durante a pandemia de COVID-19?”

## METODOLOGIA

Extração de dados:
  FAO/FAOSTAT: população em condição de insegurança alimentar severa, em milhões de pessoas, por triênios.
  DATASUS: internações hospitalares por desnutrição (CID-10 E40 a E46), de 2014 a 2024.
Tratamento:
  Agregação dos dados anuais do SUS em médias trienais para alinhar à periodicidade da FAO.
  Análise descritiva e exploratória com Python (Pandas, NumPy, Matplotlib, Seaborn).
Estatística:
  Cálculo da correlação de Pearson entre a série de insegurança alimentar severa (FAO) e a série de internações por desnutrição (SUS).

## RESULTADOS

Os dados da FAO mostram um aumento expressivo da insegurança alimentar severa nos triênios que incluem os anos da pandemia, com a proporção da população em fome severa saltando de 6,4% (2018–2020) para 17,9% (2020–2022).
Paralelamente, as internações por desnutrição no SUS apresentam tendência continuamente decrescente ao longo de todo o período, inclusive nos anos em que a fome mais aumenta.
A correlação de Pearson entre os dois indicadores é forte e negativa (r = -0,856), indicando que, enquanto a insegurança alimentar cresce, os registros clínicos de desnutrição caminham na direção oposta.

## GRÁFICOS

## COMPROVANTE DE PUBLICAÇÃO

(Comprovante_PUBLICAÇÃO.png)

