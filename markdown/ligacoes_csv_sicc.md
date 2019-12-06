# Ligações CSV no SICC SNC-AP

O sistema SICC SNC-AP possibilita o registo de diversos documentos contabilísticos, que são a base para a produção de peças contabilísticas – mapas de relato mensal.

</br>Estes documentos podem ser registados no sistema de forma manual, beneficiando dos automatismos de registo do sistema, ou via integração de ficheiros de formato CSV.

</br>Seguidamente estão apresentados todos os documentos que podem ser registados no sistema SIC SNC-AP.

</br>**Documentos Despesa**

| Documento | Designação                           |
|:---------:|:-------------------------------------|
|    AB     | Alteração/Anulação de compromisso    |
|    AC     | Anulação de Faturas de Fornecedores  |
|    AF     | Anulação de Faturas                  |
|    AL     | Alteração aos Compromissos Assumidos |
|    AM     | Alteração ao Cabimento               |
|    AP     | Autorização de Pagamento             |
|    CB     | Cabimentos                           |
|    CM     | Compromissos                         |
|    CP     | Compromissos Assumidos               |
|    DA     | Despesa fundos alheios               |
|    DF     | Débito sobre a fatura                |
|    NC     | Notas de crédito                     |
|    P1     | Fatura em Receção e Conferência      |
|    P2     | Fatura Conferida do Fornecedor       |
|    PG     | Pagamentos                           |

</br>**Documentos Receita**

| Documento | Designação             |
|:---------:|:-----------------------|
|    AD     | Anulação de devedores  |
|    AR     | Anulação de Receita    |
|    CC     | Créditos a Clientes    |
|    CD     | Cobrança duvidosa      |
|    CF     | Crédito sobre a fatura |
|    CI     | Créditos incobráveis   |
|    CO     | Cobranças              |
|    FD     | Faturas de devedores   |
|    GR     | Guia de receita        |
|    OR     | Outras receitas        |
|    RA     | Receita fundos alheios |

</br>**Outros Documentos**

| Documento | Designação                 |
|:---------:|:---------------------------|
|    OO     | Orçamento exec. orçamental |
|    PE     | Proposta orç. exploração   |
|    PO     | Proposta orç. ex. orçam.   |
|    OD     | Operações Diversas         |


## 1 Importação de Orçamento

Na aplicação SICC SNC-AP pode ser importado o Orçamento Ordinário, as respetivas alterações e o Orçamento Económico. Estes orçamentos podem ser integrados através de ficheiros CSV, de acordo com os _layouts_ apresentados seguidamente.

### 1.1 Orçamento Ordinário

Para efetuar a importação do orçamento ordinário deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8570877f.png)

De seguida, deve o utilizador clicar no botão “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-7328798a.png)

No novo ecrã aberto, o utilizador deve escolher do diretório de origem, o ficheiro que pretende importar. Seguidamente deve testar/validar o ficheiro a integrar, através da seleção do botão “Ver/Testar Ficheiro”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-55294290.png)

Quando o ficheiro tem a estrutura correta, os campos do ecrã aparecem preenchidos com os elementos do ficheiro importado. Por fim o utilizador deve confirmar a importação através da seleção do botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-505866f0.png)

No caso de o ficheiro ter erros, estes são reportados na janela criada para o efeito. Estes erros têm de ser corrigidos e o ficheiro tem de ser novamente testado.

O ficheiro CSV a ser importado deve ter o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-a7726889.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PO_SNCAP.csv'">Descarregar CSV</button>
</div>

### 1.2 Orçamento Económico

Para efetuar a importação do orçamento ordinário deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-15b7a60d.png)

De seguida, deve o utilizador clicar em “Importar".

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d8200d9a.png)

No novo ecrã aberto, o utilizador deve escolher do diretório de origem, o ficheiro que pretende importar. Seguidamente deve validar o ficheiro a integrar, através do clique no botão “Ver/Testar Ficheiro”.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-99f75ffd.png)

Quando o ficheiro tem a estrutura correta, os campos do ecrã aparecem preenchidos com os elementos do ficheiro importado. Por fim o utilizador deve confirmar a importação através da seleção do botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-d4737d43.png)

No caso de o ficheiro ter erros, estes são reportados na janela criada para o efeito. Estes erros têm de ser corrigidos e o ficheiro tem de ser novamente testado.

</br>O ficheiro CSV a ser importado deve ter o seguinte aspeto:

>**NOTA:** A amarelo estão destacados os campos obrigatórios.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-34975321.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PE_SNCAP.csv'">Descarregar CSV</button>
</div>


## 2 Importação de Documentos de Despesa

### 2.1 Cabimentos (CB)

Os documentos do tipo CB podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4ab45932.png)

 No ecrã aberto, deve o utilizador clicar em “Importar”.

 ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ef856afa.png)

 Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

 ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-29a883a8.png)

 O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

 > **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

 ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8fafadce.png)

 <div style="height:40px">
 <button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CB_SNCAP.csv'">Descarregar CSV</button>
 </div>

 Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

 ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-7ea48c75.png)

 Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

 Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

 ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-edc5fce9.png)

 Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

 ![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

### 2.2 Alteração de Cabimentos (AM)

Para registar documentos relativos a alterações ao cabimento (AM) deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-19410ace.png)

No ecrã aberto, deve o utilizador clicar em “Importar”:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-ae9a8970.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-cb3a9570.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f39f69dd.png)


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AM_SNCAP.csv'">Descarregar CSV</button>
</div>


### 2.3 Compromissos (CM)

Os documentos do tipo CM podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4ab45932.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-a98ec4bd.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.


![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6278bdcf.png)

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5b600345.png)


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CM-SNCAP.csv'">Descarregar CSV</button>
</div>


### 2.4 Alteração do Compromisso (AB)

Os documentos do tipo AB podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c02d02d9.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-67e7c8bf.png)


Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.


![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-af2ef553.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5624da01.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AB_SNCAP.csv'">Descarregar CSV</button>
</div>

### 2.5 Compromissos Assumidos (CP)

Os documentos do tipo CP podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d996a102.png)

No ecrã aberto, deve o utilizador selecionar o **separador** “Compromisso Assumido (CP)”.

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-8a16289b.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-04fc2b1a.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-03c76ca6.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CP_SNCAP.csv'">Descarregar CSV</button>
</div>


### 2.6 Alteração ao Compromisso Assumido (AL)

Os documentos do tipo AL podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d72a6934.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-807bbd2f.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b4c65ee0.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-9f1ebbcb.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AL_SNCAP.csv'">Descarregar CSV</button>
</div>

### 2.7 Faturas em Receção e Conferência (P1)

Os documentos do tipo P1 podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d72a6934.png)

No ecrã aberto deve o utilizador selecionar o separador designado por: “Processado - F.Rec.\Conf. (P1)”.
De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-5a24f2b5.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.


![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-c16ab3e1.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b47f305a.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P1_SNCAP.csv'">Descarregar CSV</button>
</div>


### 2.8 Faturas Processadas (P2)

Os documentos do tipo P2 podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d72a6934.png)

No ecrã aberto deve o utilizador selecionar o separador designado por: “Processado - F.Confer. (P2)”

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-610768c4.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-a7826854.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-241d6bb8.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P2_SNCAP.csv'">Descarregar CSV</button>
</div>

### 2.9 Notas de Crédito (NC)

Os documentos do tipo NC podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-fe475f0b.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-b97948c6.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8971096d.png)

O aspeto do ficheiro **CSV** a ser importado é semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e3438c35.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/NC_SNCAP.csv'">Descarregar CSV</button>
</div>

>**NOTA:** Neste ficheiro de importação apenas podem ser integradas as notas de crédito convencionais, sendo que as NC-RAP apenas podem ser introduzidas no sistema de forma manual.

### 2.10 Crédito sobre Faturas (CF)

Os documentos do tipo CF podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-7b23d5b0.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-05be6f91.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8d01cbea.png)


### 2.11 Débito sobre Faturas (DF)

Os documentos do tipo DF podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d3355ef7.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-6888dd3a.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-11fb6a67.png)

O aspeto do ficheiro CSV a ser importado deve ser semelhante ao seguidamente apresentado.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1c074965.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/DF_SNCAP.csv'">Descarregar CSV</button>
</div>

### 2.12 Autorização de Pagamento (AP)

Os documentos do tipo AP podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-de23f2bc.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-1224abde.png)


Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.


![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-141ac688.png)

Caso o utilizador pretenda importar APs para serem pagos por Transferência Bancária, deve preencher também os campos: Conta Bancária, IBAN e Categoria de Motivo.
Na coluna Categoria de Motivo, deve indicar o respetivo código numérico.
Seguidamente é apresentada a lista de códigos numéricos a utilizar, conforme o motivo pretendido.


| Código | Sigla | Descrição                               |  
|:------:|:-----:|:----------------------------------------|
|   1    | SUPP  | Fatura                                  |   
|   2    | SUPP  | Recibo                                  |   
|   3    | TRAD  | Auto                                    |   
|   4    | SALA  | Vencimento                              |   
|   5    | TRAD  | Guia                                    |  
|   7    | TRAD  | Pagamento Serviços                      |   
|   8    | GOVT  | Pagamentos ao Estado                    |   
|   11   | PENS  | Pagamentos de Pensão                    |   
|   12   | SSBE  | Segurança Social                        |   
|   13   | TAXS  | Pagamento Imposto                       |   
|   14   | TREA  | Operação Tesouraria                     |   
|   15   | VATX  | Pagamento IVA                           |   
|   16   | WHLD  | Pagamento IRS (IRS retido)              |   
|   17   | GOVT  | Reembolsos Impostos                     |   
|   20   | OTHR  | PAG IGCP                                |   
|   21   | PDUC  | Transação referente ao pagamento de DUC |   
|   21   | PTSU  | Transação referente ao pagamento de TSU |   


O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-376ff731.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AP_SNCAP.csv'">Descarregar CSV</button>
</div>


### 2.13 Despesa de Fluxos Financeiros (DA)

Os documentos do tipo DA podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-42f137dd.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-ff590818.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.


![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6cb5495f.png)


O aspeto do ficheiro **CSV** a importar deve ser semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/fundos_alheios.assets/fundos_alheios-b0a3eddb.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/DA_SNCAP.csv'">Descarregar CSV</button>
</div>


Alerta-se que, em casos em que se preenchem várias linhas para o mesmo número de DA, o valor total da DA é a soma de todas as linhas do documento com contas **diferentes de contas de classe zero**. Seguem abaixo exemplos com as possíveis situações e respetivos totais.

![](https://spmssicc.github.io/pages/markdown/fundos_alheios.assets/fundos_alheios-b19eb36a.png)

Caso o utilizador pretenda importar DAs para serem pagos por Transferência Bancária, deve preencher também os seguintes campos: **Conta Bancária, IBAN e Categoria de Motivo**.

Na coluna Categoria de Motivo, deve colocar o respetivo  código numérico. A lista de códigos é apresentada seguidamente:

| Código | Sigla | Descrição                               |   
|:------:|:-----:|:----------------------------------------|
|   1    | SUPP  | Fatura                                  |   
|   2    | SUPP  | Recibo                                  |   
|   3    | TRAD  | Auto                                    |   
|   4    | SALA  | Vencimento                              |   
|   5    | TRAD  | Guia                                    |   
|   7    | TRAD  | Pagamento Serviços                      |   
|   8    | GOVT  | Pagamentos ao Estado                    |   
|   11   | PENS  | Pagamentos de Pensão                    |   
|   12   | SSBE  | Segurança Social                        |   
|   13   | TAXS  | Pagamento Imposto                       |   
|   14   | TREA  | Operação Tesouraria                     |   
|   15   | VATX  | Pagamento IVA                           |   
|   16   | WHLD  | Pagamento IRS (IRS retido)              |   
|   17   | GOVT  | Reembolsos Impostos                     |   
|   20   | OTHR  | PAG IGCP                                |   
|   21   | PDUC  | Transação referente ao pagamento de DUC |   
|   21   | PTSU  | Transação referente ao pagamento de TSU |   


### 2.14 Pagamento (PG)


Os documentos do tipo PG podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](ttps://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-aed610c1.png)

De seguida deve o utilizador clicar em “Importar”.

![](ttps://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-cce62fea.png)

Os passos seguintes são:

1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-70996b6c.png)

O aspecto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2d59f8a4.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PG_SNCAP.csv'">Descarregar CSV</button>
</div>

### 2.15 Anulação de Faturas (AC)

Os documentos do tipo AC podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-e912e051.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-2f76fa15.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ba9bd3b4.png)

O aspeto do ficheiro a importar deve ser como o do apresentado seguidamente:

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-7472eccd.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AC_SNCAP.csv'">Descarregar CSV</button>
</div>

>**Nota:** A chave orçamental a ser introduzida para AC, varia com o documento que este regulariza, nomeadamente:
            </br> - Para AC que regularizam P2 e DF, a chave deve ser a parametrizada para a **conta a crédito** do AC.
            </br> - Para AC que regularizam NC e CF, a chave deve ser a parametrizada para a **conta a débito** do AC.


### 2.16 Ciclo de Despesa (DSP)


Os documentos do tipo DSP podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-3284e075.png)

De seguida deve o utilizador clicar em “Ciclo da Despesa”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-7e1346e5.png)

No ecrã que é aberto, ecrã este que é semelhante ao ecrã de importações descritas anteriormente, deve o utilizador selecionar da diretoria, o ficheiro em **formato CSV**. De seguida deve pressionar no botão "Ver/Testar Ficheiro" para que o sistema valide o ficheiro que se pretende importar.

Após ter sido concluída a validação do ficheiro, no caso de este apresentar a estrutura correta, os campos do ecrã irão ficar preenchidos com dados do ficheiro. No caso do ficheiro apresentar erros, estes irão ser reportados na janela respetiva e será gerada uma mensagem informativa.
Os erros reportados devem ser corrigidos e o ficheiro atualizado deve ser novamente validado.

</br>Por fim, no sentido de confirmar e executar a importação de dados, deve o utilizador pressionar no botão "Importa Ligação".

O aspeto do ficheiro CSV a ser importado deve ser semelhante ao seguidamente apresentado:

> **Nota:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-983ab8f8.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CSV_DSP_exemplo_1.csv'">Descarregar CSV</button>
</div>

Este ficheiro pode ser utilizado para integrar os seguintes conjuntos de documentos:
- CB
- 	CB + CM
- 	CB + CM + CP
- 	CB + CM + CP + P1
- 	CB + CM + CP + P1 + P2
- 	CB + CM + CP + P2

> **NOTA:** Os campos "Conta a crédito P1" e "Conta a crédito P2" são de preenchimento obrigatório quando se importam P1 e P2 respetivamente. Caso estes campos não estejam preenchidos, o sistema gera erros com essa indicação.


Os números dos documentos são **NUMÉRICOS**. Caso seja necessário incluir letras, o campo “Série” pode ser utilizado para esse fim.

</br> As contas, os classificadores económicos, os centros de custo bem como os elementos da chave orçamental devem estar parametrizados no sistema no ano dos documentos a transitarem.
Os elementos da chave orçamental no ficheiro devem estar coerentes com os parametrizados no sistema.

</br>Alerta-se principalmente para os elementos constituídos por zeros, o número de zeros deve ser igual e os zeros à esquerda devem ser mantidos. A colocação da plica " ' " antes do zero à esquerda facilita.


>**NOTA:** Os campos Data documento e Data Contabilística são referentes ao CB, pelo que todos os documentos que regularizam este, ao serem importados através deste ficheiro, ficam com esta data.

Desta forma, para manter as datas ORIGINAIS das faturas, nesta transição de documentos, pode optar por uma das seguintes opções: 	

1.	Numerar o CB, CM e CP com o mesmo número da fatura; 		
2.	Atribuir um número interno, sequencial, ao CB, CM e CP, mantendo a numeração original das faturas;		
3.	Importar através do DSP os documentos CB, CM e CP, com a numeração e datas originais. E importar as faturas num ficheiro em separado, específico para este fim.


As contas utilizadas nestes documentos devem estar de acordo com o **SNC-AP**.

>**NOTA:** Considerando que este ficheiro cria CB, CM, CP, P1 e P2 simultaneamente, para otimizar o processo de integração, sugerimos que o tamanho do mesmo não exceda as **2000 linhas**.

Segue abaixo uma explicação de situações possíveis aquando a importação do ciclo de despesa.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0c0b170a.png)

- A situação A representa o caso quando para o mesmo cabimento (CB) existem várias faturas (P2);
- A situação B representa o caso em que os documentos contemplam várias contas.

Para ambas as situações, está também apresentada a forma como são calculados os valores dos documentos quando são "desdobrados" em várias linhas.

## 3 Importação de Documentos de Receita

### 3.1 Faturas Devedores (FD)

Os documentos do tipo FD podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-543fb0f8.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-07ca1311.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6059bf69.png)

O aspeto do ficheiro a importar deve ser semelhante ao seguidamente apresentado.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_receita.assets/ciclo_receita-c4d8977f.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/FD_SNCAP.csv'">Descarregar CSV</button>
</div>


### 3.2 Guias de Receita (GR)

Os documentos do tipo GR podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-30e18f76.png)


De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-a4786b81.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.


![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-56186dfa.png)

O aspeto do ficheiro a importar deve ser semelhante ao seguidamente apresentado.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a52ce6af.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/GR_SNCAP.csv'">Descarregar CSV</button>
</div>



### 3.3 Créditos a Clientes (CC)

Os documentos do tipo CC podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-23c2bfa5.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-7eaafa0a.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-882c6423.png)

O aspeto do ficheiro **CSV** a importar deve ser semelhante ao seguidamente apresentado.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_receita.assets/ciclo_receita-35349d7a.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CC_SNCAP.csv'">Descarregar CSV</button>
</div>

>**NOTA:** Neste ficheiro de importação apenas podem ser integradas as notas de crédito convencionais, sendo que as CC-Reembolsos/Restituições apenas podem ser introduzidas no sistema de forma manual.

### 3.4 Cobranças Duvidosas (CD)

Os documentos do tipo CD podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-b9f1faa8.png)


No ecrã aberto, deve estar selecionado o separador “Cobrança Duvidosa (CD)”.
De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-366da0ac.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/ciclo_receita.assets/ciclo_receita-c0f88a65.png)

O aspeto do ficheiro **CSV** a ser importado deve ser semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_receita.assets/ciclo_receita-bafbde4e.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CD_SNCAP.csv'">Descarregar CSV</button>
</div>

### 3.5 Receita de Fluxos Financeiros (RA)

Os documentos do tipo RA podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-2f10a608.png)

No ecrã aberto, deve o utilizador selecionar o separador designado por: “Receitas de Fundos Alheios”.
De seguida deve o utilizador clicar em “Importar”.

![](vligacoes_csv_sicc.assets/ligacoes_csv_sicc-2fc23512.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2cc2ffa4.png)

O aspeto do ficheiro **CSV** a importar deve ser semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/fundos_alheios.assets/fundos_alheios-30eb3d61.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/RA_SNCAP.csv'">Descarregar CSV</button>
</div>



### 3.6 Cobranças (CO)

Os documentos do tipo CO podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-7041ec41.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-d1173fd0.png)


Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7aca8a97.png)

O aspeto do ficheiro **CSV** a ser importado deve ser semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-02b4358a.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CO_SNCAP_1.csv'">Descarregar CSV</button>
</div>

### 3.7 Outras Receitas (OR)

Os documentos do tipo OR podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-28c3c7d4.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-f29bbc67.png)


Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3806f752.png)

O aspeto do ficheiro **CSV** a ser importado é semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5e8572c4.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/OR_SNCAP.csv'">Descarregar CSV</button>
</div>

### 3.8 Anulações (AD)

Os documentos do tipo AD podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-4b284e21.png)

No ecrã aberto, deve estar selecionado o separador “Anulações (AD)”.
De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-2cef7c99.png)

Na nova janela aberta, deve o utilizador selecionar da diretoria do seu computador o ficheiro a importar e clicar em "Ver/ Testar ficheiro" para que o sistema valide a estrutura do mesmo.
Caso esta corresponda aos critérios de integração, as duas janelas disponíveis ficarão preenchidos com os dados do ficheiro. Caso apresenta incoerências, as mesmas serão comunicadas ao utilizador através da janela destinada para o efeito.

</br>Para finalizar a importação, deve o utilizador clicar em "Importar Ligação".

O aspeto do ficheiro a importar deve ser como o do apresentado seguidamente:

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_receita.assets/ciclo_receita-2fe9f13f.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AD_SNCAP.csv'">Descarregar CSV</button>
</div>

>**Nota:** A chave orçamental a ser introduzida para AD, varia com o documento que este regulariza, nomeadamente:
            </br> - Para AD que regularizam CC, a chave deve ser a parametrizada para a **conta a crédito** do AD.
            </br> - Para AD que regularizam FD, a chave deve ser a parametrizada para a **conta a débito** do AD.


## 4 Importação de Operações diversas (OD)

Os documentos do tipo OD podem ser importados no sistema. Para o efeito, deve o utilizador seguir o seguinte caminho da aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-554c8188.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-e3bae94d.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4a69feb5.png)

O aspeto do ficheiro CSV a importar deve ser semelhante ao seguidamente apresentado.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2092bf3.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/OD_SNCAP.csv'">Descarregar CSV</button>
</div>

## 5 Importação de Entidades

As entidades, no menu Gestão de Entidades, podem ser criadas através da importação do ficheiro CSV. Para o efeito, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-0c2697f9.png)

De seguida deve o utilizador clicar em “Importar”.

![](https://spmssicc.github.io/pages/markdown/ligacoes_csv_sicc.assets/ligacoes_csv_sicc-a2a5ff2f.png)

Os passos seguintes são:
1.	Selecionar da diretoria o ficheiro que se pretende integrar;
2.	Clicar em “Ver/Testar Ficheiro” para validar o ficheiro a importar;
3.	Corrigir os erros caso estes existam e voltar a clicar em “Ver/Testar Ficheiro”;
4.	Clicar em “Importar Ligação”.

![](https://spmssicc.github.io/pages/markdown/assets/parametrizacao-018bca45.png)

O aspeto do ficheiro a importar deve ser semelhante ao seguidamente apresentado.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/parametrizacao.assets/parametrizacao-3d22e3bb.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/importa_entidades.csv'">Descarregar CSV</button>
</div>

##### Atualização de dados de entidades

Caso se pretenda atualizar os dados de várias entidades de uma vez só, o utilizador pode efetuar esse processo através da integração do mesmo ficheiro CSV no mesmo ecrã da aplicação que é utilizado para criação de novas entidades.

</br>Para o sistema assumir que a informação a integrar é para atualização de dados e não para criar entidades novas, adaptando as validações de integração, deve o utilizador selecionar, imperativamente, a _checkbox_ "Atualizar entidades".

![](https://spmssicc.github.io/pages/markdown/parametrizacao.assets/parametrizacao-e4ef1cc9.png)

Os campos obrigatórios do ficheiro CSV a importar são os mesmos da criação de entidades novas, pelo que todos estes campos devem estar preenchidos mesmo se a informação for para manter.

A título de exemplo pretende-se atualizar a morada da entidade de código 123 que tem a seguinte informação no sistema: (estão destacados os campos que devem constar no ficheiro de importação)

![](https://spmssicc.github.io/pages/markdown/parametrizacao.assets/parametrizacao-a0175fb3.png)

O ficheiro de importação deverá ter, **obrigatoriamente**, a seguinte informação:

![](https://spmssicc.github.io/pages/markdown/parametrizacao.assets/parametrizacao-3d8974de.png)

Porém ao integrar o ficheiro apenas com esta informação, os campos referentes aos IBANs serão apagados, pois no ficheiro vêm em branco.

Para manter esta informação, esta deve estar contemplada no ficheiro a integrar. Assim, toda a informação já inserida no sistema que seja para manter, deve estar contemplada no ficheiro CSV a integrar.

![](https://spmssicc.github.io/pages/markdown/parametrizacao.assets/parametrizacao-a528cb85.png)

>**NOTA:** Caso neste ficheiro de atualização de dados esteja uma entidade inexistente (com código novo), essa entidade é criada.
