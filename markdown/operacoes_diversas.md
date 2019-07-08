# Operações Diversas

Devem ser registados em Operações Diversas os Consumos, Apuramentos, Provisões e as Amortizações.

Para aceder ao menu relativo aos registos, impressões e listagens de OD's deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1329a32e.png)

## 1. Recolhas

No ecrã relativo à recolha de registos de OD's deve o utilizador preencher os campos obrigatórios assinalados na imagem apresentada seguidamente. No fim do preenchimento destes campos, deve o utilizador clicar em "Gravar nova OD".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-33223ddb.png)

No ecrã que surge, o utilizador deve indicar as contas movimento a débito e a crédito com os respetivos montantes e deve clicar em "Gerar Contabilidade".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e4d771f8.png)

Na nova janela, o utilizador deve indicar o Centro de Custo associado à conta *6*. O acesso à listagem dos centros de custo disponíveis no sistema pode ser feito através do botão redondo disponível. Para confirmar o registo da OD deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1301a399.png)


### 1.1. Importação OD
Este tipo de documentos podem ser importados no sistema através da funcionalidade disponível no botão "Importar".

No ecrã aberto, o utilizador deve selecionar o ficheiro CSV da diretoria do seu computador, e testar se este ficheiro está de acordo com a estrutura estipulada através da seleção do botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7798f755.png)

Se não existirem incoerências, as duas janelas do ecrã ficarão preenchidas com os dados do ficheiro selecionado. Em caso de existirem incoerências, as mesmas serão comunicadas ao utilizador através da janela respetiva pelo que deve o utilizador corrigir as mesmas e testar o ficheiro novamente.

Para finalizar a importação deve clicar em "Importa Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4a69feb5.png)

O aspeto do ficheiro CSV a importar deve ser semelhante ao seguidamente apresentado.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2092bf3.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/OD_SNCAP.csv'">Descarregar CSV</button>
</div>

### 1.2. Impressão de Notas de lançamento OD

Para aceder ao ecrã onde o utilizador pode selecionar os documentos OD para impressão, deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bf4b7a1b.png)

No ecrã aberto, deve o utilizador indicar os critérios de pesquisa de documentos:

|Campo| Descrição|
|:--|:--|
|Primeira Data    | Data do primeiro do documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.    |
|Última Data    |Data da último documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.   |
|Ano    | Ano do Exercício.   |
|Número    | Número do documento. Ao indicar um número específico, será apenas apresentado o indicado.   |
|Ordenação    | Critério de Ordenação dos documentos na janela: Número, Valor ou Data. ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b520cb09.png)  |

Finda a indicação dos critérios de pesquisa, deve o utilizador clicar em "Calcular".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-48118c7f.png)

Dos documentos apresentados, deve o utilizador selecionar os que pretende imprimir indicando-o na checkbox respetiva e, de seguida deve clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-89451eb4.png)

O aspeto dos ficheiros PDF gerados será como apresentado seguidamente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-cf4d3e63.png)

### 1.3. Listagens OD

Para aceder ao ecrã que permite gerar listagens de OD's deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0915d94d.png)

No ecrã que é aberto, o utilizador deve preencher os campos assinalados, com os critérios de pesquisa.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-36b514eb.png)

Deve também indicar se pretende que a listagem contemple ou não as contas a débito e a crédito discriminadas através da seleção da _checkbox_ respetiva.

De seguida o utilizador deve selecionar a forma como pretende gerar a listagem: em ficheiro CSV ou em ficheiro PDF.

##### Gerar CSV

Quando esta opção é selecionada, o utilizador deve indicar a diretoria no seu computador onde pretende guardar o ficheiro.

O aspeto do ficheiro exportado será como o do ficheiro apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-07b58737.png)

##### Gerar PDF

Quando esta opção é selecionada, o aspeto do ficheiro PDF gerado é semelhante ao seguidamente apresentado:

</br>**Por Contabilidade Discriminada**

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-14b9e895.png)

**Sem Contabilidade Discriminada**

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8abbffb4.png)

## 2 Ativos não correntes

No âmbito do processo de preenchimento automático dos **ficheiros S3CP AFT, AI e PI**, particularmente os mapas de Adições e Diminuições dos três ficheiros referidos, é necessário discriminar os diversos tipos de Adições e Diminuições possíveis.

Para facilitar a identificação deste tipo de transações, através de operações diversas, foram criados subtipos de OD que devem ser devidamente indicados no momento de registo.

Desta forma, para proceder ao registo destes documentos, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-d25143b5.png)

No ecrã aberto, deve o utilizador inserir os dados relativos ao documento a registar, nomeadamente:

|         Campo          | Obrigatório | Descrição                                                                 |
|:----------------------:|:-----------:|:--------------------------------------------------------------------------|
|          Ano           |     **SIM**     | Indicação do ano no qual será efetuado o registo do documento em questão. |
|        Entidade        |     **SIM**     | Indicação do código de entidade para a qual será efetuado o registo do documento.      |
|  Número do documento   |     Não     | Indicação do Nº de documento. Caso o utilizador deixe este campo em branco ou a zero, o sistema irá atribuir um número ao documento de forma **automática**. Esse número será comunicado ao utilizador no final do registo.  |
|   Data de Documento    |     **SIM**     | Indicação da data de documento.   |
| Data de Contabilização |     **SIM**     | Indicação da data contabilística do documento. Esta data não pode ser inferior à data de documento.    |
|      Importância       |     **SIM**     | Indicação do montante do documento.  |
|         Diário         |     **SIM**     |Indicação do diário. O sistema, por defeito, indica o diário 39 - Diversos.   |
| Atividade/Departamento |     **SIM**     | Indicação do Departamento da instituição. Alerta-se principalmente para organismos que possuem a contabilidade distribuída por mais do que um departamento. |
|        Projeto         |     Não     | Indicação do projeto.|
|      Observações       |     Não     | Indicação de possíveis observações ao documento.    |


</br>Após a indicação dos dados do documento a registar, resta indicar o subtipo da OD a lançar, no sentido do sistema reconhecer a natureza da transação e preencher os mapas de Adições e Diminuições.

</br>Os subtipos de OD possíveis são:

|  Sigla  | Descrição                                 |
|:-------:|:------------------------------------------|
|   CES   | Cessão                                    |
|   DAC   | Dação em pagamento                        |
|  DEVOL  | Devolução ou reversão                     |
| EXPROP  | Expropriação                              |
|  FUSA   | Fusão, cisão, reestruturação - Adição     |
|  FUSD   | Fusão, cisão, reestruturação - Diminuição |
|   INT   | Internas                                  |
| OUTRASA | Outras - Adição                           |
| OUTRASD | Outras - Diminuição                       |
|   TIE   | Transferências internas à entidade        |
|  TTRA   | Transferência ou troca - Adição           |
|  TTRD   | Transferência ou troca - Diminuição       |
|  ABAT   | Abates                                    |

</br>Para finalizar, deve o utilizador clicar em "Gravar Nova OD".

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-87378b2a.png)

No novo ecrã, deve o utilizador indicar as contas e os respetivos montantes: (para exemplo foi selecionado o subtipo de OD - **Dação em pagamento**)

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-dac9d564.png)

Para confirmar o registo é necessário clicar em "Confirmar".


</br>Considerando que não foi atribuído número de documento pelo utilizador, o sistema atribui o nº de forma automática e indica-o através de uma mensagem como a seguidamente apresentada:

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-21561439.png)

Os lançamentos destas tipologias de ODs serão, posteriormente, espelhados nos mapas AFT, AI e PI, da seguinte forma:

| Tipologias                   | AFT | AI  | PI  |
|------------------------------|:---:|:---:|:---:|
| Internas                     |  A  |  A  |  A  |
| Cessão                       |  A  |  A  |  A  |
| Transferência ou troca       | A/D | A/D | A/D |
| Dação em pagamento           |  A  |  A  |  A  |
| Fusão, cisão, reestruturação | A/D | A/D | A/D |
| Outras                       | A/D | A/D | A/D |
| Expropriação                 |  A  | N/a | N/a |
| Devolução ou reversão        |  D  | N/a | N/a |

Legenda: **A** - Adição (movimentos a débito)
         **D** - Diminuições (movimentos a crédito)

</br>A título de exemplo, no mapa S3CP **AI**, as colunas que espelham o registo efetuado são: "Adições" e "Dações em pagamento":

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-f5eb8836.png)

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-455b7184.png)


## 3 Alterações ao Património Líquido

No âmbito do processo de preenchimento automático dos ficheiros S3CP, designadamente, do **ficheiro DAPL**, foram criados subtipos de operações diversas (OD) de forma a identificar transações deste tipo.

Cada registo contabilístico nas subcontas da classe 5 ficam devidamente mapeados (tipificadas) facilitando o preenchimento da Demonstração de Alterações do Património Líquido.

Desta forma, para efetuar estes registos, deve o utilizador seguir o seguintes caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-005242a4.png)

No ecrã aberto, deve o utilizador inserir os dados relativos ao documento a registar, nomeadamente:

|         Campo          | Obrigatório | Descrição |
|:----------------------:|:-----------:  |:----------|
|          Ano           |    **SIM**    | Indicação do ano no qual será efetuado o registo do documento em questão.          |
|        Entidade        |   **SIM**     |  Indicação do código de entidade para a qual será efetuado o registo do documento.           |
|  Número de Documento   |    Não        | Indicação do Nº de documento. Caso o utilizador deixe este campo em branco ou a zero, o sistema irá atribuir um número ao documento de forma **automática**. Esse número será comunicado ao utilizador no final do registo.          |
|   Data de Documento    | **SIM**       | Indicação da data de documento.          |
| Data de Contabilização |  **SIM**      | Indicação da data contabilística do documento. Esta data não pode ser inferior à data de documento. |
|      Importância       |    **SIM**    | Indicação do montante do documento.          |
|         Diário         |    **SIM**    | Indicação do diário. O sistema, por defeito, indica o diário 39 - Diversos.          |
| Atividade/Departamento |   **SIM**     | Indicação do Departamento da instituição. Alerta-se principalmente para organismos que possuem a contabilidade distribuída por mais do que um departamento. |
|        Projeto         |    Não        |   Indicação do Projeto.        |
|      Observações       |    Não        |   Indicação das possíveis observações de documento.        |


</br>Após a indicação dos dados do documento a registar, resta indicar o subtipo da OD a lançar, no sentido do sistema reconhecer a natureza da transação e preencher os mapas de Adições e Diminuições.

</br>Os subtipos de OD possíveis são:

| Sigla | Descrição                                                                              |
|:-----:|:---------------------------------------------------------------------------------------|
|  AAF  | Ajustamentos em Ativos Financeiros                                                     |
| AAIP  | Ajustamento anual do imposto proporcional                                              |
|  AID  | Ajustamentos por impostos diferidos                                                    |
|  ARL  | Aplicação do Resultado Líquido do Período em Resultados Transitados                    |
| ARTAF | Aplicação do Resultado Transitado em Outras Reservas (Ativos financeiros)              |
| ARTOR | Aplicação do Resultado Transitado em Outras Reservas                                   |
| ARTRL | Aplicação do Resultado Transitado em Reservas Legais                                   |
|  DOA  | Doações, herança, legado ou perdido a favor do Estado                                  |
| DOAC  | Doações: (recebidas)                                                                   |
|  ECP  | Entradas para cobertura de perdas                                                      |
| ERVAR | Excedentes de revalorização de respetivas variações (podem ser positivas ou negativas) |
|  RC   | Realizações de capital/Património                                                      |
|  RER  | Realização do Excedente de Revalorização                                               |
| SUBS  | Subsídios                                                                              |
| OAPL  | Outras alterações ao património Líquido                                                |

</br>Para finalizar, deve o utilizador clicar em "Gravar Nova OD".

</br>**Subsídios**

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-9c889753.png)

No novo ecrã, deve o utilizador indicar as contas e os respetivos montantes:


![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-3b306593.png)

Para confirmar o registo é necessário clicar em "Gerar Contabilidade" e "Confirmar".

</br>Considerando que não foi atribuído número de documento pelo utilizador, o sistema atribui o nº de forma automática e indica-o através de uma mensagem como a seguidamente apresentada:

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-5b78934a.png)


**Doações**

</br> Para o caso de se pretender registar o recebimento de uma doação, o processo que se deverá adotar será o seguinte:

>**NOTA**: Deve ser indicado **SEMPRE** o subtipo do documento.

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-7e712caa.png)

No ecrã de recolha de contabilidade devem ser indicados os movimentos correspondentes a esta transação e por fim deve-se clicar em "Confirmar".

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-debfe9f2.png)

O resultado destes registos pode ser observado no mapa **DAPL**:

![](https://spmssicc.github.io/pages/markdown/operacoes_diversas.assets/operacoes_diversas-170996f0.png)
