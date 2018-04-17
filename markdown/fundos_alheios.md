# Fundos Alheios

Este capítulo descreve o registo de adiantamentos ou de despesas/receitas extra-orçamentais.

</br>Para aceder a este menu, o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f23f964a.png)

Este menu permite ao utilizador efetuar registos de despesas e receitas de Fundos Alheios bem como Imprimir e Listar as mesmas.

## 1. Preenchimento de Documento

No ecrã que é aberto, o utilizador tem duas tabulações disponíveis: "Despesa de Fundos Alheios (DA)" e "Receitas de Fundos Alheios (RA)".

Deve por isso selecionar a que se adequa ao pretendido.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2b812dbe.png)

### 1.1 Despesa de Fundos Alheios

Nesta tabulação o utilizador deve preencher os campos obrigatórios, descritos seguidamente, e por fim deve clicar no botão "Gravar novo DA".

|Campo|Descrição|
|:---|:---|
|Número de Entidade   | Indicar a entidade para a qual será registada a DA.   |
|Data de doc:    | Indicar a data de documento.   |
|Data de Contabilização:   |Indicar a data de contabilização. |
|Importância    |Indicar a importância.    |
|Forma de pagamento    |Indicar a forma de pagamento que se pretende efetuar: Tesouraria ou por Transferência Bancária. </br></br> **Transferência Bancária-** Quando esta forma de pagamento é selecionada, o utilizador deve indicar a Instituição Bancária e todos os seus dados inerentes. É também de referir que nesta situação, após o lançamento da DA deve ser emitido o ficheiro da Transferência Bancária no menu respetivo.  |

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ec6dae02.png)

O campo referente ao Número da Despesa pode ser preenchido. No entanto, se o utilizador não o fizer, o sistema no final do registo irá atribuír um número automaticamente.

</br>Ao selecionar “Gravar novo DA” irá ser aberta uma nova janela onde o utilizador deve selecionar as contas e os respetivos montantes. Para consultar as contas disponíveis, o botão situado entre a Conta e a Designação deve ser premido.

Findo o preenchimento dos campos deve clicar no botão "Confirme".

>**NOTA:** Os exemplos são meramente ilustrativos

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0b28ea7f.png)

#### 1.1.1. Importação DA

Estes documentos também podem ser importados no sistema através da opção disponível no botão "Importar"

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ea8c1aa3.png)

Na janela aberta, o utilizador deve selecionar o ficheiro da diretoria do computador e, de seguida, deve clicar em "Ver/ Testar ficheiro" para a validação do mesmo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-92592737.png)

Em caso deste apresentar uma estrutura correta, as duas janelas ficarão preenchidas com os dados do ficheiro. No caso do ficheiro apresentar incoerências, as mesmas ficarão apresentadas na janela respetiva, sendo que o utilizador deverá corrigi-las e testar o ficheiro novamente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6cb5495f.png)

Para confirmar a importação, deve clicar em "Importar Ligação".

O aspeto do ficheiro **CSV** a importar deve ser semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5972698a.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/DA_SNCAP.csv'">Descarregar CSV</button>
</div>

Alerta-se que, em casos em que se preenchem várias linhas para o mesmo número de DA, o valor total da DA é a soma de todas as linhas do documento com contas **diferentes de contas de classe zero**. Seguem abaixo exemplos com as possíveis situações e respetivos totais.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-aac53ff1.png)

Caso o utilizador pretenda importar DAs para serem pagos por Transferência Bancária, deve preencher também os seguintes campos: Conta Bancária, IBAN e Categoria de Motivo.

Na coluna Categoria de Motivo, deve colocar o respetivo  código numérico. A lista de códigos é apresentada seguidamente:

|Código| Sigla| Descrição|
|:--:|:--:|:--|
|1   | SUPP  | Fatura  |   
|2   | SUPP  | Recibo  |   
|3   | TRAD   | Auto   |   
|4   | SALA |Vencimento    |   
|5   | TRAD  | Guia   |   
|7   |TRAD   | Pagamento Serviços  |   
|8   | GOVT  | Pagamentos ao Estado    |   
|11   |  PENS |Pagamentos de Pensão    |   
|12   |SSBE   | Segurança Social   |   
|13   |TAXS   | Pagamento Imposto   |   
|14   | TREA  | Operação Tesouraria   |
|15   | VATX  |Pagamento IVA    |   
|16   |WHLD   |Pagamento IRS (IRS retido)    |   
|17   |GOVT   |Reembolsos Impostos   |   
|20   |OTHR   |PAG IGCP  |   

**Pagamento**

Tendo o lançamento da DA concluído, pode-se agora prosseguir ao lançamento do pagamento.

</br>Para isso, deve o utilizador, no respetivo ecrã, selecionar a tabulação "Fundos Alheios (PG->DA)". No ecrã aberto, deve ser indicada a Entidade e de seguida deve ser clicado o botão "Ver Documentos".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c6328edf.png)

O sistema irá apresentar todos os documentos por regularizar da entidade selecionada. Assim, e para vizualizar os dados do documento, deve o utilizador selecionar o documento pretendido, a DA neste caso, clicando sobre ele duas vezes. Por fim deve clicar no botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3c687a0a.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/da_pag.gif)

Na nova janela aberta devem ser confirmadas as contas e os respetivos montantes. Para validar, deve ser primido o botão "Confirme".

### 1.2. Receita de Fundos Alheios

Nesta tabulação o utilizador deve preencher os campos obrigatórios, descritos seguidamente, e por fim deve clicar no botão "Gravar novo RA".

|Campo|Descrição|
|:---|:---|
|Número de Entidade   | Indicar a entidade para a qual será registada a DA.   |
|Data de doc:    | Indicar a data de documento.   |
|Data de Contabilização:   |Indicar a data de contabilização. |
|Importância    |Indicar a importância.    |

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-17e2f2be.png)

O campo referente ao Número da Receita pode ser preenchido. No entanto, se o utilizador não o fizer, o sistema no final do registo irá atribuír um número automaticamente.

Ao selecionar “Gravar novo RA” irá ser aberta uma nova janela onde o utilizador deve selecionar as contas e os respetivos montantes. Para consultar as contas disponíveis, o botão situado entre a Conta e a Designação deve ser premido.

Findo o preenchimento dos campos deve clicar no botão "Confirme".

>**NOTA:** Os exemplos são meramente ilustrativos

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4bfd2b6f.png)

#### 1.2.1. Importação RA

Estes documentos também podem ser importados no sistema através da opção disponível no botão "Importar"

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-da6073fa.png)

Na janela aberta, o utilizador deve selecionar o ficheiro da diretoria do computador e, de seguida, deve clicar em "Ver/ Testar ficheiro" para a validação do mesmo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-425ac4e4.png)

Em caso deste apresentar uma estrutura correta, as duas janelas ficarão preenchidas com os dados do ficheiro. No caso do ficheiro apresentar incoerências, as mesmas ficarão apresentadas na janela respetiva, sendo que o utilizador deverá corrigi-las e testar o ficheiro novamente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2cc2ffa4.png)

Para confirmar a importação, deve clicar em "Importar Ligação".

O aspeto do ficheiro **CSV** a importar deve ser semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2c31132e.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/RA_SNCAP.csv'">Descarregar CSV</button>
</div>

**Cobrança**

Findo o lançamento da RA, deve-se agora prosseguir ao registo da Cobrança.

No ecrã respetivo, o utilizador deve selecionar a tabulação correspondente ao registo de cobrança de "Receita de Fundos Alheios (CO->RA)". Na janela, devem ser preenchidos os campos do Ano e da Entidade seguindo de seleção do botão "Ver Documentos".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-70a74d11.png)

Na janela inferior do ecrã serão apresentadas todas as receitas por cobrar. A seleção do documento pretendido deve ser efetuada através de um duplo clique em cima do mesmo. Deve também indicar a forma como será cobrado o valor indicado, Tesouraria ou por Transferência Bancária, sendo que se for por transferência bancária o utilizador deve indicar a conta que receberá o montante.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5ac61c2b.png)

Por fim, deve clicar no botão "Gravar novo CO".

No novo ecrã que é aberto, o utilizador deve validar as contas movimento apresentadas automaticamente. Para confirmar deve clicar no botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e26487a8.png)


### 1.3. Encontro de contas

Quando se pretende efetuar um Encontro de Contas deve-se seguir o seguinte processo:

</br>**1. Lançar uma RA**

Deve o utilizador lançar uma RA, pelo processo descrito anteriormente, para uma determinada entidade com um montante estipulado.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e3d9cc7e.png)

</br>**2. Lançar uma DA para a mesma entidade**

Deve, de seguida,  lançar uma DA para a mesma entidade da RA previamente lançada. Ao registar a DA, o utilizador deve indicar que o tipo de pagamento é por **Transferência Bancária** visto que só assim é possivel efetuar o encontro de contas. Por isso deve o utilizador preencher os campos referentes à instituição bancária, ao IBAN e motivo.

</br>**3. Primir no botão "Encontro de Contas"**

Ao clicar neste botão irá ser aberta uma nova janela onde o utiliador deve selecionar a RA, selecionando a checkbox do documento pretendido, e por fim deve clicar em "Confirmar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4978788b.png)

Por fim, deve o utilizador primir o botão "Gravar nova DA".

Na janela que será aberta, o utilizador deve indicar as contas e respetivos montantes e por fim deve confirmar o registo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b3d8112a.png)

De seguida, como se trata de uma despesa, que será paga por Transferência Bancária, deve ser emitido o ficheiro .xml no respetivo menu. Este processo é descrito detalhadamente no capítulo **3.2.8. Transferências Bancárias** deste manual.

</br> É de referir que, aquando a seleção da DA para gerar o ficheiro de Transf. Bancária, o valor da DA que aparece será o valor líquido. Considerando o exemplo tomado, a RA de montante de 100 e a DA de 200, o valor da DA que aparece nas transferências é de 100.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a13b590e.png)

Após ter emitido o ficheiro da tarnsferência bancária segue-se a regularização dos dois documentos, RA e DA, isto é deve-se lançar a cobrança da RA e o pagamento da DA da mesma forma como foi descrito anteriormente.


## 2. Impressão da DA

Para imprimir a/as despesa/s de fundos alheios deve seguir o seguinte caminho:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-924d9073.png)

No ecrã aberto o utilizador deve preencher os seguintes critérios de pesquisa:

|Campo| Descrição|
|:--:|:--|
|Primeira Entidade:  |Primeiro código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.   |
|Última Entidade    | Último código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo. |
|Primeira Data:    |Data do primeiro do documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.   |
|Última Data:    | Data da último documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.  |
|Tipo de Autorização    | Indicar que tipo de autorização de pagamento que se pretende imprimir. ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2742bc65.png)  |


</br> Após terem sido indicados os critérios de pesquisa, deve o utilizador clicar em "Calcular" para que sejam apresentados os documentos que estão em conformidade com os critérios inseridos.

Para selecionar os documentos deve ser preenchida a checkbox respetiva e por fim deve ser clicado em "Imprimir".  

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-57e47936.png)

</br> **Autorização de pagamento**

Quando esta opção é selecionada é gerada uma folha por DA com as contas descriminadas. O documento PDF gerado tem o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-848b1dd8.png)

</br> **Autorização Global de Pagamento**

Quando esta opção é selecionada é apenas gerada uma folha com todas as DA's selecionadas. O documento PDF gerado tem o seguinte aspeto:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-10099246.png)


## 3. Impressão da RA

Para imprimir a ou as receitas de fundos alheios deve seguir o seguinte caminho:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c85ced2a.png)

No ecrã aberto o utilizador deve preencher os seguintes critérios de pesquisa:

|Campo| Descrição|
|:--:|:--|
|Primeira Entidade:  |Primeiro código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.   |
|Última Entidade    | Último código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo. |
|Primeira Data:    |Data do primeiro do documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.   |
|Última Data:    | Data da último documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.  |

</br> Após terem sido indicados os critérios de pesquisa, deve o utilizador clicar em "Calcular" para que sejam apresentados os documentos que estão em conformidade com os critérios inseridos.

Para selecionar os documentos, deve ser preenchida a checkbox respetiva e por fim deve ser clicado em "Imprimir".  
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1f466f8c.png)

O aspecto do ficheiro PDF gerado é o seguinte:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-59a5e06e.png)

## 4. Listagem despesa de fundos Alheios

Para aceder ao ecrã que permite realizar uma listagem da despesa de fundos alheios, o utilizador deve seguir o caminho:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0baab926.png)

No ecrã aberto, o utilizador deve indicar qual o tipo de documento que será o principal e qual o que será secundário. Em caso de o principal for a DA e o secundário o PG, o ficheiro irá listar, dentro dos critérios posteriormente estabelecidos, as DA's com os PG's associados.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c79d1a10.png)

Conforme o tipo de documento principal selecionado o utilizador deve indicar, de seguida, os critérios de pesquisa, nomeadamente, o ano do exercício, o intervalo das entidades e datas e o intervalo dos documentos principais que pretende visualizar. Também deve indicar a forma como pretende ordenar os documentos: pelo número de documento ou por conta.

Por fim deve selecionar a diretoria no computador onde pretende guardar o ficheiro CSV e deve clicar em "Ficheiro".

O aspeto do Ficheiro gerado será como o seguidamente apresentado:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-11a3cf0a.png)

## 5. Listagem receita de fundos Alheios

Para aceder ao ecrã que permite realizar uma listagem da despesa de fundos alheios, o utilizador deve seguir o caminho:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0e7ae171.png)

O processo de geração do ficheiro é igual ao descrito no capítulo anterior: 4. Listagem despesa de fundos alheios.
