<div class="cabecalho"><img src="https://spmssicc.github.io/pages/img/logos/SPMS2016B_272x105.png">
Gestão de Tesouraria</div>

Este capitulo pretende descrever o processo de cálculo e consulta da Folha de Caixa bem como efetuar oregisto de Depósitos e Levantamentos.

> Recomenda-se o uso da tecla **_TAB_** para a navegação pelos campos dos ecrãs do sistema. Esta forma de navegação garante que todos os campos obrigatórios sejam preenchidos e validados permitindo o posterior desbloqueio de outros campos.

## 1. Folha de Caixa

Para aceder ao ecrã relativo à folha de caixa deve o utilizador seguir o seguinte caminho:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-82d65e75.png)

No ecrã que é aberto o utilizador deve preencher os seguintes campos:

|Campo| Descrição|
|:--|:--|
| Ano   | Indicação do ano dos documentos contabilizados para a folha de caixa.  |
|Do dia:    |Indicação da data a partir da qual se pretendem extrair dados para a folha de caixa.  |
|Ao dia:   | Indicação da data até a qual se pretendem extrair dados para a folha de caixa.  |
|Parametrização   | Indicação das contas que serão contabilizadas para a designação descrita do lado esquerdo. ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bc6acd73.png)  |

</br>Para efetuar o cálculo da folha de caixa deve o utilizador, após ter preenchido todos os parâmetros, pressionar no botão "Calcular".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/folha_caixa.gif)

Quando o cálculo da folha de caixa finalizar, o utilizador pode guardar os dados em formato de ficheiro CSV, na diretoria indicada, ou poderá imprimi-los.

**</br>Imprimir**

Quando a opção "Imprimir" for selecionada o aspeto do ficheiro PDF gerado é igual ao seguidamente apresentado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bb249f37.png)

Nesta Folha de Caixa podem-se observar alguns movimentos (Constituição do Fundo de Maneio (OD), Pagamentos (PG), Cobrança (CO), Depósitos e Levantamentos) destacados na seguinte imagem:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b6c28f21.png)

## 2. Depósitos/Levantamentos
Para aceder ao ecrã relativo ao registo de Depósitos/Levantamentos o utilizador deve seguir o caminho:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8941e97b.png)

Irá ser aberto um ecrã onde o utilizador deve preencher os dados relativos ao registo contabilistico de um depósito/levantamento. Estes movimentos, depósitos e levantamentos, são relativos à CONTA BANCÁRIA , isto é, quando se pretende registar um depósito, é feito um levantamento em caixa que é posteriormente depositado na Conta Bancária. Quando se pretende registar um levantamento, é feito um levantamento daConta Bancária que é posteriormente depositado em caixa.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1ef27d4e.png)

### 2.1.Registo de Depósito

Para registar um depósito deve o utilizador preencher os seguintes campos obrigatórios: Número de Documento, Data de Documento, Data de Contabilização, Importância, Diário, Tipo de Movimento (neste caso Depósito) e Inst. Bancária. Se o campo relativo ao Número de Documento não for preenchido pelo utilizador, o sistema irá atribuir um número de forma automática no final do registo. O Diário pode ser selecionado dentro da lista disponível no botão redondo ao lado do campo.
As instituições bancárias das entidades disponíveis podem ser consultadas através do botão redondo disponível entre o campo da conta do banco e o campo da designação do banco.
Por fim deve o utilizador selecionar o botão "Gravar nova OD".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-851aa204.png)

Ao clicar sobre "Gravar nova OD" irá surgir uma nova janela com os movimentos contabilísticos.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-044abd95.png)

O sistema automaticamente irá mostrar as contas respetivas com os valores correspondentes. Estes dados devem ser verificados e, em caso de estarem corretos deve o utilizador confirmá-los através da seleção do botão "Confirme".

</br>As contas apresentadas automaticamente pelo sistema podem ser desdobradas se o utilizador assim o pretender. Para tal, deve o utilizador alterar o valor da conta que pretende desdobrar e na linha livre seguinte introduzir a conta e o seu valor correspondente. Por exemplo, como se pode verificar na imagem seguinte, a conta 1221 foi desdobrada em duas linhas, cada uma com valor de 50€ perfazendo o total de 100€.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d297af64.png)

O lançamento efetuado pode agora ser consultado, guardado em PDF ou abatido. Para o fazer, deve o utilizador inserir o Número do Documento no campo respetivo e selecionar a ação pretendida.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-de79cb61.png)

1.Ao selecionar "PDF" irá ser aberta uma nova janela onde o utilizador poderá visualizar um documento com o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fa668d69.png)

2.Ao selecionar "Consulta" irá ser aberto um novo ecrã onde o utilizador poderá visualizar as contas que foram lançadas:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-170e840d.png)

3.Ao selecionar "Abater" o utilizador irá eliminar o registo efetuado.

</br>Este movimento fica espelhado na Folha de Caixa e no Extrato de Contas. A forma como este movimento aparece é descrita seguidamente.

**</br>Folha de Caixa**
</br>Para visualizar este movimento na Folha de Caixa deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6754429c.png)

De seguida, o utilizador deve selecionar o período de tempo que pretende visualizar e pressionar no botão "Calcular".

Após o cálculo da Folha de Caixa estar concluído, o ecrã respetivo irá ser preenchido com os dados relativos à mesma. De seguida, esta informação pode ser guardada num ficheiro CSV ou impressa.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9ea074cc.png)

Quando a opção "Imprimir" é selecionada o aspeto do ficheiro PDF que é gerado é igual ao apresentado seguidamente. O movimento lançado no exemplo anterior pode ser visualizado no rectângulo vermelho.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5f020140.png)

**Extrato de Contas**
</br>Para visualizar o movimento no Extrato de Contas deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ef257541.png)

De seguida, o utilizador deve indicar os critérios de pesquisa do extrato, nomeadamente as datas, as contas, as entidades, o tipo de atividade e os números de contribuinte. Finda a indicação dos critérios, o utilizador seleciona o que pretende fazer com o extrato, guardá-lo na forma de ficheiro CSV ou imprimi-lo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c1af6153.png)

Quando a opção "Imprimir" é selecionada, o aspeto do ficheiro PDF que é gerado será igual ao seguidamente apresentado.
**</br>Nota:** Os movimentos registados no exemplo anterior estão destacados com o rectângulo laranja.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8c9cd6ab.png)

### 2.2. Registo de Levantamento

Para registar um depósito deve o utilizador preencher os seguintes campos obrigatórios: Número de Documento, Data de Documento, Data de Contabilização, Importância, Diário, Tipo de Movimento (neste caso Levantamento) e Inst. Bancária. Se o campo relativo ao Número de Documento não for preenchido pelo utilizador, o sistema irá atribuir um número de forma automático no final do registo. O Diário pode ser selecionado dentro da lista disponível no botão redondo ao lado do campo.
As instituições bancárias da entidade disponíveis onde neste caso será eftuado o depósito, podem ser consultadas através do botão redondo disponível entre o campo da conta do banco e o campo da designação do banco.
Por fim deve o utilizador selecionar o botão "Gravar nova OD".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-eca071e7.png)

Ao gravar uma nova OD irá surgir uma janela nova onde estarão apresentados automaticamente os movimentos contabilísticos. Deve o utilizador verificar os dados e no caso de estes estarem corretos confirmar o lançamento através da seleção do botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5775c46e.png)

É de referir que, neste lançamento as contas de movimento podem ser desdobradas como demonstrado em 2.1..

O registo efetuado pode agora ser consultado, guardado em PDF ou abatido. Para efetuar qualquer uma destas ações, o utilizador deve inserir o Número do Documento no campo respetivo e selecionar a ação pretendida.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-31fc4fee.png)

O registo de um levantamento também é espelhado na Folha de Caixa e no Extrato de Contas de forma semelhante como demonstrado em 4.2.1..

## Notas

Nesta janela apenas podem ser consultadas OD's resultandes de um movimento contabilístico de depósito/levantamento. No caso de se pretender consultar uma OD existente mas que não seja de depósito/levantamento o sistema irá mostrar uma mensagem como a seguidamente apresentada.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c7cda5e6.png)

O mesmo acontece se se pretender consultar uma OD existente mas lançada através de Depósitos/Levantamentos na janela de Recolha de Operações Diversas. O sistema gera uma mensagem como a apresentada seguidamente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4169174c.png)
