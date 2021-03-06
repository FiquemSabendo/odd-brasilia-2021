# Open Data Day Brasília - 2021

Repositório de dados da Fiquem Sabendo no Open Data Day Brasília 2021

Este repositório contém bases de dados públicos liberadas pela [Fiquem Sabendo](https://fiquemsabendo.com.br/), agência de dados independente e especializada na Lei de Acesso à Informação (LAI). As bases de dados foram disponibilizadas para as atividades do [Open Data Day Brasília 2021](https://www.sympla.com.br/open-data-day-brasilia__1142950), organizado pela [Open Knowledge Brasil](https://www.ok.org.br/) em parceria com a comunidade de dados abertos do Distrito Federal.

## As bases de dados

Este repositório contém duas bases de dados liberadas pela Fiquem Sabendo com base na Lei de Acesso à Informação: a base de **apreensões de animais silvestres** e as bases de **gastos de ex-presidentes com alimentação e hospedagem**.

Ambas as bases são reproduzidas no diretório [`/data`][./data], nos formatos
originalmente fornecido pelos órgãos (`.xlsx`) e no formato `.csv`. A estrutura
do diretório com as bases de dados é a seguinte (*veja os links
[abaixo](#base-de-dados-de-animais-silvestres) para download direto*):

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
```

### Base de dados de animais silvestres

⬇️ **Downloads** ⬇️

- [[XLSX]](https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/blob/main/data/animais_silvestres/2015_apreensoes_animais_silvestres.xlsx)
- [[CSV]](https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/animais_silvestres/2015_apreensoes_animais_silvestres.csv)

### Base de gastos de ex-presidentes

⬇️ **Downloads** ⬇️

- Lula *(2003-2010)*:
  - Todos os gastos: [[XLSX]][lula-xlsx]
  - Alimentação: [[CSV]][lula-alim-csv]
  - Hospedagem: [[CSV]][lula-hosp-csv]
  - Locação de transporte: [[CSV]][lula-tran-csv]
- Dilma I *(2011-2014)*:
  - Todos os gastos: [[XLSX]][dilma-1-xlsx]
  - Alimentação: [[CSV]][dilma-1-alim-csv]
  - Hospedagem: [[CSV]][dilma-1-hosp-csv]
- Dilma II *(2015-2016)*:
  - Todos os gastos: [[XLSX]][dilma-2-xlsx]
  - Alimentação: [[CSV]][dilma-2-alim-csv]
  - Hospedagem: [[CSV]][dilma-2-hosp-csv]
- Temer *(2016-2018)*:
  - Alimentação: [[XLSX]][temer-alim-xlsx] [[CSV]][temer-alim-csv]
  - Hospedagem: [[XLSX]][temer-hosp-xlsx] [[CSV]][temer-hosp-csv]

[lula-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2010-2003_Lula.xlsx

[lula-alim-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2010-2003_Lula_alimentacao.csv

[lula-hosp-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2010-2003_Lula_hospedagem.csv

[lula-tran-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2010-2003_Lula_transporte.csv

[dilma-1-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2014-2011_Dilma_1.xlsx

[dilma-1-alim-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2014-2011_Dilma_alimentacao.csv

[dilma-1-hosp-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2014-2011_Dilma_hospedagem.csv

[dilma-2-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2016-2015_Dilma_2.xlsx

[dilma-2-alim-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2016-2015_Dilma_alimentacao.csv

[dilma-2-hosp-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2016-2015_Dilma_hospedagem.csv

[temer-alim-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2018-2016_ Temer_alimentacao.xlsx

[temer-alim-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2018-2016_ Temer_alimentacao.csv

[temer-hosp-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2018-2016_ Temer_hospedagem.xlsx

[temer-hosp-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2018-2016_ Temer_hospedagem.csv

## Formato dos arquivos `.csv`

Se necessário, a leitura dos arquivos `.csv` deve utilizar os seguintes
parâmetros:

| Parâmetro | Valor |
| ------ | ------ |
| Codificação (*encoding*) | UTF-8 |
| Separador | `,` |
| Delimitador de texto | `""` |
| Separador decimal | `,` |

Quanto às datas, a maioria está no formato `DD/MM/AAAA`, embora alguns arquivos
possam conter outros formatos, como `DD-mês-AAAA` (onde `mês` é a abreviatura
de três letras do mês em inglês).

## Contato

Se tiver qualquer dúvida, acompanhe a discussão do ODD Brasília 2021 no 
[Discord da Open Knowledge Brasil](https://discord.gg/WpSsGW47).
