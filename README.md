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

A insegurança alimentar severa no Brasil sofreu aumento significativo nos triênios que possuem os anos da pandemia da covid-19, como mostra o gráfico abaixo.

<img width="989" height="490" alt="gráfico 3" src="https://github.com/user-attachments/assets/6f8f411d-3524-40f1-b1d7-1502601f00f9" />

Os dados do DATASUS de internações hospitalares por morbidades nutricionais vão em linha contrária aos dados reportados pelo FAO, conforme figura 3. É evidente uma linha de tendência decrescente para os mesmos anos onde a FAO reporta picos de insegurança alimentar severa. 

<img width="1189" height="590" alt="gráfico 2" src="https://github.com/user-attachments/assets/76b53c76-1e84-4dfd-97ed-91a69a829dcb" />


<img width="1189" height="589" alt="gráfico 1" src="https://github.com/user-attachments/assets/f07cac13-68e3-4418-a98b-b6740b7ffd45" />

<img width="986" height="590" alt="correlação" src="https://github.com/user-attachments/assets/32587a5d-c3cd-4362-80f4-3a46a49dc556" />


## COMPROVANTE DE PUBLICAÇÃO

<img width="1118" height="794" alt="Comprovante_PUBLICAÇÃO" src="https://github.com/user-attachments/assets/2f1dcf3d-075c-4574-ac63-c1056e06fa93" />


