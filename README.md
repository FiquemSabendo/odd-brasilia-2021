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
 ┃ ┃ ┣ 📜2020-2015_apreensoes_animais_silvestres.csv
 ┃ ┃ ┗ 📜2020-2015_apreensoes_animais_silvestres.xlsx
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

Esta base de dados contém informações sobre as ocorrências relacionadas ao 
tráfico de animais silvestres registradas pelo Departamento de Polícia Federal
entre 2015 e outubro de 2020, conforme disponível [neste pedido][lai-animais]
de acesso à informação.

[lai-animais]: http://www.consultaesic.cgu.gov.br/busca/_layouts/15/DetalhePedido/DetalhePedido.aspx?nup=08198033422202065

#### Colunas

| Nome da coluna | Tipo | Descrição |
| ------ | ------ | ------ |
| UF | Texto | Sigla da Unidade da Federação da ocorrência |
| Cidade | Texto | Nome do município da ocorrência |
| Data | Data (`DD/MM/AAAA`) | Data de registro da ocorrência |
| Dados da apreensão | Texto | Descrição dos animais e/ou materiais apreendidos |
| Tipo penal | Texto | Descrição dos artigos da legislação ambiental e/ou penal infringidos |

#### ⬇️ **Downloads** ⬇️

Clique com o botão direito do mouse sobre o link e escolha a opção
`Salvar link como...` (ou equivalente) para salvar o arquivo no seu computador.

- [[XLSX]](https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/blob/main/data/animais_silvestres/2020-2015_apreensoes_animais_silvestres.xlsx)
- [[CSV]](https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/animais_silvestres/2020-2015_apreensoes_animais_silvestres.csv)

### Base de gastos de ex-presidentes

Esta base de dados contém informação sobre os gastos das equipes dos Presidentes da República que deixaram o cargo desde 2003 com alimentação, hospedagem e transporte\*, durante o período em que estes exerceram os respectivos mandatos.

 Em todos os anos, as despesas se referem ao total gasto com todas as equipes que fizeram parte das comitivas do Presidente da República - por exemplo, equipes de segurança, equipes de imprensa e comunicações, cerimonial, assessores, de tecnologia da informação, etc. Ou seja, não se trata do gasto apenas com o Presidente da República.

Para mais detalhes sobre as limitações dos dados, leia as notas técnicas 
que acompanham os dados na pasta [`/data/gastos_expresidentes`](./data/gastos_expresidentes).

\* Os dados sobre gastos com transporte são fornecidos apenas para os anos 2003 a 2010.

#### ⬇️ **Downloads** ⬇️

Clique com o botão direito do mouse sobre o link e escolha a opção
`Salvar link como...` (ou equivalente) para salvar o arquivo no seu computador.

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

[temer-alim-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2018-2016_Temer_alimentacao.xlsx

[temer-alim-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2018-2016_Temer_alimentacao.csv

[temer-hosp-xlsx]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/xlsx/2018-2016_Temer_hospedagem.xlsx

[temer-hosp-csv]: https://raw.githubusercontent.com/FiquemSabendo/odd-brasilia-2021/main/data/gastos_expresidentes/csv/2018-2016_Temer_hospedagem.csv

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
