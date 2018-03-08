<div class="cabecalho"><img src="https://spmssicc.github.io/pages/img/logos/SPMS2016B_272x105.png">
Ciclo de Despesa</div>

Este capítulo tem por objetivo descrever o processo de registo de todos os documentos inerentes ao ciclo de despesa, isto é, desde o registo do cabimento até ao pagamento da fatura ao fornecedor.

> Recomenda-se o uso da tecla **_TAB_** para a navegação pelos campos dos ecrãs do sistema. Esta forma de navegação garante que todos os campos obrigatórios sejam preenchidos e validados permitindo o posterior desbloqueio de outros campos.

## 1. Cabimento (CB)

Esta opção permite, consultar ou criar um novo documento de Cabimento e com base em critérios selecionados pelo utilizador.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4ab45932.png)

Ao selecionar Cabimentos/Verificação Prévia, irá surgir o seguinte ecrã, cujo objetivo é a criação de um Cabimento (CB), conforme imagem abaixo:

![img_57a.gif](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_57a.gif)

O seu registo, o processo de cabimentação não sofre qualquer alteração, continuando a ter registar a referência o orçamento anual da entidade líquido de cativos devendo ser cabimentadas todas as despesas prováveis.

![img_58.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_58.png)

A gravação do CB abre novo ecrã, onde teremos um botão de ajuda no preenchimento dos seguintes campos obrigatórios:

![img_60.gif](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_60.gif)

|Campo|Obrigatoriedade|Descrição|
|:----|:--------------|:---------|
|Classificador Económico|**Sim**| No método de registo de contas patrimoniais, disponível a partir do menu de Parametrização>Instituição>Configurações ![9561c58b](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/processos_snc_ap-9561c58b.png), o classificador económico é mostrado automaticamente através da conta patrimonial, de acordo com a associação feita no menu do Plano de Contas. ![img_61.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_61.png) No método de registo de Classificador económico, é necessáiro registar primeiro o classificador económico e a conta patrimonial é mostrada automaticamente|
|Conta|**Sim**|Seleção da conta ao classificador. ![img_62.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_62.png)|
|Valor|**Sim**|Montante do cabimento: ![img_62a.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_62a.png)|

</br>__Existem dois métodos de Registo (método de classificador económico e método de conta patrimonial) definido no menu de parametrização – Configuração__

O método apresentado é de conta patrimonial que deverá ser registado a contas da classe 3, 4, 5, 6. Automaticamente associa o classificador económico, sendo que este poderá ser alterado pelo utilizador. Relativamente à chave orçamental esta transparece automaticamente de acordo com a chave definida no menu parametrização configuração e que nesta fase também pode ser alterada.

</br>__Se existirem para a mesma conta ou classificador económico chaves orçamentais diferentes então devem ser criadas várias linhas com a mesma informação mas com chaves orçamentais diferentes.__

O preenchimento final, é idêntico ao do ecrã abaixo. O próximo passo é o de gerar de forma automática os movimentos na contabilidade selecionando o botão "Gerar Contabilidade".

![img_63.gif](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_63.gif)

No novo ecrã mostrado, aparecem os movimentos de lançamento do cabimento. Se os lançamentos estiverem corretos, o utilizador confirma, selecionando o botão de confirmação.

![img_64.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_64.png)

O Cabimento acaba de ser gerado, no entanto deverá o utilizador confirmar em sistema a criação do mesmo. No primeiro separador, o utilizador tem duas formas de o fazer: de entrar no seguinte ecrã, evidenciando o número de processo de aquisição da criação do CB:

-   Para aceder à informação de cabimento deverá ser pressionado o botão "Informação de CB";
-   Para consulta deverá ser pressionado o botão "Consulta".

__A novidade no novo sistema SICC é o aparecimento do botão "Importar", que permite aos utilizadores carregarem a partir de um documento de Excel vários cabimentos de forma muito mais rápida e fiável.__

### 1.1 Importação CB

O utilizador ao selecionar o botão ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e77f6488.png), vai fazer com que o novo ecrã surja para importação do ficheiro.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-baff3e42.png)


Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o diretório de origem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a996bb37.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-11b27685.png)

<!-- ![img_67.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_67.png) -->

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CB_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação,o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![img_68.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_68.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão  "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

Caso se trate de uma importação ou de valores introduzidos manualmente, no ecrã principal o utilizador tem outros botões que permitem assim uma análise mais cuidada.
Desta forma, nos passos seguintes, é demonstrado o funcionamento dos outros botões constantes do ecrã.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0ccf1c91.png)

O utilizador ao escolher um dos seguintes botões obtém os ecrãs:

### 1.2 Informação de CB

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d414c285.png)

O utilizador ao selecionar o botão "Imprimir", gera no ecrã o resultado da criação do CB.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c0eb122c.png)

Ao selecionar "Ficheiro", o aspeto do mesmo será como o do seguidamente apresentado:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b9a6ea3d.png)

### 1.3 Listagens de CB

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-776977c3.png)

Nos ecrãs atrás referidos, o procedimento é similar:

|Botão|Descrição|
|:---|:---|
|Calcular|Este botão permite apresentar os cabimentos no espaço "Documentos para imprimir". ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-594b7d1e.png)|
|Imprimir|Este botão permite que o utilizador gere relatório diretamente no ecrã|
|Ficheiro|Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido. ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-aea0e214.png)|
|Sair|Este botão permite que o utilizador saia do ecrã e regresse ao menu inicial|

O formato na opção "Imprimir", é o seguinte:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c393e3d6.png)

### 1.4. Alterações de Cabimentos (AM)

Neste processo o que se pretende demonstrar é uma alteração a um CB já existente. Desta forma, iremos contemplar mais uma linha de item financeiro ao CB criado anteriormente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-19410ace.png)

Ao entrar no ecrã de Alteração de CB, deve o utilizador associar o “Nº de CB” criado anteriormente para proceder à alteração. Terá igualmente de dar duplo clique na linha assinalada abaixo, para proceder à AM.

![img_79.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_79.gif)

Uma vez a linha subir um nível acima, deverá o utilizador definir por que montante pretende fazer a nova AM, pressionando posteriormente o botão "Gravar nova AM".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fbd35096.png)

Novo ecrã surge, no qual o utilizador definirá o novo item financeiro, conta e importância a registar na alteração do CB. Finda a alteração, deverá gerar os documentos contabilísticos de forma automática pressionando para o efeito o botão "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-513a1d48.png)

O novo ecrã surge e associada a ela, aparecem os movimentos de lançamento do cabimento. Se os lançamentos estiverem corretos, deve o utilizador confirmar, pressionado o botão de confirmação.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5f18c1ab.png)

A alteração ao Cabimento acaba de ser efetuada, sendo que o sistema gera uma mensagem de confirmação.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-03702c8f.png)

De realçar que qualquer movimento de estorno que seja efetuado no CB, não existe a necessidade de alterar o registo inicial, sendo que assim impede que haja alterações a nível dos mapas de execução orçamental.
Da mesma maneira que na importação de cabimentos, este processo de Alteração também pode ser feita por carregamento de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-74dc29f8.png)

Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o diretório de origem.

![img_85.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_85.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d10e4460.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AM_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação, o utilizador, tem de usar o botão "Verificar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![img_87.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_87.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão. Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

## 2. Verificação Prévia (CM)

Entende-se por _Verificação Prévia (CM)_, a verificação prévia de fundos disponíveis, as obrigações de efetuar pagamentos a terceiros em contrapartida do fornecimento de bens e serviços ou da satisfação de outras condições. Os compromissos consideram-se assumidos quando é executada uma ação formal pela entidade, como seja a emissão de ordem de compra, nota de encomenda ou documento equivalente, ou a assinatura de um contrato, acordo ou protocolo, podendo também ter um carácter permanente e estarem associados a pagamentos durante um período indeterminado de tempo, nomeadamente, salários, rendas, eletricidade ou pagamentos de prestações diversas.

Por parte do utilizador, há necessidade de evidenciar novamente o “Número de Processo de Aquisição”. De forma automática, o preenchimento do “valor disponível de cabimento” aparece por defeito. Posteriormente, deve o utilizador selecionar no botão “Gravar como CM”, bem como atribuir o montante do compromisso.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7e27de3f.png)

Neste ecrã, o utilizador terá de introduzir o valor manualmente e após confirmação dos elementos constituintes do CM, deve gerar os movimentos na contabilidade, utilizando o botão "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ef0da4bc.png)

Os movimentos contabilísticos aparecem no ecrã, sendo que se estiverem corretos, deverá o utilizador selecionar o botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-50c88c43.png)

Uma nova mensagem surgirá com a classificação do compromisso criado, sendo que este processo está concluído:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-aa19db1f.png)

Após a criação do compromisso, o utilizador terá assim a possibilidade de ter “Informação do CM” criado, para o efeito tem de selecionar no botão "Informação de CM".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b000b868.png)

Neste ecrã, surge o resumo da criação efetuada no passo anterior.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-299ce3c5.png)

Igualmente e da mesma forma que no ecrã dos cabimentos, o utilizador tem assim disponíveis as seguintes possibilidades:

|Botão|Descrição|
|:---|:---|
|Calcular|Este botão permite o resumo do que foi criado no cabimento|
|Imprimir|Este botão permite que o utilizador gere relatório diretamente no ecrã|
|Ficheiro|Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido|



O utilizador ao selecionar o botão "Imprimir", gera no ecrã o resultado da criação do CM.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1b010f55.png)

Ao selecionar "Ficheiro", o aspeto da informação de CM em ficheiro CSV será semelhante ao ficheiro seguidamente apresentado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f4a9ba48.png)

__A novidade no novo sistema SICC-SNC-AP é o aparecimento do botão , que permite aos utilizadores carregarem a partir de um documento de Excel vários compromissos de forma muito mais rápida e viável.__

### 2.1. Importação CM

No ecrã inicial, o utilizador ao selecionar este novo botão, vai fazer com que novo ecrã surja para importação do ficheiro.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-532c3768.png)

Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o diretório de origem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c0a092cc.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5669ced8.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CM-SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação,o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![img_98.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_98.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.
![img_98a.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_98a.png)

Sempre que um "Número de Processos de Aquisição" já tenha Compromissos associados, o sistema deve apresentar a seguinte mensagem:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0ed3fcdb.png)

### 2.2. Alteração de Compromisso (AB)

__Existe igualmente a possibilidade de proceder à alteração no Compromisso, pelo que o utilizador terá de ter em atenção que as alterações efetuadas também têm de estar alinhadas com o valor do Cabimento. O sistema deteta e envia mensagem de erro caso se verifique que o valor do compromisso seja superior ao cabimento, ou mesmo quando não existe cabimento para determinado item financeiro produzido posteriormente no compromisso. O Processo em si é semelhante ao explicado anteriormente nas alterações dos cabimentos (AM).__

</br> Menu de acesso:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c02d02d9.png)

Nesta etapa, demostramos, a título de exemplo, este processo de Alteração de Compromisso feita por carregamento de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-24fb53e0.png)

Ao selecionar o botão "Importar", o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o Diretório de Origem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-06629cf0.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-eb1b7514.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AB_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação,o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![img_104.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_104.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão. Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_105.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_105.png)

## 3. Lançamentos

Antes de realizar o registo de fatura FI, existe a necessidade de o utilizador verificar a disponibilidade do compromisso. Esta validação pode ser efetuada utilizando para o efeito, o botão "Consulta", explicado em passos anteriores.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-27cda4ab.png)

Neste menu o utilizador tem acesso a três separadores diferentes: Comprimisso Assumido (CP), Processado-F.Rec./Conf.(P1) e Processado - F.Confer.(P2).

### 3.1. Compromisso Assumido (CP)

O utilizador neste separador, deve indicar o nº do compromisso (CM). De forma automática, o sistema gera a data de criação do documento, a conta financeira associada e o respetivo montante. A fase seguinte é a de definir a entidade. Para o efeito deve selecionar sobre o botão "![img_radio_unselected.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_radio_unselected.png)" para chamada de todas as entidades registadas na base de dados.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-66afd507.png)

Para o exemplo em questão, foi criado mais um compromisso para demonstração do processo, no separador "Compromisso Assumido(CP)".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b1042c44.png)

Este compromisso para a entidade “2 – Sindicato dos trabalhadores Função Publica Zona Norte” foi criada pelo montante abaixo indicado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-87ac079d.png)

Selecionando a opção "Confirme", os movimentos contabilísticos são guardados de acordo com o apresentado no quadro "Razão Geral" e o formulário "Recolha de Contabilidade" é fechado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-18efe6fa.png)

Em caso de haver necessidade cria-se um "Processado - F.Conf.\Rec.(P1)" no separador seguinte. Caso não seja necessário, o utilizador prossegue para o separador "Processado - F.Confer. (P2)".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4e97c0a0.png)

#### 3.1.1. Importação CP

Nesta fase, ao exemplo das anteriores, demonstramos este processo de lançamento feito por importação de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-cce29a3b.png)

Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o Diretório de Origem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0c593329.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6201a896.png)

<!-- ![img_119.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_119.png) -->

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CP_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação, o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![img_120.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_120.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

### 3.2. Processado-F.Rec.\Conf. (P1)

Neste separador o utilizador deve inserir o Nº do Compromisso Assumido (CP) para que o sistema mostre o Valor Disponível e a Entidade correspondente. De seguida, o utilizador deve inserir o "Nº de guia/factura" bem como a "Importância" respectiva. Para gravar, deverá ser seleccionado o botão "Gravar novo P1".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c065dc68.png)

Após a gravação do P1 surge a janela de Recolha de Contabilidade com a conta de custos preenchida. O utilizador deve apenas introduzir a conta de contrapartida e o respetivo valor. De seguida gera-se a contabilidade através do botão correspondente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9ba5eaac.png)

No separador "Analítica", que é aberto ao gerar os documentos na contabilidade, é necessário atribuír um centro de custo para as contas de classe 6. O botão "![img_radio_unselected.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_radio_unselected.png)" permite o acesso a todos os centros de custos inseridos no sistema à semelhança do exemplo anterior. Para terminar deve ser selecionada a opção "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5f97b9c1.png)

#### 3.2.1. Importação P1

Nesta fase, ao exemplo das anteriores, demonstramos este processo de lançamento feito por importação de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3a4c64bd.png)

Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o Diretório de Origem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-14962395.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d6a122de.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P1_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação, o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-700fa4b1.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

### 3.3. Processado - F.Confer. (P2)

Este separador é preenchido conforme o tipo de documento anterior: "Compromisso Assumido" ou "F.Conf.\Rec.".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9f4ebec9.png)

Quando "Compromisso Assumido" é selecionado, o utilizador deve preencher os campos relativos à "Entidade" e ao número do "Compromisso Assumido" gerado para que o sistema indique o montante disponível. De seguida devem ser preenchidos os campos do "Nº de factura" bem como o da "Data da Contabilização" e a respetiva "Importância". Para gravar, deve selecionar sobre o botão "Gravar novo P2".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2ebaaaa2.png)

A conta de custos por defeito aparece, tendo somente o utilizador que introduzir a conta de contrapartida e respetivos valores da fatura.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-228379fe.png)

Ao gerar os documentos na contabilidade, é necessário que na analítica seja atribuído um centro de custo para as contas classe 6. Através do botão "![img_radio_unselected.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_radio_unselected.png)", o utilizador tem acesso a todos os centros de custo inseridos em sistema.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7cd014f9.png)

__O botão "Desdobrar Conta", permite ao utilizador, para a mesma conta (separador ca Cont. Analítica) , a possibilidade de escolher o número de linhas para desdobrar, no sentido de integrar vários Centros de Custo.__

Posteriormente à confirmação, o sistema gera uma mensagem com a seguinte informação.

![img_115.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_115.png)

Após confirmação, o sistema assume assim que para o compromisso e para a entidade já é existente o registo de fatura.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-40dd47b7.png)

Para gerar um P2 proveniente de um P1, o utilizador deve selecionar a opção "F.Conf.\Rec.". De seguida, deve preencher os campos da "Entidade", do número de "F.Conf.\Rec."", do "Nº de factura", da "Data de Contabilização" e da "Importância" da fatura. Para gravar deve selecionar o botão "Gravar novo P2".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-cf071459.png)

Na janela que surge após a gravação, o utilizador deve selecionar a conta "221" e atribuír-lhe o respetivo montante, neste exemplo será de 200€. De seguida deve selecionar o botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9433a3fc.png)

Após confirmação, o sistema assume assim que para o P1 e para a entidade já é existente o registo de fatura.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-32c2e610.png)

#### 3.3.1. Importação P2

Nesta fase, ao exemplo das anteriores, demonstramos este processo de lançamento feito por importação de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1e9d2caa.png)

Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o diretório de origem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1520b2ab.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4053f1f8.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P2_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação, o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-dbfb927e.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)


### 3.4. Importação de documentos de forma agrupada

É também possível, nesta fase de registos, importar documentos de uma forma agrupada, isto é, importar todos os documentos referentes ao ciclo de despesa até às faturas inclusivé (CB, CM, CP, P1 e P2). Para tal, deve o utilizador selecionar o botão "Ciclo da Despesa" disponível ao lado do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-436a2041.png)

No ecrã que é aberto, ecrã este que é semelhante ao ecrã de importações descritas anteriormente, deve o utilizador selecionar da directoria, o ficheiro em **formato CSV**. De seguida deve pressionar no botão "Ver/Testar Ficheiro" para que o sistema valide o ficheiro que se pretende importar.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e54ee938.png)

Após ter sido concluída a validação do ficheiro, no caso de este apresentar a estrutura correta, os campos do ecrã irão ficar preenchidos com dados do ficheiro.
No caso do ficheiro apresentar erros, estes irão ser reportados na janela respetiva e será gerada uma mensagem informativa.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ae2d54e7.png)

Os erros reportados devem ser corrigidos e o ficheiro atualizado deve ser novamente validado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/import_dsp.gif)

Por fim, no sentido de confirmar e executar a importação de dados, deve o utilizador pressionar no botão "Importa Ligação". O sistema irá gerar uma mensagem de confirmação, com a indicação abaixo descrita.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fe7caecb.png)

O aspeto do ficheiro CSV a ser importado deve ser semelhante ao seguidamente apresentado:

> **Nota:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-983ab8f8.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CSV_DSP_exemplo_1.csv'">Descarregar CSV</button>
</div>

Segue abaixo uma explicação de situações possíveis aquando a importação do ciclo de despesa.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0c0b170a.png)

- A situação A reresenta o caso quando para o mesmo cabimento (CB) existem várias faturas (P2);
- A situação B reresenta o caso em que os documentos contemplam várias contas.

Para ambas as situações, está também apresentada a forma como são calculados os valores dos documentos quando são "desdobrados" em várias linhas.

### 3.5. Alteração de Lançamentos (AL)

Neste processo o que se pretende demonstrar é uma alteração a um CP existente. O caminho que o utilizador deve seguir é:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2374f53.png)

Neste processo, demostramos a título de exemplo o este processo de Alteração de lançamentos efetuada por carregamento de ficheiro através do botão "Importar".

![img_122.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_122.png)

Ao pressionar, o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o Diretório de Origem.

![img_123.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_123.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d01be3bc.png)

<!-- ![img_124.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_124.png) -->

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AL_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação,o utilizador, tem de usar o botão "Verificar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.


![img_125.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_125.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

## 4. Autorização de Pagamento (AP)

A autorização de pagamento das despesas, são autorizadas pelos dirigentes dos serviços ou outros que detenham autorização, mediante operações de tesouraria ou ainda através de transferência bancária, quando esta forma se revelar a mais conveniente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2995da1.png)

Neste processo, o utilizador terá de identificar a entidade e os documentos que dela fazem parte, bem como atribuir um nº de autorização. O não preenchimento deste último, determina que a numeração seja automática. Ao exemplo do anterior, terá de dar duplo clique na linha que contém os elementos para a mesma subir ao nível seguinte.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f3ce9222.png)

O utilizador define também se o pagamento é efetuado por Tesouraria ou por Transf. Bancária, sendo que para este último caso tem de selecionar qual a Instituição Bancária.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-519d916a.png)

|Campo|Descrição|
|:---|:---|
|NIB/IBAN|Este campo dá a hipótese do utilizador escolher se é um IBAN Credor ou _Factoring_, aparecendo as seguintes opções: ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4a09e554.png)|
|Motivo|O motivo deverá igualmente ser escolhido dentro das parametrizações inseridas em sistema: ![img_secu_pag_igcp.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_secu_pag_igcp.png)|

Para o exemplo, escolhemos IBAN Credor, sendo que para este caso é sempre obrigatório colocar um motivo. Deve o utilizador, seguidamente, confirmar para dar continuidade à AP.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5242482a.png)

Ao confirmar, uma nova janela surge com os movimentos contabilísticos associados. Caso estejam corretos, o utilizador terá de confirmar para finalizar o processo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-396a3f91.png)

### 4.1. Importação AP

Este processo de Autorização de Pagamento também pode ser efetuado por carregamento de ficheiro CSV através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ce8fa564.png)

Ao selecionar o botão vai ser aberto um novo ecrã onde o utilizador, para carregar o ficheiro CSV, tem de escolher o diretório de origem do mesmo.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1d28edba.png)

O aspecto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-277bb7fb.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AP_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação, o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-43ae47eb.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8bbe8dd6.png)


### 4.2. Impressão de Autorizações de Pagamento (AP)

Nesta etapa, é demonstrado o procedimento para fazer as impressões das AP’s (de forma _individual_ ou _global_) geradas no passo anterior. Para isso, deve o utilizador seguir o seguinte caminho no sistema:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-97b60cbd.png)

_Individual_

Deve o utilizador, escolher a entidade da qual pretende extrair a Autorização de Pagamento.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-19178dba.png)

__O utilizador tem de selecionar SEMPRE os documentos que deseja, sejam para consulta ou impressão através da colocação de ![img_checkbox_checked.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_checkbox_checked.png) no ecrã.__

_Global_

O utilizador tem a possibilidade de definir um intervalo, com a possibilidade de escolher as entidades das quais pretende extrair as Autorizações de Pagamento.

![img_141.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_141.png)

__O utilizador tem de selecionar SEMPRE os documentos que deseja, sejam para consulta ou impressão através da colocação de ![img_checkbox_checked.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_checkbox_checked.png) no ecrã.__

|Campo|Obrigatoriedade|Descrição|
|:---|:---|:---|
|Primeira Entidade|**Sim**|Definir primeira entidade a filtrar|
|Última Entidade|**Sim**|Definir última entidade a filtrar|
|Primeira data|**Sim**|Definir intervalo primeira data|
|Última data|**Sim**|Definir intervalo última data|
|“Pôr autorizações regularizadas”|Opcional|Permite ao utilizador quando o estiver ativo imprimir guias com histórico e em que já tenha ocorrido o recebimento.![img_checkbox_checked_2.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_checkbox_checked_2.png)|
|Autorização de Pagamento / Autorização Global de Pagamento|**Sim**|O utilizador escolhe: ![img_autorizacao_pagamento.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_autorizacao_pagamento.png), sendo que, para mais que um registo existe a possibilidade de "Selecionar Todos" ![img_selecionar_todos.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_selecionar_todos.png)|

|Botão|Descrição|
|:---|:---|
|Calcular|Este botão permite ao utilizador consultar os valores carregados de orçamento, bem como os respetivos classificadores económicos|
|Imprimir|Este botão permite a geração do documento em PDF|
|Sair|Este botão permite ao utilizador sair do ecrã corrente|

De forma _Individual_, ao selecionar “Imprimir”, o sistema produz a Autorização de Pagamento em PDF.

![img_144.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_144.png)

De forma _Global_, ao selecionar “Imprimir”, o sistema produz a Autorização de Pagamento Coletiva em PDF.

![img_145.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_145.png)

### 4.3. Ofício de Pagamento

Para aceder ao ecrã onde é gerado o ofício de pagamento, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d12f61d8.png)

Noecrã aberto, o utilizador deve preencher os seguintes campos:

|Campo| Descrição |
|:--|:--|
|Pri. Entidade    | Primeiro código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.    |
|Últ. Entidade    |Último código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.    |
|Primeira Data:    | Data do primeiro do documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.    |
|Última Data:    | Data da último documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo. |
|Referência    | Referência do ofício.   |
|Texto    | Texto que irá aparecer no documeto gerado.    |

</br> Deve também ser indicado se os documentos que se pretendem incluír no ofício devem ser regularizados ou ainda por regularizar.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-243a80a9.png)

Após ter definido os critérios de pesquisa,deve o utilizador clicar em "Calcular" para que o sistema apresente todos os documentos que estejam de acordo com os critérios de pesquisa. Para selecionar o documento, deve o utilizador preencher a check box do documento pretendido.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-05ab035f.png)

Pode agora Ofício ser impresso ou enviado através de email.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-482e81f2.png)

##### Imprimir

Quando esta opção é selecionada, o aspeto do ficheiro PDF gerado é semelhante ao seguidamente apresentado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f5a24fd0.png).

Quando é selecionada mais do que uma AP, cada uma vez numa página.

##### Email

Quando esta opção é selecionada, surge um novo ecrã ondeo utilizador deve selecionar as entidade a quem pretende enviar o oficio, inserir o texto que aparecerá no corpo do emial enviado. De seguida deve clicar em "Calcular" para verificar os emails das entidades selecionadas. Por fim, deve clicar em "Enviar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3b59e7f0.png)

#####  Listagens de Encontro de Contas

Para aceder ao ecrã que permite listar todos os documentos relacionados com o registo de Encontro de Contas, o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8438ff18.png)

No ecrã que é aberto, o utilizador deve preencher os critérios de pesquisa de documentos.

|Critério | Descrição|
|:--|:--|
|Primeira Data    |Data do primeiro do documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.    |
|Última Data    | Data da último documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.  |
|Primeiro Documento   | Número do primeiro documento a extrair. Apenas são extraidos documentos cujos códigos sejam igual ou superior ao indicado neste campo.    |
|Último Documento    | Número do último documento a extrair. Apenas são extraidos documentos cujos códigos sejam iguais ou inferiores ao indicado neste campo.    |
|Primeira Entidade    |  Primeiro código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.   |
|Última Entidade    | Último código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.  |   

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d0afe91e.png)

De seguida o utilizador deve selecionar o formato em que pretende guardar a listagem: Ficheiro CSV ou ficheiro PDF - Imprimir.

##### Ficheiro

Nesta opção, o utilizador deve selecionar a diretoria onde pretende guardar o ficheiro e por fim deve clicar em "Ficheiro".

O aspeto do ficheiro CSV será como o do apresentado seguidamente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-beddb177.png)

##### Imprimir

Nesta opção, será gerado um ficheiro em formato PDF com o aspeto semelhante ao do documento seguidamente apresentado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9e2c17d1.png)

## 5. Transferências Bancárias

Nesta etapa, o utilizador vai criar os ficheiros para enviar aos respetivos órgãos com indicação das entidades e montantes associados. Deve assim seguir o seguinte caminho no sistema:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-837d7d7c.png)

Surge um ecrã na qual o utilizador tem de preencher de acordo com o quadro abaixo:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bd925707.png)

__No caso da ACSS, o utilizador na altura da criação dos vários tipos de documentos (notas de crédito, notas de débito, etc), pode associar os mesmos ao referido Departamento a que dizem respeito, evidenciando posteriormente no ecrã e no respetivo campo![img_actividade_departamento.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_actividade_departamento.png).__


|Campo|Obrigatoriedade|Descrição|
|:---|:---|:---|
|Instituição bancária|**Sim**|Definir a instituição bancária|
|Primeira Entidade|**Sim**|Definir primeira entidade a filtrar|
|Última Entidade|**Sim**|Definir última entidade a filtrar|
|Primeira data|**Sim**|Definir intervalo primeira data|
|Última data|**Sim**|Definir intervalo última data|
|Primeiro documento|**Sim**|Definir intervalo primeiro documento a integrar|
|Último documento|**Sim**|Definir intervalo último documento a integrar|
|Gerar Ficheiro de carregamento|**Sim**|Geração do ficheiro com número sequencial, sendo que prevalece o número de cálculo maior, ou seja, se o número da última transferência efetuada for superior ao ![img_num_de_sequencia_prox.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_num_de_sequencia_prox.png), do caminho: _Parametrização - Tabelas Genéricas - Inst. Bancárias – Recolha_, a numeração atribuída é sempre a mais alta numericamente|

Findo o preenchimento dos campos, deve o utilizador dar continuidade ao processo pressionando o botão "Transferência Bancária", originando novo ecrã.

__O utilizador tem de ter escolher o tipo de documento que quer gerar, dependendo das obrigatoriedades associadas. Para o efeito o sistema pode criar 3 tipos de documentos, associado cada um deles ao tipo de identificador, sendo que a sua seleção é sempre obrigatória.__

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3d73cf14.png)

|Botão|Descrição|
|:---|:---|
|Ficheiro|Este botão permite ao utilizador escolher o diretório de gravação do ficheiroTXT. (IGCP) ou XML. (IGCP – Novo) que será gerado. ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b51ea880.png) ![img_152.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_152.png)|
|Imprimir 2ª Via|Este botão permite que o utilizador gere relatório diretamente no ecrã|
|Ficheiro 2ª Via|Este botão permite ao utilizador escolher o novo diretório de gravação do ficheiro TXT ou XML a ser produzido em caso de alteração ou engano|

![img_153.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_153.png)

__Após a geração do ficheiro, este botão deixa de estar “ativo”, pelo que o utilizador pode gerar uma 2ª via do Ficheiro.__

O ficheiro, após gerado, fica guardado na extensão definida pelo utilizador para posteriormente ser submetido. Caso o utilizador queira imprimir o resumo do ficheiro de forma a obter o comprovativo, pode entrar novamente no ecrã e “Imprimir 2ª Via”, pressionando sobre o botão. De forma automática e no Browser, surgirá o comprovativo, conforme abaixo demonstrado.

![img_154.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_154.png)

__No caso específico da ACSS e por se tratar de uma instituição com 2 departamentos distintos, deve o utilizador ver o ponto 4 deste manual.__

### 5.1. Importar Transferências Bancárias

O  sistema SICC, permite ao utilizador a importação de ficheiros TXT. e a conversão de ficheiros TXT. em XML.

Para o efeito, o passo para este processo é o abaixo demonstrado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8133feeb.png)

Nesta etapa, um novo ecrã surge, em que o utilizador tem possibilidade de realizar as seguintes tarefas:

![img_156.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_156.png)

|Botão|Descrição|
|:---|:---|
|Importar Ficheiro|Este botão permite ao utilizador escolher o diretório onde está o ficheiro para importação com formato TXT. Após determinar o caminho deve selecionar sobre o botão de importação.
![img_157.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_157.png) ![img_158.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_158.png)||
|Converter em XML|Através deste botão, o utilizador escolhe o diretório onde está o ficheiro para importação. A aplicação permite ao utilizador através do botão de conversão, transformar um formato TXT. para um formato XML|
|Ficheiro 2ª Via|Este botão permite ao utilizador gerar uma segunda via do ficheiro TXT ou XML|
|Sair|Este botão permite que o utilizador saia do ecrã e regresse ao menu inicial|

__Na importação de TXT. ou na Conversão para XML, o sistema ao carregar o ficheiro, vai determinar o último "Número de sequência", sendo que o vai atribuir de forma automática e sequencial para cada um dos casos referidos.__

## 6. Pagamentos (PG)

De forma automática, uma conta de disponibilidades deve ser lançada a crédito por contrapartida da compensação da partida de autorização de pagamento com código de razão especial (252*).

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-645ee5ad.png)

Ao entrar neste submenu, o utilizador deve fazer o registo do pagamento. A informação referente à entidade é obrigatória, bem como a visualização dos documentos. O utilizador ainda no presente ecrã, terá de definir o número de tesouraria para registo do pagamento. Desta forma e a título de exemplo foi escolhido o número 11.

Ao fazer duplo clique sobre a linha resumo, a informação é preenchida automaticamente com base no que foi definido anteriormente, nomeadamente: IBAN e importância, devendo no final confirmar.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b5df60d0.png)

Surge nova janela na qual apresenta as movimentações contabilísticas, para o utilizador ver os registos efetuados pelo sistema. Para concluir, deve selecionar "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-21efb928.png)

Ao confirmar surge de novo o ecrã inicial e pode constatar que a AP não aparece. Este principio tem como finalidade evitar que possam vir a existir pagamentos em duplicado.

![img_163.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_163.png)

__Deve o utilizador no final, verificar o impacto no mapa de execução orçamental da despesa.__

Para finalizar o processo de pagamento, o utilizador no ecrã principal tem de selecionar: “Número de entidade”, bem como a “Situação do Documento”.

__O utilizador tem de ter em conta qual o tipo de situação do documento, sendo que neste processo o que se pretende é a visualização dos documentos pagos.__

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6d01295b.png)

Como o sistema dá indicação da situação do documento, deve o utilizador fazer uma impressão do mesmo.

Para o efeito, tem de seguir o caminho:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-01eba65e.png)

Neste ecrã, o utilizador tem de preencher com a informação de acordo com as instruções do quadro abaixo:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8feaaa84.png)

__O utilizador tem de selecionar SEMPRE os documentos que deseja, sejam para consulta ou impressão através da colocação do visto ![img_checkbox_checked.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_checkbox_checked.png) no ecrã anterior.__


| Campo                               | Obrigatoriedade | Descrição                                                                                                                             |
|:------------------------------------|:----------------|:--------------------------------------------------------------------------------------------------------------------------------------|
| Ano                                 | **Sim**     | Exercício a que dizem respeito as informação da instituição                                                                           |
| Primeira Entidade                   | **Sim**     | Definir primeira entidade a filtrar                                                                                                   |
| Última Entidade                     | **Sim**     | Definir última entidade a filtrar                                                                                                     |
| Primeira data                       | **Sim**     | Definir intervalo primeira data                                                                                                       |
| Última data                         | **Sim**     | Definir intervalo última data                                                                                                         |
| Referência                          | Não        | Campo de texto                                                                                                                        |
| Texto                               | Não        | Campo de texto                                                                                                                        |
| AP/DA por regularizar/regularizadas | **Sim**     | O utilizador escolhe a opção "AP/DA regularizadas" , sendo que, para mais que um registo existe a possibilidade de "Selecionar todos" |

Ao selecionar “Imprimir”, o sistema produz o documento em PDF:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ce32adec.png)

### 6.1. Importação PG

Este processo de Pagamento de facturas também pode ser efetuado por carregamento de ficheiro CSV através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6bc11671.png)

Ao selecionar o botão vai ser aberto um novo ecrã onde o utilizador, para carregar o ficheiro CSV, tem de escolher o diretório de origem do mesmo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c8777600.png)

O aspecto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2d59f8a4.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PG_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação, o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este mesmo botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-70996b6c.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a3186286.png)

## 7. Notas de Crédito (NC)

Para proceder ao registo de uma nota de crédito deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e89bb563.png)

No ecrã que é aberto o utilizador deve preencher os seguintes campos obrigatórios:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-509f28ec.png)

Após terem sido introduzidos todos os parâmetros,o utilizador deve clicar no botão "Gravar nova NC".

Neste novo ecrã, o utilizador deve indicar as contas de movimento e os respetivos valores. De seguida deve clicar no botão "Gerar contabilidade".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-30d5c28a.png)

Na segunda janela que será aberta, o utilizador deve indicar o centro de custo. Pode consultar com a ajuda do botão redondo, todos os centros de custo disponíveis no sistema.

Para concluir este registo, o utilizador deve clicar no botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4a7f77a3.png)


</br>**Autorização de Pagamento**
</br>Após ter sido registada a NC, pode-se se prosseguir ao registo da Autorização de Pagamento (AP).

No ecrã respetivo, descrito no capítulo **5.** desta secção do manual, o utilizador deve indicar a entidade, e selecionar o botão "Ver Documentos".


</br>Dos documentos apresentados, o utilizador deve selecionar, em primeiro lugar, a fatura (P2) e depois a NC. A seleção deve ser feita com um duplo clique sobre os documentos.

Nesta fase também deve ser selecionado o tipo de pagamento a efetuar (Tesouraria ou por Transferência Bancária) e o registo consequente deve ser efetuado de acordo com este.

Para confirmar o registo da AP, o utilizador ,deve clicar no botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/nota_credito_ap.gif)

No ecrã que abrir o utilizador deve confirmr se as contas lançadas e os respetivos valores estão corretos e por fim deve clicar no botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a5034333.png)

Após ter sido registada a autorização de pagamento, pode agora o utilizador prosseguir com o registo do pagamento.
A descrição deste processo pode ser consultada no capítulo 7. desta secção.

### 7.1. Importação NC

As Notas de Crédito podem ser importadas através do botão "Importar" disponivel no ecrã inicial de registo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-64f28739.png)

Na janela aberta, o utilizador deve selecionar da diretoria o ficheiro que pretende importar, à semelhança de todas as outras importações, e para validar a consistência do mesmo deve clicar no botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-dbc245d9.png)

O aspeto do ficheiro **CSV** a ser importado é semelhante ao seguidamente apresentado:

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e3438c35.png)
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/NC_SNCAP.csv'">Descarregar CSV</button>
</div>

Após validação do ficheiro, as janelas do ecrã ficarão preenchidas com os dados do ficheiro importado. Caso este apresente inconsistências, estas serão apresentadas na janela respetiva.
De seguida, para efetuar a importação dos dados deve o utilizador pressionar no botão "Importa Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8971096d.png)

Para validar a importação, o sistema irá mostrar uma mensagem como a seguidamente apresentada:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a9ba0cca.png)

#### 7.1.1.  Reposição Abatida aos Pagamentos (RAP)

Sempre que seja detetado um pagamento indevido deve-se prosseguir à emissão de uma RAP que é considerada contabilisticamente como uma Nota de Crédito (NC).

A existência de uma reposição abatida pressupõe que houve um pagamento excessivo em relação a uma determinada aquisição, cuja regularização é efetuada, no respetivo ano financeiro, através da correção da dotação utilizada e do respetivo saldo disponível, aumentando-o. Decorre deste entendimento que a reposição abatida aos pagamentos não seja tida como uma receita orçamental.


Os registos a efetuar na Contabilidade Financeira devem ser com as contas 2x, 3x, 4x ou 6x. A nivel de registos na Contabilidade Orçamental, estes são efetuados de forma automática pelo sistema e são os seguintes:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-55401346.png)


Desta forma, no ecrã relativo ao registo de uma nova NC deve ser indicado na respetiva checkbox que se trata de uma RAP. Todos os preenchimentos seguintes seguem a mesma lógica que uma Nota de Crédito convencional.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e86b55f0.png)

No momento do registo da AP, deixa de ser necessário associar uma factura pelo facto de se tratar de uma reposição abatida aos pagamentos. O valor deste documento será negativo.

Mais uma vez, aquando a realização do pagamento da AP criada, o sistema irá efetuar registos, automaticamente, na contabilidade orçamental, que serão os seguintes:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-39b58c60.png)

## 8. Anulação de Faturas P2/NC (AF)

Em conformidade com as recomendações da Autoridade Tributária e Aduaneira (AT), não é possível anular diretamente uma fatura. A anulação do movimento de uma fatura é feita através da emissão de uma nota de crédito. Sem reflexo para a contabilidade, o que se pretende com este tipo de documento é a regularização do mesmo, de modo a que o seu impacto no final seja nulo.

Este tipo de documento, proveniente exclusivamente do P2 ou da NC (exceto RAP), obriga o utilizador a selecionar pelo menos uma fatura e uma nota de crédito com o objetivo do resultado final ter o valor de "0" para proceder ao registo de anulação. O objetivo deste documento é regularizar ambos os documentos selecionados sem que seja necessário efetuar registos contabilísticos.

Para aceder ao ecrã de registo da Anulação de Fatura (AF) deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a697fec9.png)

No ecrã aberto, o utilizador deve indicar os critérios de pesquisa de documento. Primeiro, deve indicar a entidade e de seguida deve clicar no TAB do teclado do seu computador para visualizar toadas as faturas por regularizar da entidade indicada ou pode indicar, nos campos respetivos, o número e o tipo de documento que pretende visualizar. Na janela de baixo irão aparecer todos os documentos encontrados que correspondem aos critérios de pesquisa inseridos.

Para efetuar o registo da AF, deve o utilizador selecionar os documentos P2 e NC, clicando sobre os mesmos duas vezes. Para confirmar o registo, deve o utilizador clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2cddb55.png)

O sistema irá gerar uma mensagem onde é indicado o número da AF registada.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-92452daa.png)

O utilizador pode agora imprimir a AF criada. Para tal deve, no ecrã de recolha de dados, indicar a entidade e número de documento. De seguida deve clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ef916b2c.png)

Na nova janela aberta, deve indicar os intervalos das entidades das quais pretende visualizar os documentos, as datas e os números dos documentos (FD e CC) que pretende visualizar. De seguida deve clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-05f2a540.png)

O aspeto do ficheiro PDF gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f0fb5277.png)


## 9. Crédito sobre Facturas  (CF)

Para aceder ao ecrã de recolha de dados relativos a crédito sobre facturas, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-96bc1e03.png)

No ecrã aberto, o utilizador deve preencher os campos obrigatórios, assinalados na imagem seguidamente apresentada, e por fim deve clicar em "Gravar novo CF".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e1c149d2.png)

Na janela que surge, o utilizador deve indicar as contas de movimento pretendidas bem como os seus respetivos montantes. Também nesta janela, o utilizador deve indicar a conta financeira que ficará associada à CF lançada e que poderá posteriormente ser visualizada no Balancete de Rubricas Financeiras. Por fim deve clicar em "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1a126468.png)

Na nova janela que surge, o utilizador deve indicar o Centro de custo associado à conta 7* indicada na janela anterior. O utilizador pode consultar a listagem dos Centros de Custo disponíveis no sistema através do botão redondo.

Por fim deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0333dd91.png)

O passo seguinte será regularizar CF com a emissão de uma Autorização de Pagamento.

</br> **Autorização de Pagamento**

No ecrã respetivo à emissão de autorizações de pagamentos, deve, como já referido em processos anteriores, o utilizador indicar a entidade ede seguida clicar em "Ver Documentos".  

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-86ee2b63.png)

Na janela de baixo irão aparecer as faturas por regularizar associadas à entidade indicada. Assim, e como se pretende regularizar a CF anteriormente lançada, deve o utilizador selecionar **primeiro** a fatura (P2) ao qual será creditado o valor da CF e depois deve ser selecionada a CF. Esta seleção deve ser efetuada com um duplo clique sobre os documentos pretendidos. Estes documentos passarão para a janela de cima e os seus dados ficarão disponíveis nos campos respetivos. De seguida o utilizador deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/ap_cf.gif)

Na nova janela aberta deve o utilizador confirmar as contas apresentadas e os respetivos montantes e por fim deve confirmar o lançamento da AP clicando em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-43f1339a.png)

O próximo passo é efetuar o pagamento da fatura.

</br> **Pagamento**

No ecrã respetivo, o utilizador deve indicar, novamente, a entidade e clicar em "Ver documentos".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ced47f65.png)

Na janela irão aparecer as autorizações de pagamento por regularizar associados à entidade indicada. Destes deve selecionar, com um duplo clique sobre o documento, a AP pretendida. Ao selecionar o documento, o campo relativo à importância da AP, ficará preenchida com os dados da AP selecionada. Por fim deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-cb7e2858.png)


Na nova janela aberta, o utilizador pode verificar todos os lançamentos efetuados. Se estes estiverem corretos deve confirmar o pagamento através do botão respetivo: "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-94bee828.png)

Este lançamento pode ser verificado, tal como já foi referido anteriormente, no Balancete Rubricas Financeiras, nomeadamente nas rubricas 9962 da P2 e na rubrica 9978 da CF, sendo que esta última deve estar a débito.

Para o efeito foi feita a impressão do balancete antes e após este lançamento e o resultado pode-se verificar na imagem seguinte.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ffaeb61f.png)

### 9.1. Importação de CF

Este documento também pode ser importado através da funcionalidade disponível no botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1894a3ac.png)

No ecrã aberto, o utilizador deve selecionar da diretoria do seu computador o **ficheiro CSV** para importação. De seguida deve clicar em "Ver/Testar Ficheiro" para verificar se este apresenta a estrutura correta bem como se existem outras incoerências.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-42db96e1.png)

Em caso de estar coerente, as duas janelas do ecrã ficarão preenchidas com os dados do ficheiro a importar. Em caso de existirem incoerências as mesmas serão comunicadas ao utilizador na janela respetiva. Deve por isso, o utilizador, efetuar a correções necessárias e testar novamente o ficheiro.
Por fim, para concluir a importação, deve clicar em "Importa Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8d01cbea.png)

Para confirmar a importação do ficheiro, o sistema irá mostrar a seguinte mensagem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bdd7e937.png)

O aspeto do ficheiro CSV a ser importado deve ser semelhante ao seguidamente apresentado.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9dd3e1a3.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CF_SNCAP.csv'">Descarregar CSV</button>
</div>

## 10. Débito sobre Faturas (DF)

Para aceder ao ecrã de recolha de dados relativos a débito sobre faturas, deve o utilizador seguir o caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e056b915.png)

No ecrã que é aberto, deve o utilizador preencher os seguintes campos obrigatórios. De seguida deve clicar em "Gravar novo DF".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-790a7191.png)

No preenchimento destes campos obrigatórios, no caso do utilizador indicar um número de CP que não exista ainda, este pode ser criado nesse momento. Para tal, o sistema gere uma mensagem a indicar que o CP é inexistente e pede para inserir o Nº de CB.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d17ee958.png)

No novo ecrã aberto, o utilizador deve preencher as contas e os movimentos respetivos.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a200cc59.png)

Findo o preenchimento das contas, o utilizador deve clicar em "Confirme".

Como o CM e CP tinham consumido o valor total do CB criado, o sistema criou as alterações aos docuemtnos, nomeadamente a AL, AB e AM. Estas alterações são comunicadas ao utilizador através de uma mensagem como a seguidamente apresentada.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-43790ce8.png)

### 10.1 Importação DF

Este documento também pode ser importado através da funcionalidade disponível no botão "Importar".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6ed844d9.png)

No ecrã aberto, o utilizador deve selecionar da diretoria do seu computador o **ficheiro CSV** para importação. De seguida deve clicar em "Ver/Testar Ficheiro" para verificar se este apresenta a estrutura correta bem como se existem outras incoerências. Em caso de estar coerente,  as duas janelas do ecrã ficarão preenchidas com os dados do ficheiro a importar. Em caso de existirem incoerências as mesmas serão comunicadas ao utilizador na janela respetiva. Deve por isso, o utilizador, efetuar a correções necessárias e testar novamente o ficheiro.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f47f683f.png)

Por fim, para concluir a importação, deve clicar em "Importa Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-11fb6a67.png)

Para confirmar a importação do ficheiro, o sistema irá mostrar a seguinte mensagem.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bdd7e937.png)

O aspeto do ficheiro CSV a ser importado deve ser semelhante ao seguidamente apresentado.

>**NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1c074965.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/DF_SNCAP.csv'">Descarregar CSV</button>
</div>

O passo seguinte ao registo da DF é o registo da autorização de pagamento (AP) da mesma. Este processo está descrito no capítulo 5. deste manual.

## 11. Listagem Despesa

Este menu permite ao utilizador obter um mapa de documentos possibilitando visualizar a sua relação e estado (regularizado ou por regularizar).  

Para tal, deve o utilizador indicar os critérios de pesquisa dos documentos a visualizar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6bd00b0b.png)

Primeiro deve indicar qual o Tipo de Documento Principal. Para o efeito, deve clicar por cima do campo a preencher e de seguida deve selecionar, do esquema do Fluxo de Despesa, o tipo de documento principal.

De seguida deve clicar no campo relativo ao "Tipo de documento secundário" e selecionar, do esquema, o tipo de documento que será o secundário.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/lista_despesa.gif

>**NOTA:** Caso o utilizador não indique o tipo de documento secundário, serão apresentados todos os documentos que se seguem ao documento principal no fluxo de despesa.

Na área "Documento Principal" o utilizador pode definir os critérios de pesquisa do documento principal. Numa primeira instância, deve indicar se pretende pesquisar documentos pelo seu número de documento ou por conta a débito. Para tal deve-o indicar através da seleção da respetiva _checkbox_.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ba775e92.png)

De seguida deve indicar o Ano ao qual se referem os documentos a pesquisar e o intervalo de Entidades a considerar para o efeito.

</br> Para indicar o intervalo de datas, deve o utilizador primeiro indicar se o intervalo se refere à data de documento ou à data de contabilização. Também deve ser indicada a data de referência.

</br> Caso a pesquisa for efetuada pelo número de documento, deve o utilizador indicar o intervalo de números de documento a incluir no ficheiro a produzir. A lista de documentos será apresentada pela ordem crescente do número de documento.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-2307e727.png)

</br>Caso a pesquisa for efetuada por Conta a débito, deve o utilizador indicar o intervalo de contas a considerar. A lista de documentos será apresentada pela ordem crescente de contas.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-11f06acd.png)

Para produzir o ficheiro deve primeiro o utilizador indicar o diretório onde pretende guardar o ficheiro CSV e de seguida deve clicar em "Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6a63c592.png)


O aspeto dos ficheiros CSV produzidos são como os apresentados seguidamente:

|NUMERO DOCUMENTO|CONTA|
|:--:|:--:|
| ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-99cf994b.png) | ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3c35318b.png) |  


## 12. Ligações de Outras Aplicações

Este capítulo pretende descrever o processo de importação de dados provenientes de outras aplicações no sentido de interligar vários departamentos da entidade. As aplicações em questão permitem a gestão de dados referentes a:

- Pessoal;
- Stocks;
- Imobilizados;
- Faturação de Devedores;
- Farmácias;
- SISO/Reembolsos;
- MCDT.

A importação de dados destas aplicações, no sistema SICC /SNC - AP,  pode ser feita via ficheiros em formato TXT.
O _layout_ geral destes ficheiros, isto é, de todos os ficheiros TXT referentes a estas importações, é igual para todas as ligações disponíveis neste menu. No entanto, os campos que são preenchidos no ficheiro para importação, variam consoante o tipo de ligação e o tipo de documento que importam - o que é definido pela referência do ficheiro.

Na imagem abaixo está representado um exemplo de dois ficheiros, referências 101 (Ligação Pessoal) e 211 (Ligação Gestão de Stocks), onde estão apresentados campos que são preenchidos nos dois ficheiros (por exemplo: Conta Débito) e outros que apenas são preenchidos por um deles.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-162effc4.png)

>**Nota:** Apenas pode ser produzido um ficheiro TXT por referência. </br> No ficheiro TXT, de uma dada referência, podem haver várias linhas por processo de aquisição.


 </br>Ao longo dos próximos sub-capítulos será descrito, com detalhe, todo o fluxo de trabalho necessário para que a importação dos dados seja bem sucedida bem como a estrutura dos ficheiros para cada tipo de importação.

> Recomenda-se o uso da tecla **_TAB_** para a navegação pelos campos dos ecrãs do sistema. Esta forma de navegação garante que todos os campos obrigatórios sejam preenchidos e validados permitindo o posterior desbloqueio de outros campos.

### 12.1 Ligações de Pessoal
Para importar dados relativos ao Pessoal o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3f6487e6.png)

</br> No ecrã referente às importações de dados de pessoal, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-eefe9ffc.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos.
Caso ocorram erros, é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser validado novamente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b8b5b12d.png)

É possível guardar a listagem de erros de duas formas:
- Em formato CSV, disponível através da seleção do botão "Ficheiro de Erros", em que o utilizador deve escolher o caminho no seu compotador onde pretende guardar o ficheiro.
- Em formato PDF, disponível através da seleção do botão "Erros" que terá o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bc712cc6.png)

</br>Quando o ficheiro não contém erros, os elementos do ficheiro carregado ficam visíveis no ecrã. Após validação dos elementos do ficheiro, o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-56b9f08d.png)

O utilizador pode ainda, selecionandpo o botão "Ligações" obter um documento PDF com os elementos carregados no sistema.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9a398c82.png)

Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)


Para a importação de dados de pessoal, podem ser importados ficheiros com as referências **101 e 102**. Os ficheiros de referência 101 importam dados relativos a documentos do tipo CB, CP e P2. Os ficheiros de referência 102 importam dados relativos a documentos do tipo OD. Estes ficheiros devem obedecer ao critério dos campos estipulados que estão apresentados seguidamente:

#### 12.1.1. Referência 101

|Campo|Posição |Observações|
|:---:|:---:|:---|
|Ref.   |1 - 3 (3)  | Indicar a referência do ficheiro. Neste caso específico a referência é **101**.   |
|Entidade   |  12 - 19 (8) | A numeração das entidades, para todas as contas iniciadas por 63, deve ser iniciada por 9963 e terminada com o indicativo do mês. Por exemplo: </br> 9963**001** - janeiro </br>9963**002** - fevereiro </br> ...</br>9963**012** - dezembro </br></br> Estas entidades devem ser criadas e parametrizadas no menu respetivo. ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c75338c1.png)</br></br> No ecrã aberto, tal como descrito na secção **Parametrização** - capítulo 4.1. Gestão de Entidades, devem ser preenchidos os campos obrigatórios. Na imagem seguinte, está o exemplo para a entidade referente ao mês de janeiro.![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f7ceb024.png) </br>**NOTA:** O NIF para todas estas 12 entidades deve ser **999999990**.   |
|Nº CB, CP, P2   | 20 - 27 (8)  | A numeração dos documentos varia consoante o grupo. </br></br> **Conta 63-Vencimentos** (com exceção dos encargos e outros custos) </br></br> A numeração dos documentos deve ser iniciada por 63, seguindo-se da indicação do mês - 01- e terminada com digitos sequenciais - 001. Por exemplo:</br> 6301**001** - documento 1 do mês de janeiro</br> 63**02**001 - documento 1 do mês de fevereiro </br>**Nota:** A numeração dos documentos deve ser efetuada por grupo de contas de vencimentos com as respetivas exceções e não por conta.</br></br> **Conta 635-Encargos sobre renumerações da responsabilidade da entidade**</br></br> A numeração dos documentos varia consoante o encargo. Deve ser iniciada por 635, seguindo-se da indicação do mês - 01- e terminada com digitos sequenciais - 001. Por exemplo: </br> 63501**001** - encargo A </br> 63501**002** - encargo B  </br> **Nota:** Cada documentos deverá corresponder a cada conta 635</br></br> **Contas 638 - Outros gastos c/ Pessoal e 639-Outros encargos sociais** </br></br> A numeração dos documentos deve ser iniciada por 638 ou 639, seguindo-se da indicação do mês - 01- e terminada com digitos sequenciais - 001. Por exemplo: </br> 639**01001** - documento 1 do mês de janeiro. </br> 639**02001** - documento 1 do mês de fevereiro. </br></br> **Conta 622 - Prestação de serviços** </br></br> A numeração dos documentos deve ser iniciado por 62, seguindo-se da indicação do mês - 01- e terminada com digitos sequenciais - 001. Por exemplo: </br> 62201**001** - documento 1 do mês de janeiro </br> 622**02**001 - documento 1 do mês de fevereiro. </br>**Nota:** Cada documento deverá corresponder a cada conta.   |
|Data Doc.   |  52 - 59 (8) | Deve ser indicada a data do documento no seguinte formato: **DDMMAAAA**  |
|Conta Débito   | 60 - 109 (50)  | As contas a débito devem ser indicadas **sem pontos** e devem ser iniciadas pelo dígito **6**.   |
|Conta Crédito   | 110 - 159 (50)   | As contas a crédito devem ser indicadas **sem pontos** e devem ser iniciadas pelo dígito **2**.  |
|Importância   |160 - 177 (18)   |Deve ser indicada a importância.   |
|Sinal   |  178 (1)  |Deve ser indicado o sinal da importância (- ou +)   |
|Centro de Custo   | 179 - 188 (10)  |  Deve ser indicado o centro de custo.  |
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/101.sncap'">Descarregar TXT</button>
</div>

#### 12.1.2. Referência 102
|Campo|Posição |Observações|
|:---:|:---:|:---|
|Ref.   |1 - 3 (3)  | Indicar a referência do ficheiro. Neste caso específico a referência é **102**.   |
|Entidade   |  12 - 19 (8) | A numeração das entidades, para todas as contas iniciadas por 63, deve ser iniciada por 9963 e terminada com o indicativo do mês. Por exemplo:  </br> 9963**001** - janeiro </br>9963**002** - fevereiro </br> ...</br>9963**012** - dezembro    |
|Nº OD  | 20 - 27 (8)  | A numeração dos documentos deve ser inicida pela conta - 63 - seguindo-se do mês - 01 - e terminada com digitos sequenciais - 001. Por exemplo: </br> 6301**001** - documento 1 do mês de janeiro </br> 6301**002** - documento 2 do mês de janeiro </br> 63**02**001 - documento 1 do mês de fevereiro.  |
|Data Doc.   |  52 - 59 (8) | Deve ser indicada a data do documento no seguinte formato: **DDMMAAAA**  |
|Conta Débito   | 60 - 109 (50)  | As contas a débito devem ser indicadas **sem pontos** e devem ser iniciadas pelo dígito **6**.   |
|Conta Crédito   | 110 - 159 (50)   | As contas a crédito devem ser indicadas **sem pontos** e devem ser iniciadas pelo dígito **2**.  |
|Importância   |160 - 177 (18)   | Deve ser indicada a importância.  |
|Sinal   |  178 (1)  | Deve ser indicado o sinal da importância (- ou +)  |
|Centro de Custo   | 179 - 188 (10)  | Deve ser indicado o centro de custo.    |


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/101.sncap'">Descarregar TXT</button>
</div>

#### 12.1.3. Contas a crédito

As contas a crédito das faturas conferidas dos fornecedores (P2), bem como das OD's, são obtidas através da relação, previamente estabelecida, com as contas a débito dos cabimentos.

O utilizador deve selecionar o botão "Contas a crédito" para criar essas associações no sentido de garantir um bom registo das faturas.  

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ecee5791.png)

Ao clicar no botão é aberto o seguinte ecrã:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f8e80fa8.png)

Estas associações apresentadas, podem ser editadas, abatidas ou podem também ser adicionadas novas.

Para adicionar uma relação nova, o utilizador deve clicar sobre o botão "+Novo", preencher o novo campo disponível com as contas respetivas e por fim deve confirmar a alteração carregando no botão "Confirmar". O utilizador pode consultar as contas existentes no sistema através do botão ajuda ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bbc0de15.png) Abaixo estão apresentadas contas exemplo que podem ser criadas nesta tabela de associação.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/cont_cred_101.gif)

Esta tabela ficará guardada e poderá sempre ser editada pelo utilizador.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-377182a8.png)

>**Nota:** As contas 2xx devem ser sempre contas de **MOVIMENTO**.

Em caso de se pretender eliminar uma relação, o utilizador deve selecionar uma linha, clicando sobre a mesma duas vezes, e clicar no botão "-Abater".

O utilizador também pode guardar esta tabela num ficheiro CSV. Para este efeito, deve no campo respetivo colocar o diretório do seu computador onde pretende guardar o ficheiro. De seguida deve apenas clicar em "Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4fb86652.png)

O aspeto do ficheiro a ser guardado será como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-18f168ee.png)


#### 12.1.4. Processamento de Vencimentos

Relativamente ao processamento dos vencimentos em SNC-AP, e como principais alterações ao normativo contabilístico anterior (POCMS), deverá ser tido em atenção o que diz a CNC através das FAQ’s n.º 1 e 17:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fd8542a8.png)

</br>Fonte: http://www.cnc.min-financas.pt/faqs_publico.html

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f77a04e9.png)

</br>Fonte: http://www.cnc.min-financas.pt/faqs_publico.html

</br>No manual de implementação do SNC-AP (2ª versão), no Capítulo 4 – Normas e Contabilidade Pública, no âmbito da NCP 26 – Contabilidade e Relato Orçamental, em resposta à questão 2.17:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7e164ce0.png)

</br>Fonte:
<a href="http://www.cnc.min-financas.pt/pdf/SNC_AP/MANUAL%20DE%20IMPLEMENTACAO_SNC_AP_Versao2_HomologadoSEO.pdf">http://www.cnc.min-financas.pt/pdf/SNC_AP/MANUAL%20DE%20IMPLEMENTACAO_SNC_AP_Versao2_HomologadoSEO.pdf</a>

</br> De referir também a NCP 19 – Benefícios dos empregados, também referida no Manual de implementação (2ª versão), que menciona como benefícios de curto prazo:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-742828a7.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3d84f42f.png)

</br>Fonte:
<a href="http://www.cnc.min-financas.pt/pdf/SNC_AP/MANUAL%20DE%20IMPLEMENTACAO_SNC_AP_Versao2_HomologadoSEO.pdf">http://www.cnc.min-financas.pt/pdf/SNC_AP/MANUAL%20DE%20IMPLEMENTACAO_SNC_AP_Versao2_HomologadoSEO.pdf</a>

</br>_In Manual de implementação (2ª versão) pág 215_

</br>Os três passivos reconhecidos seriam eliminados na data do pagamento ao empregado e às
entidades credoras das retenções.

Estas são as referências que se conhecem até à data, relativas ao processamento dos vencimentos em SNC-AP.
Assim, tendo em conta as recomendações da CNC, às normas NCP do SNC-AP, construímos um pequeno exemplo que pretende ajudar a clarificar algumas dúvidas que têm surgido no registo contabilístico dos vencimentos.

</br>**Exemplo prático:**

No mês **n** do ano 201**N** a entidade pública tem a processar e pagar os vencimentos e os descontos dos seguintes trabalhadores:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5ea639a2.png)

Atendendo aos valores a processar obteríamos a seguinte folha de vencimentos:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-77f51f9f.png)

Admitindo que já tinham sido efetuados os registos do cabimento e do compromisso, pretende-se proceder aos registos do processamento, pagamento dos vencimentos aos trabalhadores e entrega dos descontos.

</br>**Classificadores a utilizar:**

Contabilidade orçamental: pelo valor despesa ilíquida de quaisquer descontos:  c.e. 010103 -  Pessoal dos Quadros - regime função pública; c.e.  010113 -  Subsidio de Refeição; c.  e. 010305A0A0 -  Contribuições para a segurança social -  CGA; 010305A0B0 -  Segurança social.

</br>**Registos contabilísticos:**

Quanto aos registos contabilísticos enuncia-se os registos no subsistema de contabilidade financeira, apenas para relembrar que deverão ocorrer em simultâneo, os registos no subsistema de contabilidade orçamental, conforme exemplo:

No subsistema da contabilidade financeira:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4e0eb5b8.png)

No subsistema de contabilidade orçamental:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4e400cab.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-556f2206.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-db6fae6d.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-37b5fab1.png)

</br>**Conclusões:**

Uma das principais alterações introduzidas pela NCP 26, consiste no tratamento das operações de tesouraria.
Em SNC-AP o pagamento dos descontos efetuados pelos trabalhadores é registado como pagamento decorrente de uma despesa de execução orçamental e não como Operação de Tesouraria.
</br>Decorre desta situação, que haverá que equacionar-se no momento do pagamento dos vencimentos, em que rubrica é que deve ser assumido o pagamento dos vencimentos, se na rubrica de vencimento principal ou em todas as restantes rubricas que constam na folha de vencimentos. Com efeito, os descontos incidem com maior expressão, na rubrica de vencimento principal. Neste contexto, por uma questão de controlo interno administrativo, neste exemplo registamos o pagamento líquido dos vencimentos em todas as reclassificações económicas até perfazer o total do valor a pagar. Enquanto não forem efetuados os pagamentos dos descontos, o saldo da conta 027-obrigações associadas a classificação económica 01.01.03-Pessoal dos Quadro-regime função publica, apresenta o valor dos descontos ainda não pagos.
Em 31 de dezembro, caso existam descontos por pagar, serão registados como obrigações a pagar e representam encargos orçamentais no ano seguinte.

</br>Relativamente à transição de normativo, concretamente aos descontos de dezembro de 2017 a pagar em janeiro de 2018, atendendo ao preconizado pela FAQ nº 17 da CNC (acima transcrita), estamos em crer que o tratamento contabilístico a seguir será o que seguidamente se expõe, a título de exemplo:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1411d5c8.png)

Em resumo salienta-se que os procedimentos a ter em conta no SICC SNC-AP, no que respeita o subsistema de contabilidade financeira são basicamente os mesmos (atente-se às contas do novo plano de contas). Já no que respeita ao subsistema de contabilidade orçamental devem ter em conta as alterações acima mencionadas.

</br> Processamento de vencimentos no SICC SNC-AP:

1. Após receção do ficheiro de vencimentos do RHV efetua-se a ligação do ficheiro de vencimentos:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-affa4e24.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-55254234.png)

De salientar que todo o registo da obrigação no subsistema de contabilidade orçamental é assegurado pelo sistema SICC SNC-AP, bem como o registo no subsistema de contabilidade financeira, assim estejam devidamente parametrizadas as contas respetivas a movimentar e assegurado os registos contabilísticos do cabimento e compromisso.

De seguida podem ser verificados os registos na respetiva conta corrente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f4309c7a.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-71b007fc.png)

Em resumo os lançamentos efetuados são os seguintes:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-aa7d2780.png)

De seguida efetuam-se os procedimentos atinentes ao registo dos pagamentos.

No que respeita aos descontos retidos para entrega a entidades terceiras, em SICC SNC-AP continuam a ser tratados através do menu de Fundos Alheios mediante o registo dos documentos RA-Receita e DA-Despesa:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-07220b0e.png)

Através do documento RA são efetuados os movimentos de retenção dos descontos:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7c38b23a.png)


Através do documento DA são efetuados os pagamentos dos descontos retidos:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-baad404f.png)

Como vimos anteriormente, uma das principais alterações introduzidas pela NCP 26, consiste no tratamento das operações de tesouraria.
Em SNC-AP o pagamento dos descontos efetuados pelos trabalhadores é registado como pagamento decorrente de uma despesa de execução orçamental e não como Operação de Tesouraria.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c7fc1833.png)

De salientar que o registo no subsistema de contabilidade orçamental poderá ser registado de duas formas, ou em simultâneo com a contabilidade financeira no documento acima indicado DA de Fundos Alheios, ou em alternativa através do registo de uma OD (operação diversa), no seguinte menu:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-144c9cf0.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b400d9a1.png)

Salienta-se que os exemplos apresentados neste documento são isso mesmo, exemplos!

Servem para demonstrar, de uma forma simples, os registos a efetuar. Cada entidade deverá atender ao caso concreto e adaptar os seus registos conforme os exemplos.

A consulta deste documento não dispensa a leitura das NCP do SNC-AP, do manual de implementação e FAQ’s da CNC, bem como as orientações da DGO/Unileo.


### 12.2. Ligações de Gestão de Stocks

A informação que deve ser enviada entre o departamento financeiro e o departamento de logística pode ser observada no seguinte esquema. Os ficheiros a serem importados no sistema, os que são referidos no esquema, são detalhadamente descritos ao longo deste capítulo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1ffc568a.png)

#### 12.2.1. Referências genéricas
Para importar dados relativos às referências genéricas dos Stocks o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9cfa4d6c.png)

</br> No ecrã referente às importações de dados de gestão de stocks, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d6ccda75.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos do ficheiro ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser validado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6c37d67c.png)

> **Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da gestão de Stocks, é possível importar ficheiros com as referências  **201, 203, 204, 205, 206, 207, 210, 211 e 214**.

 A descrição dos campos para cada uma das referências é apresentada seguidamente.

##### 12.2.1.1. Referência 201
Esta referência importa dados relativos a documentos do tipo **CB** proveniente dos Stocks. Para ficheiros de referência 201 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)   | 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/201.sncap'">Descarregar TXT</button>
</div>

##### 12.2.1.2. Referência 203
Ficheiros de referência 203 importam dados relativos a documentos do tipo **P1**. Para ficheiros de referência 203 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| NºCP| NºP1| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|20 - 27 (8) |28 - 39 (12)|52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/203.sncap'">Descarregar TXT</button>
</div>

##### 12.2.1.3. Referências 204, 205, 206 e 207
Ficheiros destas referências importam dados relativos a documentos do tipo **OD**. Para ficheiros de referência 204-207 os campos que devem estar preenchidos são:

|   | Ref.    | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   | Centro Custo |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Posição (Comprimento) | 1 - 3 (3) | 52 - 59 (8) | 60 - 109 (50)  | 110 - 159 (50)  | 160 - 177 (18) | 178 (1) | 179 - 188 (10) |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/204.sncap'">Descarregar TXT</button>
</div>

##### 12.2.1.4. Referência 210
Ficheiros de referência 210 importam dados relativos a documentos do tipo P2. Para ficheiros de referência 210 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição |Ent.|NºCP|NºP2| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo| Nº dias Data Vencimento |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   |1 - 3 (3)   | 4 - 11 (8)  | 12 - 19 (8)  | 20 - 27 (8)  |40 - 51 (12)   | 52 - 59 (8)  |60 - 109 (50)   |110 - 159 (50)   |160 - 177 (18)   |178 (1)   |179 - 188 (10)   |230 - 232 (3)   |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/210.sncap'">Descarregar TXT</button>
</div>

##### 12.2.1.5. Referência 211
Ficheiros de referência 211 importam dados relativos a documentos do tipo **P2**. Para ficheiros de referência 211 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição |Ent.|NºCP|NºP1|NºP2| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo| Nº dias Data Vencimento |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   |1 - 3 (3)   | 4 - 11 (8)  | 12 - 19 (8)  | 20 - 27 (8)  |28 - 39 (12)| 40 - 51 (12)   | 52 - 59 (8)  |60 - 109 (50)   |110 - 159 (50)   |160 - 177 (18)   |178 (1)   |179 - 188 (10)   |230 - 232 (3)   |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/211.sncap'">Descarregar TXT</button>
</div>

##### 12.2.1.6. Referência 214
Ficheiros de referência 214 importam dados relativos a documentos do tipo **CM**.Para ficheiros de referência 214 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   | Nº dias Data Vencimento |Nota de encomenda|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:--:|
|Posição (Comprimento)|1 - 3 (3)|4 - 11 (8) |52 - 59(8) |60 - 109 (50)|110 - 159 (50)|160 - 177 (18)|178 (1) |230 - 232(3)   | 250 - 269(10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/214.sncap'">Descarregar TXT</button>
</div>

#### 12.2.2. Refª 202 (Compromissos Assumidos)
Para importar dados relativos à Refª 202 de Stocks o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5be9deea.png)

Irá abrir o ecrã seguidamente apresentado onde o processo de importação de ficheiros segue o mesmo fluxo de trabalho das referências anteriores referentes à gestão de stocks.
Ficheiros de referência 202 importam dados relativos a documentos do tipo **CP**.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4d1dae6e.png)


|   | Ref.  | Nº Proc. Aquisição | Ent.| NºCP| NºCM| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Nº Dias Data Vencimento|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8) |40 - 51 (12)|52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |230 - 232 (3)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/202.sncap'">Descarregar TXT</button>
</div>

### 12.3. Ligações de Gestão de Imobilizado
Para importar dados relativos aos imobilizados o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9e5e2d6d.png)

</br> No ecrã referente às importações de dados de imobilizado, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1e524aec.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-22169578.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>Para importar ficheiros relativos ao imobilizado, devem ser importados os ficheiros de referência  **301, 302, 303, 304, 305, 306 e 307**. A descrição dos campos para cada uma das referências é apresentada seguidamente.

#### 12.3.1. Referência 301
Ficheiros de referência 301 importam dados relativos a documentos do tipo CB. Para ficheiros de referência 301 os campos que devem estar preenchidos são:

|   | Ref.  | NºProc. Aquisição | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)|52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/301.sncap'">Descarregar TXT</button>
</div>

#### 12.3.2. Referência 302
Ficheiros de referência 302 importam dados relativos a documentos do tipo CP. Para ficheiros de referência 302 os campos que devem estar preenchidos são:

|   | Ref.  |Ent.| NºCP |NºCM| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)|20 - 27 (8)|43 - 51 (9)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/302.sncap'">Descarregar TXT</button>
</div>

#### 12.3.3. Referência 303
Ficheiros de referência 303 importam dados relativos a documentos do tipo P1. Para ficheiros de referência 303 os campos que devem estar preenchidos são:

|   | Ref.  |Ent.| NºCP |NºP1| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) | 1 - 3 (3)  |12 - 19 (8)|20 - 27 (8)|28 -  39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/303.sncap'">Descarregar TXT</button>
</div>

#### 12.3.4. Referências 304, 305, 306, 307
Ficheiros destas referências importam dados relativos a documentos do tipo OD. Para ficheiros de referências 304 - 307 os campos que devem estar preenchidos são:

|     | Ref.    | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   | Centro Custo |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Posição (Comprimento) | 1 - 3 (3) | 52 - 59 (8) | 60 - 109 (50)  | 110 - 159 (50)  | 160 - 177 (18) | 178 (1) | 179 - 188 (10) |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/304.sncap'">Descarregar TXT</button>
</div>

### 12.4. Ligações de Faturação de Devedores
Para importar dados relativos à faturação de devedores o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6fc81755.png)

</br> No ecrã referente às importações de dados de faturas de devedores, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b7254af5.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-effe3987.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da gestão de imobilizado, é possível importar ficheiros de referência **401**. A descrição dos campos da referência é apresentada seguidamente. Estes ficheiros importam dados relativos a documentos do tipo FD.

#### 12.4.1. Referência 401
Para ficheiros de referência 401 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| NºP2| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| 40 - 51 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/401.sncap'">Descarregar TXT</button>
</div>

### 12.5. Ligações de Farmácias
Para importar dados relativos às Farmácias o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0629654e.png)

</br> No ecrã referente às importações de dados de farmácias, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".
<!--falta imagem-->

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-32659b0f.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-34e3c81a.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso de farmácias, é possível importar ficheiros com as referências  **702, 703, 704 e 706**.
A descrição dos campos para cada uma das referências é apresentada seguidamente.

>**Nota:** Alguns ficheiros variam a sua estrutura para entidades do tipo ARS e ULS. A descrição dos campos destes ficheiros é apresentada separadamente para cada referência.


#### 12.5.1. Referência 702
Ficheiros de referência 702 importam dados relativos a documentos do tipo P2. Para ficheiros de referência 702 os campos que devem estar preenchidos são:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 -  188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/702.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) |1 - 3 (3)|4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 112 (50)  | 113 - 162 (50)  |163 - 180 (18)   |  181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/702_ars.sncap'">Descarregar TXT</button>
</div>

#### 12.5.2. Referência 703
Ficheiros de referência 703 importam dados relativos a documentos do tipo OD. Para ficheiros de referência 703 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| NºOD| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| 40 - 51 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/703.sncap'">Descarregar TXT</button>
</div>

#### 12.5.3. Referência 704
Ficheiros de referência 704 importam dados relativos a documentos do tipo NC. Para ficheiros de referência 704 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| Nº NC/Série| Data Doc. | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| 28 - 39 (12)| 52 - 59 (8)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/704.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | Ent.| Nº NC/Série| Data Doc. | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| **28 - 42 (15)**| 55 - 62 (8)  | 113 - 162 (50)  |163 - 180 (18)   |  181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/704_ars.sncap'">Descarregar TXT</button>
</div>

#### 12.5.4. Referência 706
Ficheiros de referência 706 importam dados relativos a documentos do tipo DF. Para ficheiros de referência 706 os campos que devem estar preenchidos são:

|   | Ref.  | NºProc.Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/706.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 112 (50)  | 113 - 162 (50)  |163 - 180 (18)   |  181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/706_ars.sncap'">Descarregar TXT</button>
</div>

</br>**Contas a crédito**
</br> As contas a crédito das faturas conferidas dos fornecedores (P2) são obtidas através da relação, previamente estabelecida, com as contas a débito dos cabimentos.
O utilizador deve selecionar o botão "Contas a crédito" para visualizar as associações já estabelecidas pelo sistema e para adicionar ou remover associações.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ecee5791.png)

Ao clicar no botão é aberto o seguinte ecrã:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fb17ad84.png)

Para adicionar uma relação, o utilizador deve clicar sobre o botão "+ Novo", preencher o novo campo disponível com as contas e por fim deve confirmar a alteração carregando no botão "Confirmar". O utilizador pode consultar as contas existentes através do botão ajuda ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bbc0de15.png).

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ea6f22fc.png)

Em caso de se pretender eliminar uma relação, o utilizador deve selecionar uma linha e clicar no botão "- Abater".

### 12.6. Ligações do SISO/Reembolsos

#### 12.6.1. Ligações de faturas
Para importar dados relativos às faturas de SISO/Reembolsos o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets//mu_snc_ap-585d2317.png)

</br> No ecrã referente às importações de dados de SISO/Reembolsos, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9210b351.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.

</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6906f3e4.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da ligação SISO/Reembolsos, é possível importar ficheiros de referência  **501**. A descrição dos campos da referência é apresentada seguidamente. Ficheiros desta referência importam dado relativos a documentos do tipo P2.

</br>**Referência 501**

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº P1/P2| Data Doc. | Conta Débito | Conta Crédito | Importância| Sinal|Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|40 - 51 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/501.sncap'">Descarregar TXT</button>
</div>

#### 12.6.2. Exportação de Pagamentos
Para exportar pagamentos o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f629ba94.png)
_Em atualização_

#### 12.6.3. Importação de Entidades
Para importar dados relativos às entidades de SISO/Reembolsos o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c3ae6905.png)
_Em atualização_

### 12.7. Ligações dos MCDT
Para importar dados relativos a MCDT o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4637c493.png)

</br> No ecrã referente às importações de dados de MCDT, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

 ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-07e190a8.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.

</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-2a02b4e5.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da gestão de imobilizado, é possível importar ficheiros com as referências  **902, 903, 904, 905, 906 e 908**. A descrição dos campos para cada uma das referências é apresentada seguidamente.

>**Nota:** Alguns ficheiros variam a sua estrutura para entidades do tipo ARS e ULS. A descrição dos campos destes ficheiros é apresentada separadamente para cada referência.


#### 12.7.1. Referência 902
Ficheiros de referência 902 importam dados relativos a documentos do tipo P2. Para ficheiros de referência 902 os campos que devem estar preenchidos são:

Caso Geral:

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/902.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br> Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 112 (50)  | 113 - 162 (50)  |163 - 180 (18)   |  181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/902_ars.sncap'">Descarregar TXT</button>
</div>

#### 12.7.2. Referência 903
Ficheiros de referência 903 importam dados relativos a documentos do tipo OD. Para ficheiros de referência 903 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.|NºOD| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|40 - 51 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/903.sncap'">Descarregar TXT</button>
</div>

#### 12.7.3. Referência 904
Ficheiros de referência 904 importam dados relativos a documentos do tipo NC. Para ficheiros de referência 904 os campos que devem estar preenchidos são:

|   | Ref.  | Entidade|Nº NC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)|12 - 19 (8)|28 - 39 (12)| 52 - 59 (8)|60 - 109 (50)| 110 - 159 (50)  |160 - 177 (18)| 178 (1)|179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/904.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | Ent.|Nº NC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)|12 - 19 (8)|**28 - 42 (15)**| 55 - 62 (8)|63 - 112 (50)| 113 - 162 (50)  |163 - 180 (18)| 181 (1)|182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/904_ars.sncap'">Descarregar TXT</button>
</div>


#### 12.7.4. Referência 905
Ficheiros de referência 905 importam dados relativos a documentos do tipo CC. Para ficheiros de referência 905 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| Nº CC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) | 1 - 3 (3)|12 - 19 (8)|28 - 39 (12)| 52 - 59 (8)|60 - 109 (50)|110 - 159 (50)|160 - 177 (18)|178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/905.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref. | Ent.| Nº CC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) | 1 - 3 (3)|12 - 19 (8)|**28 - 42 (15)**| 55 - 62 (8)|63 - 112 (50)|113 - 162 (50)|163 - 180 (18)|181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/905_ars.sncap'">Descarregar TXT</button>
</div>

#### 12.7.5. Referência 906
Ficheiros de referência 906 importam dados relativos a documentos do tipo DF. Para ficheiros de referência 906 os campos que devem estar preenchidos são:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/906.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br> Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 112 (50)  | 113 - 162 (50)  |163 - 180 (18)   |  181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/906_ars.sncap'">Descarregar TXT</button>
</div>

#### 12.7.6. Referência 908
Ficheiros de referência 908 importam dados relativos a documentos do tipo CF. Para ficheiros de referência 908 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.|Nº CF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/908.sncap'">Descarregar TXT</button>
</div>

</br> **ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | Ent.|Nº CF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 112 (50)  | 113 - 162 (50)  |163 - 180 (18)   |  181 (1) |182 - 191 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/908_ars.sncap'">Descarregar TXT</button>
</div>
