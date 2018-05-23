# CER - Migração de dados para SICC (em atualização)

## 1. Enquadramento e Âmbito

O presente documento insere-se no âmbito do desenvolvimento do sistema de informação financeira para entidades do Ministério da Saúde, com informação normalizada de acordo com o SNC-AP e em linha com as práticas de referência na gestão e na contabilidade pública.

Este documento visa essencialmente:
- Estabelecer uma base de entendimento atualizada e comum a todas as partes interessadas;
- Acelerar o processo de migração;

Desta forma, este documento estabelece:
- As principais fases e tarefas do processo de transição para o SICC-SNC-AP e respetivos responsáveis;
- Os fluxos financeiros e respetivas regras relevantes;
- Os registos contabilísticos suportados e as respetivas regras associadas;
- Os conjuntos mínimos de dados para o funcionamento do sistema;
- As estruturas completas de dados a carregar.


## 2. Fluxo do processo de migração SICC

![](https://spmssicc.github.io/pages/markdown/cer_migracao_sicc.assets/cer_migracao_sicc-00caf3c8.png)

| Tarefa e respetivo detalhe | Responsável |
|--------|:----------------:|
| **Produzir ficheiros de migração**:</br>Extração de dados a migrar do sistema anterior e envio para a equipa do SICC, de acordo com os requisitos especificados neste documento.</br> Assegurar que:</br> i) Não existem autorizações de pagamentos por regularizar;</br>ii) Não existem guias de receita por cobrar;</br>iii) É enviada a informação até ao dia da produção do ficheiro;</br>iv) A data contabilística deverá ser “encerrada”, ao dia da produção do ficheiro. | Entidade do MS |
| **Verificar ficheiros, produzir relatório de migração e disponibilizar SICC-teste:**</br>Os ficheiros enviados pela entidade do MS são incorporados e verificados no sistema SICC-Teste. Este procedimento originará um relatório de validação e consistência de informação contabilística, que inclui eventuais medidas corretivas a serem executadas pela entidade do MS.</br>Os dados estarão aptos a serem carregados para produção quando todas as regras forem cumpridas e consequentemente, não forem identificadas situações que impeçam o seu carregamento  | Equipa SICC    |
| **Efetuar ajustamentos sugeridos**</br>Devem ser efetuadas as medidas corretivas indicadas no relatório produzido na tarefa anterior deste fluxo. Após a execução de todas as medidas corretivas, os ficheiros devem ser produzidos de novo.</br>Situações frequentes:</br>1.  “Entidade não encontrada” - Identifica um documento com uma entidade que não existe. Esta entidade deverá ser criada para possibilitar a migração do documento em causa. Os dados da entidade a criar podem ser obtidos;</br>2.  “Conta xxxxx não é de movimento no exercício XXXX” - As duas situações mais frequentes associadas com esta mensagem são:</br>2.1.  A conta foi utilizada corretamente e deverá ser alterado o seu tipo para “de movimento”;</br>2.2.  A conta foi utilizada incorretamente, devendo o lançamento ser corrigido.</br>Contudo, esta situação deverá ser analisada detalhadamente, pois as correções a efetuar poderão ser distintas das apontadas anteriormente.</br>3.  “Conta xxxxx inexistente no exercício XXXX” - O lançamento efetuado poderá ter utilizado uma conta incorreta que deverá ser corrigida. Contudo, outras razões poderão contribuir para esta situação, devendo proceder-se à sua análise detalhada. Depois de efetuados os ajustamentos, o processo de migração terá de ser novamente iniciado para o ano em causa. | Entidade do MS |
| **Comparar documentos contabilísticos entre o sistema anterior e SICC:**</br>Validações contabilísticas finais entre o sistema anterior e o SICC, nomeadamente:</br>-   A comparação de balancetes;</br>-   Extrato de contas correntes.  | Entidade do MS |
| **Identificar e corrigir diferenças:**</br> Identificação e execução de ajustamentos necessários para que os documentos contabilísticos produzam os mesmos valores em ambas as aplicações.</br>1.  Verificação e identificação de contas com valores diferentes e produção dos respetivos extratos de conta;</br>2.  Análise detalhada das diferenças e execução das respetivas ações corretivas.</br> Após efetuados os ajustamentos, o processo de migração e respetivas verificações terão de ser novamente efetuados para o exercício em questão. | Entidade do MS |
| **Finalizar migração e disponibilização do ambiente de produção:**</br>Envio dos ficheiros validados pelo parceiro para a equipa SICC validar e carregar para ambiente de produção | Equipa SICC |

## 3.  Tipos de documentos contabilísticos do sistema

São apresentadas, seguidamente, tabelas com a listagem e respectiva descrição de todos os documentos contabilísticos necessários.

### 3.1.  Documentos de despesa

| ID | Nome                                 |
|:--:|--------------------------------------|
| AB | Alteração/Anulação de compromisso    |
| AC | Anulação de Faturas de Fornecedores  |
| AF | Anulação de Faturas                  |    
| AL | Alteração aos Compromissos Assumidos |         
| AM | Alteração ao Cabimento               |           
| AP | Autorização de Pagamento             |           
| CB | Cabimentos                           |           
| CM | Compromissos                         |           
| CP | Compromissos Assumidos               |           
| DA | Despesa fundos alheios               |           
| DF | Débito sobre a fatura                |           
| NC | Notas de crédito                     |           
| P1 | Fatura em Receção e Conferência      |           
| P2 | Fatura Conferida do Fornecedor       |           
| PG | Pagamentos                           |           

### 3.2. Documentos de receita

| ID | Nome                            |
|:--:|---------------------------------|
| AD | Anulação de devedores           |           
| AR | Anulação de Receita             |           
| CC | Créditos a Clientes             |           
| CD | Cobrança duvidosa               |           
| CF | Crédito sobre a fatura          |          
| CI | Créditos incobráveis            |           
| CO | Cobranças                       |           
| DE | Devedores p/execução orçamental |           
| FD | Faturas de devedores            |           
| GR | Guia de receita                 |           
| OR | Outras receitas                 |           
| RA | Receita fundos alheios          |           

### 3.3. Despesa/receita

| ID | Nome                           |
|:--:|--------------------------------|
| CT | Cativos ou congelamentos       |           
| DT | Descativos ou descongelamentos |           
| OD | Operações diversas             |           

### 3.4. Outros documentos

| ID | Nome                            |
|:--:|---------------------------------|
| FP | Fundos disponíveis              |           
| NB | Notas de débito                 |           
| OA | Orçamento fundos alheios        |           
| OC | Orçamento de compras            |           
| OE | Orçamento de exploração         |           
| OF | Orçamento financeiro            |           
| OI | Orçamento de investimentos      |           
| OO | Orçamento exec. orçamental      |           
| PA | Proposta orç. fundos alheios    |           
| PC | Proposta orçamento compras      |           
| PE | Proposta orç. exploração        |           
| PF | Proposta orçamento financeiro   |           
| PI | Proposta orç. investimentos     |           
| PO | Proposta orç. ex. orçam.        |           
| RC | Resultados correntes            |           
| RD | Recuperação de dívidas          |           
| RE | Resultados extraordinários      |           
| RF | Resultados financeiros          |           
| RI | Resultados antes de impostos    |           
| RL | Resultados líquidos             |           
| RO | Resultados operacionais         |           

## 4.  Fluxos financeiros do sistema

### 4.1.  Despesa de Fundos Próprios

![](https://spmssicc.github.io/pages/markdown/cer_migracao_sicc.assets/cer_migracao_sicc-e00fe481.png)

Regras e considerações de relevo do fluxo:

|ID|Descrição |
|:--:|-----|
| 1  | Todos os tipos de documentos podem ser regularizados por um ou vários documentos até ao seu valor total. Ex.: Um CB no valor de 100€ poderá dar origem a vários CM até ao valor de 100€ |
| 2  | O documento de registo AL e AM alteram o valor do CB e CP respetivamente, alterando também o valor disponível para o tipo do documento subsequente.|
| 3  | Em caso de utilização do documento Fatura em Receção e Conferência em P1, posteriormente este deverá ser regularizado em P2. |

### 4.2 Receita de Fundos Próprios

![](https://spmssicc.github.io/pages/markdown/cer_migracao_sicc.assets/cer_migracao_sicc-eb07e506.png)

Regras relevantes:

| ID | Descrição |
|:--:|---------|
| 1  | Todos os tipos de documentos podem ser regularizados por um ou vários até ao seu valor total. Ex: FD no valor de 100€ poderá dar origem a vários GR até ao valor de 100€ |


## 5. Relação de tipos de documentos

| Tipo Doc | Designação                          | Regulariza          | Regularizado   | Observações                                      |
|:--------:|-------------------------------------|---------------------|----------------|--------------------------------------------------|
|    AB    | Anulações de compromissos           | CM                  |                |                                                  |
|    AC    | Anulação de credores                | P1, P2 e NC         |                |                                                  |
|    AD    | Anulação de devedores               | FD e CC             |                |                                                  |
|    AF    |                                     |                     |                |                                                  |
|    AL    | Alteração de compromissos assumidos | CP                  |                |                                                  |
|    AM    | Alteração de CB                     | CB                  |                |                                                  |
|    AP    | Autorização de pagamento            | P2, NC, DF, CF e DA | PG             |                                                  |
|    AR    |                                     |                     |                |                                                  |
|    CB    | Cabimentos                          |                     | AM e CM        |                                                  |
|    CC    | Créditos a clientes                 |                     | GR             |                                                  |
|    CD    | Cobrança duvidosa                   | FD                  |                |                                                  |
|    CF    | Créditos a fornecedores             |                     | AP             |                                                  |
|    CI    | Créditos incobráveis                | FD                  |                |                                                  |
|    CM    | Compromissos                        | CB, AM              | AB, CP, AL     |                                                  |
|    CO    | Cobranças                           | GR, RA              |                |                                                  |
|    CP    | Compromissos assumidos              | CM, AB              | AL, P1 ou P2   |                                                  |
|    CT    | Cativos ou congelamentos            |                     | DT             |                                                  |
|    DA    | Despesa fundos alheios              |                     | PG             |                                                  |
|    DF    | Débitos a fornecedores              |                     | AP             |                                                  |
|    DT    | Descativos ou congelamentos         | CT                  |                |                                                  |
|    FD    | Faturas de devedores                |                     | GR, CI, AD, CD |                                                  |
|    FP    | Fundos disponíveis                  |                     |                | Regulariza e regularizado pelo próprio Documento |
|    GR    | Guia de receita                     | FD, CC, OR, RA      | CO             |                                                  |
|    IG    | Transferências bancarias            |                     |                |                                                  |
|    NB    | Notas de débito                     |                     |                |                                                  |
|    NC    | Notas de crédito                    |                     | AP , AD        |                                                  |
|    OA    | Orçamento fundos alheios            | PA                  |                |                                                  |
|    OC    | Orçamento de compras                | PC                  |                |                                                  |
|    OD    | Operações diversas                  |                     |                |                                                  |
|    OE    | Orçamento de exploração             | PE                  |                |                                                  |
|    OF    | Orçamento financeiro                | PF                  |                |                                                  |
|    OI    | Orçamento de investimentos          | PI                  |                |                                                  |
|    OO    | Orçamento exec. orçamental          | PO                  |                |                                                  |
|    OR    | Outras receitas                     |                     | GR             |                                                  |
|    P1    | Processado em conferência           | CB, AL              | P2             | Caso exista P1                                   |
|    P2    | Processado conferido                | P1 ou CP, AL        | AP , AC        | Caso exista P1                                   |
|    PA    | Proposta orç. fundos alheios        |                     | OA             |                                                  |
|    PC    | Proposta orçamento compras          |                     | OC             |                                                  |
|    PE    | Proposta orç. exploração            |                     | OE             |                                                  |
|    PF    | Proposta orçamento financeiro       |                     | OF             |                                                  |
|    PG    | Pagamentos                          | AP                  |                |                                                  |
|    PI    | Proposta orç. investimentos         |                     | OI             |                                                  |
|    PO    | Proposta orç. ex. orçam.            |                     | OO             |                                                  |
|    RA    | Receita fundos alheios              |                     | CO             |                                                  |
|    RC    | Resultados correntes                |                     |                | Cálculos Contabilísticos                         |
|    RD    | Recuperação de dívidas              |                     |                |                                                  |
|    RE    | Resultados extraordinários          |                     |                | Cálculos Contabilísticos                         |
|    RF    | Resultados financeiros              |                     |                | Cálculos Contabilísticos                         |
|    RI    | Resultados antes de impostos        |                     |                | Cálculos Contabilísticos                         |
|    RL    | Resultados líquidos                 |                     |                | Cálculos Contabilísticos                         |
|    RO    | Resultados operacionais             |                     |                | Cálculos Contabilísticos                         |

## 6. Estrutura da informação a carregar

A importação dos dados de histórico é feita de acordo com as 9 dimensões
seguintes (conjuntos de dados):

-   Plano de Contas;

-   Entidades;

-   Centros de Custos;

-   Contabilidade Analítica;

-   Contabilidade Geral;

-   Contabilidade Orçamental;

-   Contabilidade Pública;

-   Cabeçalhos dos documentos contabilísticos;

-   Registos Contabilísticos Relacionados.

Nas subsecções seguintes, detalham-se os campos de cada dimensão.

Uma especial atenção deve ser dada aos campos que são de preenchimento obrigatório.

>**Notas**

**Nenhum** ficheiro de migração deve conter a linha de cabeçalho.


**Todos** os ficheiros de migração, após preenchidos, devem ser guardados em formato **CSV** e devem estar codificados em UTF-8.

Quando o ficheiro é preenchido em Excel o processo para guardar o ficheiro de forma correta é:

1. Indicar o nome do ficheiro consoante o tipo de dados importados (Nomes indicados mais adiante);
2. Indicar o tipo de ficheiro - CSV (Comma delimited)

 ![](https://spmssicc.github.io/pages/markdown/cer_migracao_sicc.assets/cer_migracao_sicc-dff900b1.png)

3. Indicar o tipo de codificação do ficheiro.

 ![](https://spmssicc.github.io/pages/markdown/cer_migracao_sicc.assets/tabelas_mestre.gif)

Os nomes com os quais os ficheiros devem ser guardados encontram-se seguidamente apresentados:

| Dimensão                                  | NOME FICHEIRO |
|:------------------------------------------|:--------------|
| Entidades                                 | ENTIDADE      |
| Tipos de entidade                         | TTIPOENT      |
| Fatores de Aglutinação                    | TFACAGLU      |
| Plano de Contas                           | PCONTAS       |
| Centros de Custos                         | CCUSTOS       |
| Contabilidade analítica                   | CONTAANA      |
| Contabilidade Geral                       | CONTABIL      |
| Contabilidade Orçamental                  | CONTAORC      |
| Contabilidade Pública                     | CPUBLICA      |
| Cabeçalhos dos documentos contabilísticos | DOCCABS       |
| Registos Contabilísticos Relacionados     | DOCLIGA       |

### 6.1. Entidades

|   ID   | Campo                        |     Tipo     |  Obrig  | Descrição                                      |
|:------:|------------------------------|:------------:|:-------:|------------------------------------------------|
| 6.1.1  | Código                       |   Numérico   | **Sim** | Identificador numérico da entidade             |
| 6.1.2  | Nome                         | Texto (100)  | **Sim** | Designação da entidade                         |
| 6.1.3  | Tipo                         |   Numérico   | **Sim** | Código identificador do tipo de entidade       |
| 6.1.4  | Contacto                     | Texto (100)  |   Não   | Contacto preferencial da entidade              |
| 6.1.5  | Morada                       | Texto (100)  |   Não   | Endereço postal da entidade                    |
| 6.1.6  | Telefone 1                   |  Texto (15)  |   Não   | Contacto telefónico primário                   |
| 6.1.7  | Telefone 2                   |  Texto (15)  |   Não   | Contacto telefónico alternativo                |
| 6.1.8  | Telefone 3                   |  Texto (15)  |   Não   | Contacto telefónico alternativo                |
| 6.1.9  | Fax                          |  Texto (15)  |   Não   | Contacto fax                                   |
| 6.1.10 | Localidade                   | Texto (100)  |   Não   | Nome da localidade                             |
| 6.1.11 | Código Postal (4 algarismos) |   Numérico   |   Não   | Primeiros 4 algarismos do Código Postal        |
| 6.1.12 | Código Postal (3 algarismos) |  Texto (3)   |   Não   | Últimos 3 algarismos do CP                     |
| 6.1.13 | IBAN 1                       |  Texto (34)  |   Não   | IBAN da entidade                               |
| 6.1.14 | IBAN 2                       |  Texto (34)  |   Não   | IBAN de Factoring                              |
| 6.1.15 | N.º/código contribuinte      |  Texto (25)  |   Não   | Identificador alfanumérico                     |
| 6.1.16 | Observações                  | Texto (1000) |   Não   |                                                |
| 6.1.17 | Prazo de vencimento (dias)   |   Numérico   |   Não   | N.º de dias de vencimento                      |
| 6.1.18 | Limite de crédito            |   Numérico   |   Não   |                                                |
| 6.1.19 | Email                        | Texto (100)  |   Não   | Endereço de correio eletrónico                 |
| 6.1.20 | Factor de aglutinação        |   Numérico   | **Sim** | Identificador numérico do fator de aglutinação |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/ENTIDADE.csv'">Descarregar CSV</button>
</div>

### 6.2. Tipos de entidades
|   ID   | Campo                           |    Tipo    |  Obrig  | Descrição                                  |
|:------:|---------------------------------|:----------:|:-------:|--------------------------------------------|
| 6.2.1  | Tipo de Entidade                |  Numérico  | **Sim** | Identificador numérico do tipo de entidade |
| 6.2.2. | Designação do tipo de entidade | Texto (30) | **Sim** |                                            |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/TTIPOENT.csv'">Descarregar CSV</button>
</div>

### 6.3. Factores de aglutinação

|   ID   | Campo                              |    Tipo     |  Obrig  | Descrição                                      |
|:------:|------------------------------------|:-----------:|:-------:|------------------------------------------------|
| 6.3.1  | Fator de Aglutinação               |  Numérico   | **Sim** | Identificador numérico do fator de aglutinação |
| 6.3.2. | Designação do fator de aglutinação | Texto (100) | **Sim** |                                                |
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/TFACAGLU.csv'">Descarregar CSV</button>
</div>

### 6.4. Plano de Contas

|   ID   | Campo                                 |      Tipo       |  Obrig  | Descrição                                   |
|:------:|---------------------------------------|:---------------:|:-------:|---------------------------------------------|
| 6.4.1  | Ano                                   |  Numérico (4)   | **Sim** | Ano do exercício                            |
| 6.4.2  | Conta                                 |   Texto (50)    | **Sim** | Código da conta                             |
| 6.4.3  | Nome                                  |   Texto (100)   | **Sim** | Nome da conta                               |
| 6.4.4  | Tipo                                  |    Texto (1)    | **Sim** | (**M**)ovimentação/(**A**)cumulação         |
| 6.4.5  | Grau                                  |    Numérico     |   Não   | Grau da conta                               |
| 6.4.6  | Conta de acumulação                   |   Texto (50)    |   Não   | Conta homóloga no exercício fiscal anterior |
| 6.4.7  | Conta analítica                       |   Texto (50)    |   Não   | Código da conta analítica                   |
| 6.4.8  | Saldo inicial a crédito de balanço    | Numérico (22,2) |   Não   | Valores de balanço N-1 a débito             |
| 6.4.9  | Saldo inicial a débito de balanço     | Numérico (22,2) |   Não   | Valores de balanço N-1 a crédito            |
| 6.4.10 | Saldo inicial a crédito de resultados | Numérico (22,2) |   Não   | Valores de resultados N-1 a débito          |
| 6.4.11 | Saldo inicial a débito de resultados  | Numérico (22,2) |   Não   | Valores de resultados N-1 a crédito         |
| 6.4.12 | Classificador económico               |   Texto (50)    |   Não   | Classificador económico da conta            |
| 6.4.13 | Rubrica financeira                    |   Texto (50)    |   Não   | Rubrica financeira da conta                 |
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PCONTAS.csv'">Descarregar CSV</button>
</div>


### 6.5. Centros de Custos

|  ID   | Campo                            |    Tipo     |  Obrig  | Descrição                                                           |
|:-----:|----------------------------------|:-----------:|:-------:|---------------------------------------------------------------------|
| 6.5.1 | Ano                              |  Numérico   | **Sim** | Formato: 2016                                                       |
| 6.5.2 | Identificador do Centro de Custo | Texto (10)  | **Sim** | Código do centro de custo                                           |
| 6.5.3 | Nome                             | Texto (100) |   Não   | Designação do centro de custo                                       |
| 6.5.4 | Tipo                             |  Texto (1)  |   Não   | Identificador do tipo da conta: (**M**)ovimento ou (**A**)cumulação |
| 6.5.5 | Centro de custo de acumulação    | Texto (20)  |   Não   | Código do centro de custo de acumulação                             |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CCUSTOS.csv'">Descarregar CSV</button>
</div>

### 6.6. Contabilidade Analítica

|   ID   | Campo                 |      Tipo       |  Obrig  | Descrição                                                                 |
|:------:|-----------------------|:---------------:|:-------:|---------------------------------------------------------------------------|
| 6.6.1  | Entidade do documento |    Numérico     | **Sim** | Identificador numérico da entidade                                        |
| 6.6.2  | Tipo de documento     |    Texto (2)    | **Sim** | Identificador alfanumérico do tipo de documento contabilístico do sistema |
| 6.6.3  | Ano de documento      |  Numérico (4)   | **Sim** | Identificador do ano                                                      |
| 6.6.4  | N.º de documento      |    Numérico     | **Sim** | Identificador do documento                                                |
| 6.6.5  | Ordem                 |    Numérico     | **Sim** | Ordem do registo contabilístico no documento                              |
| 6.6.6  | Estado                |    Numérico     |   Não   | Estado de contabilização (contabilizado ou não)                           |
| 6.6.7  | Conta                 |   Texto (50)    |   Não   | Código da conta                                                           |
| 6.6.8  | Centro de custo       |   Texto (20)    |   Não   |                                                                           |
| 6.6.9  | Conta analítica       |   Texto (50)    |   Não   |                                                                           |
| 6.6.10 | Débito                | Numérico (22,2) |   Não   | Conta movimento a débito.                                                 |
| 6.6.11 | Crédito               | Numérico (22,2) |   Não   | Conta movimento a crédito                                                 |
| 6.6.12 | Descrição             |   Texto (100)   |   Não   |                                                                           |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CONTAANA.csv'">Descarregar CSV</button>
</div>

### 6.7. Contabilidade Geral

| ID     | Campo                    | Tipo            | Obrig | Descrição                                                                 |
|:--------:|--------------------------|:-----------------:|:-------:|---------------------------------------------------------------------------|
| 6.7.1  | Entidade do documento    | Numérico        | **Sim**    | Identificador numérico da entidade                                        |
| 6.7.2  | Tipo de documento        | Texto (2)       | **Sim**    | Identificador alfanumérico do tipo de documento contabilístico do sistema |
| 6.7.3  | Ano do documento         | Numérico (4)    | **Sim**    | Identificador do ano                                                      |
| 6.7.4  | N.º do documento         | Numérico        | **Sim**    |                                                                           |
| 6.7.5  | Ordem                    | Numérico        | **Sim**    | Posição do registo no documento                                           |
| 6.7.6  | Estado de contabilização | Numérico        | **Sim**    | São possíveis os estados 0 e 2. O estado 0 corresponde ao contabilizado e o estado 2 ao não contabilizado                  |
| 6.7.7  | Conta                    | Texto (50)      | **Sim**    | Código da conta                                                           |
| 6.7.8  | Débito                   | Numérico (22,2) |**Sim**|Conta movimento a débito.       |
| 6.7.9  | Crédito                  | Numérico (22,2) | **Sim**    |  Conta movimento a crédito.    |
| 6.7.10 | Descrição                | Texto (100)     | Não   |                                                                           |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CONTABIL.csv'">Descarregar CSV</button>
</div>

### 6.8. Contabilidade Orçamental

|   ID   | Campo                 |      Tipo       |  Obrig  | Descrição                                                                 |
|:------:|-----------------------|:---------------:|:-------:|---------------------------------------------------------------------------|
| 6.8.1  | Entidade do documento |    Numérico     | **Sim** | Identificador numérico da entidade                                        |
| 6.8.2  | Tipo de documento     |    Texto (2)    | **Sim** | Identificador alfanumérico do tipo de documento contabilístico do sistema |
| 6.8.3  | Ano do documento      |  Numérico (4)   | **Sim** | Identificador do ano                                                      |
| 6.8.4  | N.º do documento      |    Numérico     | **Sim** | Código identificador do documento                                         |
| 6.8.5  | Ordem                 |    Numérico     | **Sim** | Posição do registo no documento                                           |
| 6.8.6  | Estado                |    Numérico     | **Sim** |                                                                           |
| 6.8.7  | Conta                 |   Texto (50)    | **Sim** | Código da conta                                                           |
| 6.8.8  | Débito                | Numérico (22,2) | **Sim** | Conta movimento a débito.                                                 |
| 6.8.9  | Crédito               | Numérico (22,2) | **Sim** | Conta movimento a crédito                                                 |
| 6.8.10 | Descrição             |   Texto (100)   |   Não   |                                                                           |
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CONTAORC.csv'">Descarregar CSV</button>
</div>

### 6.9. Contabilidade Pública

|  ID   | Campo                                 |    Tipo     |  Obrig  | Descrição                                                   |
|:-----:|---------------------------------------|:-----------:|:-------:|-------------------------------------------------------------|
| 6.9.1 | Ano                                   |  Numérico   | **Sim** | Identificador do ano                                        |
| 6.9.2 | Classificador Económico               | Texto (20)  | **Sim** | Código da conta                                             |
| 6.9.3 | D/R                                   |  Texto (1)  | **Sim** | Despesa/Receita                                             |
| 6.9.4 | Nome                                  | Texto (100) |   Não   | Nome da conta                                               |
| 6.9.5 | Tipo                                  |  Texto (1)  |   Não   | Identificador do tipo da conta: (M)ovimento ou (A)cumulação |
| 6.9.6 | Classificador económico de acumulação | Texto (20)  |   Não   | Código do classificador económico de acumulação             |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CPUBLICA.csv'">Descarregar CSV</button>
</div>

### 6.10. Cabeçalhos dos documentos contabilísticos

|   ID   | Campo                |      Tipo       |  Obrig  | Descrição                                                                 |
|:------:|----------------------|:---------------:|:-------:|---------------------------------------------------------------------------|
| 6.10.1  | Entidade             |    Numérico     | **Sim** | Identificador numérico da entidade                                        |
| 6.10.2  | Tipo                 |    Texto (2)    | **Sim** | Identificador alfanumérico do tipo de documento contabilístico do sistema |
| 6.10.3  | Ano                  |  Numérico (4)   | **Sim** | Identificador do ano                                                      |
| 6.10.4  | Numero               |    Numérico     | **Sim** |                                                                           |
| 6.10.5  | Data                 |      Data       | **Sim** | Formato: 31/12/2017                                                       |
| 6.10.6  | Valor                | Numérico (22,2) | **Sim** |                                                                           |
| 6.10.7  | Data contabilística  |      Data       | **Sim** | Formato: 31/12/2017                                                       |
| 6.10.8  | Arquivo              |    Numérico     | **Sim** |                                                                           |
| 6.10.9  | Diário               |    Numérico     | **Sim** |                                                                           |
| 6.10.10 | Instituição Bancária |   Texto (50)    |   Não   |                                                                           |
| 6.10.11 | Data vencimento      |      Data       | **Sim** | Formato: 31/12/2017                                                       |
| 6.10.12 | Dias vencimento      |    Numérico     | **Sim** |                                                                           |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/DOCCABS.csv'">Descarregar CSV</button>
</div>

### 6.11. Registos de Documentos Relacionados

| ID    | Campo                                                             | Tipo      | Obrig | Descrição                                                                                                                                    |
|:-------:|-------------------------------------------------------------------|:-----------:|:-------:|----------------------------------------------------------------------------------------------------------------------------------------------|
| 6.11.1 | Documento subsequente - Entidade                                  | Numérico  | **Sim**    | Identificador numérico da entidade subsequente |
| 6.11.2 | Documento subsequente - Tipo                                      | Texto (2) | **Sim**    | Identificador alfanumérico do tipo de documento contabilístico do sistema  |
| 6.11.3 | Documento subsequente - Ano                                       | Numérico  | **Sim**    | Ano do documento subsequente                                                                                                                 |
| 6.11.4 | Documento subsequente – Nº                                        | Numérico  | **Sim**    |                                                                                                                                              |
| 6.11.5 | Nº de documentos subsequentes resultantes do documento precedente | Numérico  | **Sim**    | Ex.: Nº sequencial do subsequente com origem na mesma fatura |
| 6.11.6 | Documento precedente - Entidade                                   | Numérico  | **Sim**    | Identificador numérico da entidade precedente                                                                                                |
| 6.11.7 | Documento precedente - Tipo                                       | Texto (2) | **Sim**    | Identificador alfanumérico do tipo de documento contabilístico do sistema                                                                    |
| 6.11.8 | Documento precedente - Ano                                        | Numérico  | **Sim**    | Documento imediatamente anterior a outro documento, conforme os fluxos financeiros do sistema. Ex: Cabimento (CB) precede o Compromisso (CM) |
| 6.11.9 | Documento precedente – Nº                                         | Numérico  | **Sim**    |                                                                                                                                              |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/DOCLIGA.csv'">Descarregar CSV</button>
</div>
