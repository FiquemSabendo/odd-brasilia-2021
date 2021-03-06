# Open Data Day Brasília - 2021

Repositório de dados da Fiquem Sabendo no Open Data Day Brasília 2021

Este repositório contém bases de dados públicos liberadas pela [Fiquem Sabendo](https://fiquemsabendo.com.br/), agência de dados independente e especializada na Lei de Acesso à Informação (LAI). As bases de dados foram disponibilizadas para as atividades do [Open Data Day Brasília 2021](https://www.sympla.com.br/open-data-day-brasilia__1142950), organizado pela [Open Knowledge Brasil](https://www.ok.org.br/) em parceria com a comunidade de dados abertos do Distrito Federal.

## As bases de dados

Este repositório contém duas bases de dados liberadas pela Fiquem Sabendo com base na Lei de Acesso à Informação: a base de **apreensões de animais silvestres** e as bases de **gastos de ex-presidentes com alimentação e hospedagem**.

Ambas as bases são reproduzidas no diretório [`/data`][./data], nos formatos
originalmente fornecido pelos órgãos (`.xlsx`) e no formato `.csv`. A estrutura
do diretório com as bases de dados é a seguinte:

```
📦odd-brasilia-2021
 ┣ 📂data
 ┃ ┣ 📂animais_silvestres
 ┃ ┃ ┣ 📜2015_apreensoes_animais_silvestres.csv
 ┃ ┃ ┗ 📜2015_apreensoes_animais_silvestres.xlsx
 ┃ ┗ 📂gastos_expresidentes
 ┃ ┃ ┣ 📂csv
 ┃ ┃ ┃ ┣ 📜2010-2003_Lula_alimentacao.csv
 ┃ ┃ ┃ ┣ 📜2010-2003_Lula_alimentacao_estabelecimentos.csv
 ┃ ┃ ┃ ┣ 📜2010-2003_Lula_hospedagem.csv
 ┃ ┃ ┃ ┣ 📜2010-2003_Lula_hospedagem_estabelecimentos.csv
 ┃ ┃ ┃ ┣ 📜2010-2003_Lula_transporte.csv
 ┃ ┃ ┃ ┣ 📜2014-2011_Dilma_alimentacao.csv
 ┃ ┃ ┃ ┣ 📜2014-2011_Dilma_hospedagem.csv
 ┃ ┃ ┃ ┣ 📜2016-2015_Dilma_alimentacao.csv
 ┃ ┃ ┃ ┣ 📜2016-2015_Dilma_alimentacao_estabelecimentos.csv
 ┃ ┃ ┃ ┣ 📜2016-2015_Dilma_hospedagem.csv
 ┃ ┃ ┃ ┣ 📜2016-2015_Dilma_hospedagem_estabelecimentos.csv
 ┃ ┃ ┃ ┣ 📜2018-2016_Temer_alimentacao.csv
 ┃ ┃ ┃ ┣ 📜2018-2016_Temer_alimentacao_estabelecimentos.csv
 ┃ ┃ ┃ ┣ 📜2018-2016_Temer_hospedagem.csv
 ┃ ┃ ┃ ┗ 📜2018-2016_Temer_hospedagem_estabelecimentos.csv
 ┃ ┃ ┣ 📂xlsx
 ┃ ┃ ┃ ┣ 📜2010-2003_Lula.xlsx
 ┃ ┃ ┃ ┣ 📜2014-2011_Dilma_1.xlsx
 ┃ ┃ ┃ ┣ 📜2016-2015_Dilma_2.xlsx
 ┃ ┃ ┃ ┣ 📜2018-2016_ Temer_alimentacao.xlsx
 ┃ ┃ ┃ ┗ 📜2018-2016_Temer_hospedagem.xlsx
 ┃ ┃ ┣ 📜nota_tecnica_1.pdf
 ┃ ┃ ┣ 📜nota_tecnica_2.pdf
 ┃ ┃ ┗ 📜resposta_LAI.pdf
```

### Formato dos arquivos `.csv`

Se necessário, a leitura dos arquivos `.csv` deve utilizar os seguintes
parâmetros:

| Parâmetro | Valor |
| ------ | ------ |
| Codificação (*encoding*) | UTF-8 |
| Separador | `,` |
| Delimitador de texto | `""` |
| Separador decimal | `,` |

## Contato

Se tiver qualquer dúvida, acompanhe a discussão do ODD Brasília 2021 no 
[Discord da Open Knowledge Brasil](https://discord.gg/WpSsGW47).
