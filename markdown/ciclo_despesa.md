# Ciclo de Despesa

Este capítulo tem por objetivo descrever o processo de registo de todos os documentos inerentes ao ciclo de despesa, isto é, desde o registo do cabimento até ao pagamento da fatura ao fornecedor.

> Recomenda-se o uso da tecla **_TAB_** para a navegação pelos campos dos ecrãs do sistema. Esta forma de navegação garante que todos os campos obrigatórios sejam preenchidos e validados permitindo o posterior desbloqueio de outros campos.

## 1. Cabimento (CB)

Esta opção permite, consultar ou criar um novo documento de Cabimento e com base em critérios selecionados pelo utilizador.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4ab45932.png)

Ao selecionar Cabimentos/Verificação Prévia, irá surgir o seguinte ecrã, cujo objetivo é a criação de um Cabimento (CB), conforme imagem abaixo:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ca9e7e59.png)

Neste ecrã devem ser preenchidos os campos obrigatórios - campos assinalados a laranja - referente ao exercício, ao Nº do Processo de Aquisição, às datas de documento e de contabilização e também o campo referente à importância do cabimento.

A numeração do cabimento é efetuada, de forma automática, no final do lançamento deste.

Os campos "Atividade/Departamento", "Projeto" e "Observações" podem ser alterados pelo utilizador consoante a necessidade.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/recolhas_cb.gif)

<!-- ![img_57a.gif](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_57a.gif) -->

O seu registo, o processo de cabimentação não sofre qualquer alteração, continuando a ter registar a referência o orçamento anual da entidade líquido de cativos devendo ser cabimentadas todas as despesas prováveis.

![img_58.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_58.png)

Ao clicar em "Gravar novo CB" abre novo ecrã, onde teremos um botão de ajuda no preenchimento dos seguintes campos:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-be036b66.png)

<!-- ![img_60.gif](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_60.gif) -->

|Campo|Obrigatoriedade|Descrição|
|:----|:--------------|:---------|
|Classificador Económico|**Sim**| Deve ser indicado o classificador económico que ficará associado à conta patrimonial. A indicação do classificador económico pode ser automática - Ver descrição abaixo da tabela.|
|Conta|**Sim**|Seleção da conta ao classificador. ![img_62.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_62.png)|
|Valor|**Sim**|Montante do cabimento: ![img_62a.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_62a.png)|

</br>__Existem dois métodos de Registo (método de Classificador Económico e método de Conta Patrimonial) definido no menu de parametrização> Instituição> Configurações__

![9561c58b](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/processos_snc_ap-9561c58b.png)

Quando o método das Contas Patrimoniais é selecionado, aquando o registo do CB, o classificador económico é apresentado, automaticamente, através da indicação da conta patrimonial, de acordo com a associação feita no Plano de Contas. No método do Classificador Económico, é necessário introduzir, primeiro, o classificador para que a conta patrimonial seja apresentada automaticamente.  
![img_61.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_61.png)

O método apresentado é de conta patrimonial que deverá ser registado a contas da classe 3, 4, 5, 6. Automaticamente associa o classificador económico, sendo que este poderá ser **alterado pelo utilizador**. Relativamente à chave orçamental esta transparece automaticamente de acordo com a chave definida no menu parametrização configuração e que nesta fase também pode ser alterada.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/recolhas_cont_cb_1.gif)

</br>__Se existirem para a mesma conta ou classificador económico chaves orçamentais diferentes então devem ser criadas várias linhas com a mesma informação mas com chaves orçamentais diferentes.__

</br>O preenchimento final, é idêntico ao do ecrã abaixo. O próximo passo é o de gerar, de forma automática, os movimentos na contabilidade selecionando o botão "Gerar Contabilidade".

No novo ecrã , aparecem os movimentos de lançamento do cabimento. Se os lançamentos estiverem corretos, o utilizador confirma, selecionando o botão de confirmação.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-e7636fee.png)

No início do registo do cabimento, caso o número de Processo de Aquisição já exista no sistema, este informa o utilizador através do campo específico para o efeito. Juntamente com a informação que o cabimento desse processo de aquisição já existe, também são apresentados os valores regularizados, disponíveis bem como os montantes resultantes das alterações efetuadas ao documento. O utilizador pode consultar o lançamento efetuado, através do clique no botão "Consultar" e, se o CB não estiver regularizado, pode efetuar alterações no próprio registo.  

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-0b32985b.png)

Uma outra forma de consultar um determinado cabimento é através da seleção do botão "Informação de CB".

### 1.1 Importação CB

Os documentos do tipo Cabimento podem também ser importados no sistema. Deve para isso, o utilizador clicar no botão "Importar" disponível no fundo do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ef856afa.png)

Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-29a883a8.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8fafadce.png)

<!-- ![img_67.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_67.png) -->

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

<hr>

Caso se trate de uma importação ou de valores introduzidos manualmente, no ecrã principal, o utilizador tem outros botões que permitem uma análise mais cuidada.

Desta forma, nos passos seguintes, é demonstrado o funcionamento dos outros botões constantes do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3036aeb5.png)

O utilizador ao escolher um dos seguintes botões obtém os ecrãs:

### 1.2 Informação de CB

Para gerar ficheiros relativos à Informação de CB, deve o utilizador primeiro indicar quais os critérios de pesquisa (1), de seguida deve clicar em "Calcular" (2). Para selecionar o documento, deve ser selecionada a respetiva checkbox (3) e por fim deve clicar no botão consoante o formato do ficheiro no qual pretende guardar a Informação de CB (4).

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-e89bd626.png)

Ao selecionar o botão "Gerar PDF" é gerado no ecrã o resultado da criação do CB.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8db9a67d.png)

Ao selecionar "Gerar CSV", o aspeto do mesmo será como o do seguidamente apresentado:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-4c287691.png)

### 1.3 Listagens de CB

Para gerar o documento com a listagem dos CBs selecionados deve o utilizador indicar os critérios de pesquisa de CBs (1), de seguida deve clicar em "Calcular" (2). Após terem sido apresentados os resultados de pesquisa na janela, deve o utilizador selecionar as checkbox referentes aos CBs pretendidos (3) e por fim clicar no botão consoante o formato do ficheiro no qual pretende guardar a listagem (4).

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-762f4bba.png)

Ao selecionar "Gerar PDF" é gerado o ficheiro com o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-697fdc78.png)

Ao selecionar "Gerar CSV" é gerado o ficheiro com o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f3087adb.png)

### 1.4. Alterações de Cabimentos (AM)

Neste processo o que se pretende demonstrar é uma alteração a um CB já existente. Desta forma, iremos contemplar mais uma linha de item financeiro ao CB criado anteriormente.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-19410ace.png)

Ao entrar no ecrã de Alteração de CB, deve o utilizador associar o “Nº do Processo de Aquisição” criado anteriormente, para proceder à alteração.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-c27d2f16.png)

Posteriormente à indicação do processo de aquisição e da execução da procura de CB, o utilizador deve, da lista de resultados apresentada, selecionar, com um **duplo clique**, a linha relativa ao documento pretendido.  

<!-- ![img_79.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_79.gif) -->

</br>Uma vez a linha subir para a janela de acima, deve o utilizador definir por que montante pretende fazer a nova AM, clicando posteriormente no botão "Gravar nova AM".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-bcfe7be3.png)

>**NOTA:** Na coluna "Disp. Diminuição" é indicado o valor disponível para reduzir no cabimento.

Novo ecrã surge, no qual o utilizador definirá o novo item financeiro, conta e importância a registar na alteração do CB. Finda a alteração, deverá gerar os documentos contabilísticos de forma automática pressionando para o efeito o botão "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-e3753de3.png)

Ao gerar contabilidade, são gerados movimentos de lançamento de cabimento. Se os lançamentos estiverem corretos, o utilizador deve confirmar os mesmos clicando no botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-51e17bca.png)

A alteração ao Cabimento acaba de ser efetuada, sendo que o sistema gera uma mensagem de confirmação.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-444b4587.png)

>**NOTA:** De realçar que qualquer movimento de estorno que seja efetuado no CB, não existe a necessidade de alterar o registo inicial, sendo que assim impede que haja alterações a nível dos mapas de execução orçamental.


#### 1.4.1. Importação de AM

Da mesma maneira que na importação de cabimentos, este processo de Alteração também pode ser feito por carregamento de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-d6c68727.png)

Ao clicar neste botão, o utilizador vai deparar-se com o seguinte ecrã, onde, para carregar o ficheiro, deve indicar o diretório de origem do mesmo:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-cadb8c11.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f39f69dd.png)


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AM_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-cb3a9570.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

#### 1.4.2. Alterações de Cabimentos - Transferência de Contas

É possível transferir um montante de uma conta para outra num CB, sem alterar o valor total desse CB. Para o efeito, deve ser lançado um AM e deve-se ter em consideração se o CB está ou não regularizado.

</br>**CB não regularizado**

</br> Quando o CB não está regularizado basta lançar um AM da seguinte forma:

</br> No ecrã de recolha de AM, o utilizador deve indicar o Ano e o Nº do Processo de Aquisição e clicar em "Procurar CB", para que o sistema mostre, na janela de baixo, todos os cabimentos que respeitem as condições indicadas.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8ac45f8c.png)

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-18509486.png)


De seguida, o utilizador deve clicar duas vezes em cima do CB a alterar, para que o mesmo passe para a janela de cima.

</br>Por se tratar de uma **Transferência de Contas**, o utilizador deve-o indicar selecionando a respetiva _checkbox_ e deve deixar o campo da **importância a 0€** para que o valor do CB não seja nem aumentado nem diminuido. Por fim, deve clicar em "Gravar nova AM".


![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6a7e9246.png)

No novo ecrã aberto, o utilizador deve lançar a conta pretendida com valor negativo e outra com valor positivo, de forma que a soma seja 0. Segue abaixo um exemplo de um CB com várias contas lançadas em que se pretende transferir 100€ da conta 626211 para a conta 626219.
De seguida, o utilizador deve clicar em "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-c9bd6619.png)

Para confirmar o registo, deve clicar em "Confirme".

</br>**CB regularizado**

</br> No caso do CB estar regularizado, deve-se ter em atenção se o valor a transferir já foi ou não "consumido" num CM e, no limite, num P2.

</br> Caso o CB estiver regularizado mas o valor a transferir não estiver "consumido", o processo do registo da alteração deve ser igual a um CB não regularizado.  

</br>Pretende-se transferir 500€ da conta 312629 para a conta, não lançada, 312625. O CB em questão encontra-se totalmente consumido pelo que, se deve efetuar o seguinte processo (**por esta ordem**):

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-321b926e.png)

1. **Anular a fatura (P2 e P1) com um AC;**

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-adae26b7.png)


2. **Anular CP com AL negativo na conta da qual se pretende transferir o valor;**

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-7a8e888a.png)

3. **Anular CM com AB negativo na conta da qual se pretende transferir o valor;**

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f7d3fbfe.png)

4. **Transferir o valor das contas num AM (como descrito para CB não regularizado);**

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-7c0bbbf8.png)

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5d8f4b72.png)

5. **Lançar os valores nas contas com AB e AL positivos e, lançar o P1 e o P2.**

</br>Lançamento do AB:

1)![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-4eaf50c2.png)

2)![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3d4c68ae.png)

Lançamento do AL:

1)![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-4e9fa5d4.png)

2)![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-e35496d7.png)

Lançamento do P2:

1)![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-d7d3f5a0.png)
2)![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f383ef6c.png)

## 2. Verificação Prévia (CM)

Entende-se por _Verificação Prévia (CM)_, a verificação prévia de fundos disponíveis, as obrigações de efetuar pagamentos a terceiros em contrapartida do fornecimento de bens e serviços ou da satisfação de outras condições. Os compromissos consideram-se assumidos quando é executada uma ação formal pela entidade, como seja a emissão de ordem de compra, nota de encomenda ou documento equivalente, ou a assinatura de um contrato, acordo ou protocolo, podendo também ter um carácter permanente e estarem associados a pagamentos durante um período indeterminado de tempo, nomeadamente, salários, rendas, eletricidade ou pagamentos de prestações diversas.

Por parte do utilizador, há necessidade de evidenciar novamente o “Número de Processo de Aquisição”. De forma automática, o preenchimento do “Valor disponível de Cabimento” aparece por defeito. Posteriormente, deve o utilizador indicar o montante, as datas de documento e de contabilização do CM e deve clicar no botão “Gravar novo CM”.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-a42c54b6.png)

Neste ecrã, o utilizador terá de introduzir o valor manualmente, para cada conta, e após confirmação dos elementos constituintes do CM, deve gerar os movimentos na contabilidade, utilizando o botão "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-063f0bec.png)

Os movimentos contabilísticos aparecem no ecrã, sendo que se estiverem corretos, deverá o utilizador selecionar o botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-40fe8f2f.png)

Uma nova mensagem surgirá com a numeração atribuída ao compromisso criado, significando assim que este processo está concluído.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-94553bbd.png)

### 2.1. Importação CM

Os documentos do tipo Compromisso podem também ser importados no sistema. Deve para isso, o utilizador clicar no botão "Importar" disponível no fundo do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3ee782e5.png)

Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-32976d17.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5b600345.png)


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CM-SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-4f37398c.png)

Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6278bdcf.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)


Sempre que um "Número de Processos de Aquisição" já tenha Compromissos associados, o sistema deve apresentar a seguinte mensagem:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f2d488bb.png)

### 2.2. Informação de CM

Após a criação do compromisso, o utilizador terá assim a possibilidade de ter “Informação do CM” criado, para o efeito tem de selecionar no botão "Informação de CM".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-624feab2.png)

Neste ecrã, deve o utilizador indicar os critérios de pesquisa e calcular o seu resultado. De seguida deve selecionar o documento pretendido e guardá-lo no formato que pretender.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8757ab4b.png)

Ao selecionar o botão "Gerar PDF", gera no ecrã o ficheiro com o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-0932642b.png)

Ao selecionar "Gerar CSV", o aspeto da informação de CM será como o do ficheiro seguidamente apresentado:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-054c999a.png)

### 2.3. Informação de Compromisso Orçamental

A _Informação de Compromisso Orçamental_ tem como objetivo integrar o processo de fiscalização prévia a enviar ao Tribunal de Contas (**Resolução nº 14/2011**).
No sentido de acomodar todas as informações em vigor, definidas pela ACSS, DGO e TC, o reporte de informação de compromisso orçamental deve ser executado no momento do CM e no momento do CP.

</br>Para gerar a informação de Compromisso Orçamental, deve o utilizador clicar no botão "Infor. da Exec.Orc.":

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-638f43c8.png)

No ecrã aberto devem ser indicados os critérios de pesquisa (1) seguindo-se do clique em "Calcular" para que o sistema apresente os documentos que respeitam os critérios indicados (2). de seguida, Da lista de resultados apresentada, devem ser selecionados os documentos pretendidos através da seleção da respetiva checkbox (3). Por fim, deve selecionar o formato de ficheiro no qual pretende guardar o documento, clicando no respetivo botão (4).   

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-69c8dcf2.png)

Ao selecionar "Gerar PDF", o ficheiro terá o aspeto como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3ec92949.png)

Ao selecionar "Gerar CSV", o ficheiro terá o aspeto como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b6ff5fbc.png)


### 2.4. Alteração de Compromisso (AB)

__Existe igualmente a possibilidade de proceder à alteração no Compromisso, pelo que o utilizador terá de ter em atenção que as alterações efetuadas também têm de estar alinhadas com o valor do Cabimento. O sistema deteta e envia mensagem de erro caso se verifique que o valor do compromisso seja superior ao cabimento, ou mesmo quando não existe cabimento para determinado item financeiro produzido posteriormente no compromisso. O processo em si é semelhante ao explicado anteriormente nas alterações dos cabimentos (AM).__

</br> Menu de acesso:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c02d02d9.png)

Nesta etapa, demonstramos, a título de exemplo, este processo de Alteração de Compromisso feita por carregamento de ficheiro através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-99c8775c.png)

Ao selecionar o botão "Importar", o utilizador vai deparar-se com o seguinte ecrã, sendo que para carregamento do ficheiro, tem de escolher o Diretório de Origem.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8dcfadf4.png)

O aspeto do ficheiro CSV. é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5624da01.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AB_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-af2ef553.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_105.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_105.png)

## 3. Lançamentos

Antes de realizar o registo de fatura FI, existe a necessidade de o utilizador verificar a disponibilidade do compromisso. Esta validação pode ser efetuada utilizando para o efeito, o botão "Consulta", explicado em passos anteriores.

</br>O menu de acesso ao registo de lançamentos é:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-27cda4ab.png)

Neste menu o utilizador tem acesso a três separadores diferentes: Comprimisso Assumido (CP), Processado-F.Rec./Conf.(P1) e Processado - F.Confer.(P2).

### 3.1. Compromisso Assumido (CP)

O utilizador neste separador, deve indicar o "Num. Compromisso (CM)". De forma automática, o sistema gera a data de criação do documento, a conta financeira associada, o respetivo montante e o valor disponível para regularização. A fase seguinte é a de definir a entidade. Para o efeito deve selecionar sobre o botão de ajuda para chamada de todas as entidades registadas na base de dados.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ed582083.png)

Para o exemplo em questão, foi criado um compromisso para demonstração do processo, no separador "Compromisso Assumido(CP)".

Este compromisso, para a entidade “240001 - Entidade 240001”, foi criado pelo montante abaixo indicado (1000€). O utilizador deve preencher todos os campos assinalados a laranja, navegando pelos mesmos utilizando a tecla TAB do teclado. Findo o preenchimento dos campos obrigatórios, deve clicar no botão "Gravar novo CP".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-bfbe6826.png)

O novo ecrã aberto irá apresentar os movimentos contabilísticos onde o utilizador deve preencher, manualmente, o valor relativo a cada conta registada, neste caso concreto, 500€ para cada uma. Após a indicação dos montantes, deve o utilizador clicar em "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-8f1eaf03.png)

Uma nova tabulação será aberta, na qual serão apresentados os movimentos contabilísticos. Deve o utilizador confirmar se os movimentos estão corretos e para finalizar deve clicar em "Confirme"

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5b97dd12.png)


Em caso de haver necessidade cria-se um "Processado - F.Conf.\Rec.(P1)" no separador seguinte. Caso não seja necessário, o utilizador prossegue para o separador "Processado - F.Confer. (P2)".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4e97c0a0.png)

#### 3.1.1. Importação CP

Os documentos do tipo Compromisso Assumido podem ser importados no sistema através de um ficheiro. Deve para isso, o utilizador clicar no botão "Importar" disponível no fundo do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-97507de1.png)

Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-d1ec4b78.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-03c76ca6.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CP_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

</br>Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-04fc2b1a.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

#### 3.1.2. Informação do Compromisso Orçamental

A _Informação de Compromisso Orçamental_ tem como objetivo integrar o processo de fiscalização prévia a enviar ao Tribunal de Contas (**Resolução nº 14/2011**).
No sentido de acomodar todas as informações em vigor, definidas pela ACSS, DGO e TC, o reporte de informação de compromisso orçamental deve ser executado no momento do CM e no momento do CP.

</br>Para gerar a informação de Compromisso Orçamental, deve o utilizador clicar no botão "Infor. da Exec.Orc.":

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-7d0436f2.png)

No ecrã aberto devem ser indicados os critérios de pesquisa (1) seguindo-se do clique em "Calcular" para que o sistema apresente os documentos que respeitam os critérios indicados (2). de seguida, Da lista de resultados apresentada, devem ser selecionados os documentos pretendidos através da seleção da respetiva checkbox (3). Por fim, deve selecionar o formato de ficheiro no qual pretende guardar o documento, clicando no respetivo botão (4).   

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-f1ec79c6.png)

Ao selecionar "Gerar PDF", o ficheiro terá o aspeto como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6d2eefa2.png)

Ao selecionar "Gerar CSV", o ficheiro terá o aspeto como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-37f23269.png)

### 3.2. Processado-F.Rec.\Conf. (P1)

Neste separador o utilizador pode registar uma fatura em Receção e Conferência. Para o efeito, deve preencher os campos com os dados da respetiva nota de encomenda (CP) indicando, por isso, o Nº do Compromisso Assumido (CP) para que o sistema mostre o Valor Disponível e a Entidade correspondente. De seguida, o utilizador deve inserir o "Nº de guia/factura", as datas de documento e de contabilização bem como a "Importância" pretendida. os campos relativos à data de vencimento, Projeto, atividade, série, e Observações podem ser preenchidas/editadas. Para gravar o documento, deverá ser selecionado o botão "Gravar novo P1".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-922c231d.png)

Será, de seguida aberta a janela de Recolha de Contabilidade com a conta de custos preenchida. Para finalizar este registo, o utilizador deve introduzir a conta de contrapartida e o respetivo valor. Para gerar os movimentos contabilísticos, deve-se clicar em "Gerar Contabilidade"

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-73ab9242.png)

No separador "Analítica", que é aberto ao gerar os documentos na contabilidade, é necessário atribuir um centro de custo para as contas de classe 6. O botão arredondado permite o acesso a todos os centros de custos inseridos no sistema. Para terminar, deve ser selecionada a opção "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-cf8f1e50.png)

#### 3.2.1. Importação P1

Estes documentos, do tipo Faturas em Receção e Conferência podem também ser importados no sistema. Deve para isso, o utilizador clicar no botão "Importar" disponível no fundo do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ea5b693c.png)

Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-fc2c1462.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b47f305a.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P1_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

</br>Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-c16ab3e1.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)


### 3.3. Processado - F.Confer. (P2)

Neste separador, o utilizador pode registar faturas conferidas. Como estas faturas podem regularizar notas de encomenda diretamente ou faturas em receção e conferência, o preenchimento dos campos depende do tipo de documento anterior: "Compromisso Assumido" ou "F.Conf.\Rec.".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b18892f4.png)

Quando "Compromisso Assumido" é selecionado, o utilizador deve preencher os campos relativos à "Entidade" e ao número do "Compromisso Assumido" gerado para que o sistema indique o montante disponível para regularização. De seguida devem ser preenchidos os campos do "Nº de factura" bem como o da "Data da Contabilização" e o da "Data de Documento" e a respetiva "Importância". Para gravar, deve selecionar sobre o botão "Gravar novo P2". Os campos da Data de Vencimento, da atividade, Projeto e Observações podem ser preenchidos/editados pelo utilizador, nesta fase.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-42e6a0ea.png)

No ecrã de Recolha de Contabilidade, o utilizador deve introduzir a conta de classe de contrapartida e respetivos valores. De seguida, deve o utilizador clicar em "Gerar Contabilidade" para que o sistema gira os movimentos contabilísticos.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-113102b9.png)

Ao gerar os documentos na contabilidade, é necessário que na analítica seja atribuído um centro de custo para as contas classe 6. Através do botão de ajuda o utilizador tem acesso a todos os centros de custo inseridos em sistema. Para finalizar o registo do documento do tipo P2, deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-396d31d8.png)

__O botão "Desdobrar Conta", permite ao utilizador, para a mesma conta (separador "Analítica"), a possibilidade de escolher o número de linhas para desdobrar, no sentido de integrar vários Centros de Custo.__

Posteriormente à confirmação, o sistema gera uma mensagem com a seguinte informação.

![img_115.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_115.png)

Após confirmação, o sistema assume assim, que para o compromisso e para a entidade já existe o registo de fatura.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-e61ea067.png)

Para gerar um **P2 proveniente de um P1**, o utilizador deve selecionar a opção "F.Conf.\Rec.". De seguida, deve preencher os campos da "Entidade", do número de "F.Conf.\Rec.", do "Nº de factura", da "Data de Contabilização", da "Data de Documento" e da "Importância" da fatura. Para gravar, deve selecionar o botão "Gravar novo P2".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-9b22d03e.png)

No ecrã que surge após a gravação, o sistema apresenta a conta 225 proveniente do P1 indicado. Em contrapartida a esta conta, o utilizador deve adicionar a conta "221" e atribuir-lhe o respetivo montante, neste exemplo será de 1000€. De seguida, deve selecionar o botão "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-32e8386f.png)

Após confirmação, o sistema assume assim que para o P1 e para a entidade já é existente o registo de fatura.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-83c86c93.png)

#### 3.3.1. Importação P2

Estes documentos do tipo Faturas Conferidas podem ser importados no sistema através de um ficheiro CSV. Deve para isso, o utilizador clicar no botão "Importar" disponível no fundo do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-0e13049c.png)

Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-1cc4c44c.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-241d6bb8.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P2_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

</br>Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-a7826854.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)

### 3.4. Importação de documentos de forma agrupada

É também possível, nesta fase de registos, importar documentos de uma forma agrupada, isto é, importar todos os documentos referentes ao ciclo de despesa até às faturas inclusive (CB, CM, CP, P1 e P2). Para tal, deve o utilizador selecionar o botão "Ciclo da Despesa" disponível ao lado do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-7ac9a385.png)

No ecrã que é aberto, ecrã este que é semelhante ao ecrã de importações descritas anteriormente, deve o utilizador selecionar da diretoria, o ficheiro em **formato CSV**. De seguida deve pressionar no botão "Ver/Testar Ficheiro" para que o sistema valide o ficheiro que se pretende importar.

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

- A situação A representa o caso quando para o mesmo cabimento (CB) existem várias faturas (P2);
- A situação B representa o caso em que os documentos contemplam várias contas.

Para ambas as situações, está também apresentada a forma como são calculados os valores dos documentos quando são "desdobrados" em várias linhas.

### 3.5. Alteração de Lançamentos (AL)

Neste processo o que se pretende demonstrar é uma alteração a um CP existente. O caminho que o utilizador deve seguir na aplicação é o seguinte:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2374f53.png)

No ecrã aberto, para efetuar o registo de uma alteração pode optar por um dos dois processos: registo manual ou através da importação de um ficheiro CSV.

</br> Para registar uma AL manualmente, o utilizador deve, primeiro indicar a "Entidade", o "Ano" e o "Nº do CP" sobre o qual pretende efetuar a alteração. Para que o sistema apresente o Compromisso assumido pretendido, deve o utilizador clicar em "Procurar CP".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5e84b4f4.png)


O CP pretendido irá aparecer na janela de baixo do ecrã e, para o selecionar, deve o utilizador clicar na respetiva linha duas vezes. Desta forma o CP irá passar para a janela de cima podendo agora o utilizador indicar o valor da AL que pretende lançar, bem como a sua "Data de Contabilização". Para gravar a AL pretendida, deve o utilizador clicar em "Gravar nova AL". Antes de indicar a importância da AL que se pretende lançar, pode o utilizador verificar, nas informações relativas ao CP selecionado os valores disponíveis quer para a diminuição quer para o aumento.

</br> Caso o pretendido seja diminuir o valor do CP, no campo da importância, o valor indicado deve ser negativo (como se pode verificar no exemplo seguinte).  

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-69f2e447.png)

Ao clicar em "Gravar nova AL", novo ecrã será aberto onde o utilizador deve confirmar a conta e indicar o respetivo valor. De seguida deve clicar em "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-4eca82c9.png)

O sistema irá lançar os movimentos contabilísticos e irá apresentá-los no ecrã. Após a sua confirmação, deve o utilizador clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-70d39ed6.png)

Como a numeração das alterações é automática, após a confirmação do registo da AL, o sistema irá gerar uma mensagem a informativa com o respetivo número de documento.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-aa4ca3c2.png)


#### 3.5.1. Importação de AL

Caso o utilizador pretenda lançar as Alterações ao Compromisso Assumido via ficheiro CSV, deve para o efeito, no ecrã inicial clicar no botão "Importar" disponível no fundo do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3a94a93a.png)

Ao selecionar esta opção, o utilizador vai se deparar com o seguinte ecrã, onde deverá indicar o diretório de origem do ficheiro que pretende importar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-02fcf8ce.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-9f1ebbcb.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AL_SNCAP.csv'">Descarregar CSV</button>
</div>

Antes da importação do ficheiro, o utilizador tem de validar a sua estrutura e o conteúdo, através do clique no botão "Ver/Testar Ficheiro". Ao validar o ficheiro, o utilizador constata que os elementos deste estão visíveis, e por isso validados e prontos para importação. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã, bem como é gerada uma mensagem ao utilizador da existência dos mesmos.

</br>Para visualizar os erros gerados, o utilizador pode guardar o relatório de erros em ficheiros de dois formatos: CSV e PDF, selecionando para o efeito o respetivo botão. Neste caso, o ficheiro deve ser corrigido e testado novamente.

Após validação dos elementos do ficheiro a importar, deve o utilizador clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b4c65ee0.png)

Para confirmar a importação dos elementos do ficheiro, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![img_importacao_concluida_sucesso.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_importacao_concluida_sucesso.png)


## 4. Autorização de Pagamento (AP)

A autorização de pagamento das despesas, são autorizadas pelos dirigentes dos serviços ou outros que detenham autorização, mediante operações de tesouraria ou ainda através de transferência bancária, quando esta forma se revelar a mais conveniente.

Para aceder ao menu, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2995da1.png)

Neste processo, o utilizador terá de identificar a Entidade e seguidamente deve clicar em "Pesquisar Documentos", para que o sistema devolva todos os documentos por regularizar da entidade identificada. Pode ainda definir a ordenação de documentos: se pretende que estejam ordenados por Data ou por Número de Documento.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-e00027c9.png)

 Como resultado da pesquisa, na janela inferior do ecrã irá aparecer uma lista de documentos por regularizar. Estes documentos podem ser do tipo: P2, NC, DF e CF. Para selecionar o/os documento/s pretendido/s deve o utilizador clicar duas vez sob os mesmos. De seguida, deve indicar a forma de pagamento pretendida - Tesouraria ou por Transf. Bancária. Caso selecione a última, deverá também indicar a Instituição Bancária, o IBAN e o Motivo.

|Campo|Descrição|
|:---|:---|
|NIB/IBAN|Este campo dá a hipótese do utilizador escolher se é um IBAN Credor ou _Factoring_, aparecendo as seguintes opções: ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4a09e554.png)|
|Motivo|O motivo deverá igualmente ser escolhido dentro das parametrizações inseridas no sistema: ![img_secu_pag_igcp.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_secu_pag_igcp.png)|

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-2a2dbc0a.png)

O utilizador pode também, indicar o Nº da Autorização no respetivo campo do ecrã, bem como as datas deste documento. Caso o utilizador não o indique, a numeração da autorização de pagamento será atribuída automaticamente pelo sistema. Tendo preenchidos todos os campos do ecrã, deve o utilizador clicar em "Gravar nova AP".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-a3fb46b4.png)

Irá ser aberto novo ecrã, onde o utilizador deve confirmar os lançamentos apresentados. Para concluir o processo, deve clicar em "Confirmar".
Como não foi indicado, no ecrã inicial, o número da AP, este é atribuído automaticamente pelo sistema. O número da AP é comunicado ao utilizador através de uma mensagem como a apresentada seguidamente.  

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-fc8cf699.png)

### 4.1. Importação AP

Este processo de Autorização de Pagamento também pode ser efetuado por carregamento de ficheiro CSV através do botão "Importar".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-74c318e4.png)

Ao selecionar o botão vai ser aberto um novo ecrã onde o utilizador, para carregar o ficheiro CSV, tem de escolher o diretório de origem do mesmo.
![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-ece28b2f.png)

O aspeto do ficheiro CSV é o abaixo demonstrado, sendo que o mesmo deve obedecer ao critério das colunas estipuladas, para efeito de carregamento.

> **NOTA:** Na imagem estão destacados com cor os campos que são de preenchimento obrigatório.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-73301e06.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AP_SNCAP.csv'">Descarregar CSV</button>
</div>

Caso o utilizador pretenda importar APs para serem pagos por Transferência Bancária, deve preencher também os campos: Conta Bancária, IBAN e Categoria de Motivo.

Na coluna Categoria de Motivo, deve indicar o respetivo **código numérico**.

Seguidamente é apresentada a lista de códigos numéricos a utilizar, conforme o motivo pretendido.

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

</br>Antes da importação, o utilizador, tem de usar o botão "Ver/Testar Ficheiro". Ao selecionar este botão, o utilizador constata que os elementos do ficheiro CSV estão visíveis e que o ficheiro integrado está testado. Caso ocorram erros, os mesmos produzem um relatório no ecrã, na caixa criada para o efeito, no canto inferior direito do ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-141ac688.png)

Após validação dos elementos integrados e constatado que os valores estão coerentes com o ficheiro integrado, o utilizador deve assim usar o botão "Importa Ligação". Depois de selecionar e de forma automática, o sistema gera uma mensagem de confirmação, com a indicação abaixo descrita.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8bbe8dd6.png)


### 4.2. Impressão de Autorizações de Pagamento (AP)

Nesta etapa, é demonstrado o procedimento para fazer as impressões das APs (de forma _individual_ ou _global_) geradas no passo anterior. Para isso, deve o utilizador seguir o seguinte caminho no sistema:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-97b60cbd.png)

_Autorização de Pagamento Individual_

</br>Para gerar as autorizações de pagamento individuais, o utilizador pode indicar apenas uma entidade, colocando o seu código nos campos "Pri.Entidade" e "Últ.Entidade", ou pode indicar um intervalo de entidades a fim de selecionar vários documentos para impressão individual. De seguida, deve clicar no botão "Calcular" para o sistema apresentar as autorizações de pagamento registadas.

>NOTA: Por defeito, o sistema apresenta as autorizações de pagamento por regularizar. Caso o utilizador pretenda gerar ficheiros para impressão, de APs já regularizadas, deve selecionar a respetiva _checkbox_.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-a62d3c62.png)

O utilizador tem de selecionar **SEMPRE** os documentos que deseja, sejam para consulta ou impressão através da seleção da _checkbox_ no ecrã.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-2281b109.png)

Para gerar o ficheiro para impressão, deve o utilizador clicar no botão "Gerar PDF".

</br>O aspeto do ficheiro PDF gerado, relativo à autorização de pagamento, é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b299a39f.png)


_Autorização de Pagamento Global_

</br>Para gerar uma autorização de pagamento coletiva, o utilizador deve definir um intervalo de entidades, bem como indicar, através da seleção da respetiva _checkbox_, que se trata de uma Autorização de Pagamento Global. De seguida, deve clicar em "Calcular" para o sistema apresentar todas as APs referentes a entidades indicadas.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-a237ee7c.png)

O utilizador tem de selecionar **SEMPRE** os documentos que deseja, sejam para consulta ou impressão através da seleção da _checkbox_ no ecrã.

Para gerar o ficheiro para impressão, deve o utilizador clicar no botão "Gerar PDF".

</br>O aspeto do ficheiro PDF gerado, relativo à autorização de pagamento, é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-5990b3b1.png)

### 4.3. Ofício de Pagamento

Para aceder ao ecrã onde é gerado o ofício de pagamento, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d12f61d8.png)

No ecrã aberto, o utilizador deve preencher os seguintes campos:

|Campo| Descrição |
|:--|:--|
|Pri. Entidade    | Primeiro código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.    |
|Últ. Entidade    |Último código da entidade a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo.    |
|Primeira Data:    | Data do primeiro do documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado neste campo.    |
|Última Data:    | Data da último documento a extrair. Apenas é extraida informação cujo código seja igual ou superior ao indicado no campo superior e menos ou igual ao indicado neste campo. |
|Referência    | Referência do ofício.   |
|Texto    | Texto que irá aparecer no documento gerado.    |

</br> Deve também ser indicado se os documentos que se pretendem incluir no ofício devem ser regularizados ou ainda por regularizar.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-243a80a9.png)

Após ter definido os critérios de pesquisa, deve o utilizador clicar em "Calcular" para que o sistema apresente todos os documentos que estejam de acordo com os critérios de pesquisa. Para selecionar o documento, deve o utilizador preencher a _checkbox_ do documento pretendido.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-05ab035f.png)

Pode agora Ofício ser impresso ou enviado através de email.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-482e81f2.png)

##### Imprimir

Quando esta opção é selecionada, o aspeto do ficheiro PDF gerado é semelhante ao seguidamente apresentado.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f5a24fd0.png).

Quando é selecionada mais do que uma AP, cada uma vez numa página.

##### Email

Quando esta opção é selecionada, surge um novo ecrã onde o utilizador deve selecionar as entidade a quem pretende enviar o oficio, inserir o texto que aparecerá no corpo do email enviado. De seguida deve clicar em "Calcular" para verificar os emails das entidades selecionadas. Por fim, deve clicar em "Enviar".

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

## 7. Anulações/ Regularizações (AC)

Para efetuar o registo de uma anulação de fatura (AC) o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-489e9cf7.png)

Este documento serve para registar, contabilísticamente, uma anulação de uma fatura quando não existe uma nota de crédito qua a possa "anular".

Para o efeito, no ecrã de recolha de informação de AC, o utilizador deve indicar a entidade e as datas do documento, clicando de seguida em "Ver Documentos", para que o sistema apresente todas as faturas da entidade indicada.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-cc69908a.png)

Da lista de faturas apresentada, o utilizador deve selecionar apenas **uma** fatura clicando sobre a mesma duas vezes. De seguida, deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-53731319.png)

Na nova janela aberta, o utilizador deve completar a informação, indicando a conta a crédito/débito e o respetivo montante. De seguida, o utilizador deve clicar em "Gerar Contabilidade".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-39b0500a.png)

Caso a conta indicada seja uma conta de classe 6, ao gerar contabilidade, irá ser aberto um novo ecrã onde o utilizador deve indicar o centro de custo.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-41bdc422.png)

Para finalizar, o utilizador deve clicar em "Confirme".

### 7.1. Importação de AC

O processo de registo de ACs também pode ser efetuado através da importação de ficheiro CSV.

Para importar o ficheiro CSV de AC, no ecrã de recolha de informação inicial, de AC, o utilizador deve clicar em "Importar".

Na nova janela aberta, o utilizador deve selecionar, do diretório do seu computador, o ficheiro CSV para importação. De seguida, deve clicar em "Ver/ Testar Ficheiro" para que o sistema valide a estrutura do mesmo.

Caso a mesma obedeça aos critérios dos campos a integrar, as duas janelas ficarão preenchidas com informação do ficheiro. Caso existam incoerências, estas serão comunicadas ao utilizador na janela destinada para o efeito.

Para finalizar a importação do ficheiro, deve clicar em "Importar Ligação".

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

## 8. Notas de Crédito (NC)

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

### 8.1. Importação NC

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

#### 8.1.1.  Reposição Abatida aos Pagamentos (RAP)

Sempre que seja detetado um pagamento indevido deve-se prosseguir à emissão de uma RAP que é considerada contabilisticamente como uma Nota de Crédito (NC).

A existência de uma reposição abatida pressupõe que houve um pagamento excessivo em relação a uma determinada aquisição, cuja regularização é efetuada, no respetivo ano financeiro, através da correção da dotação utilizada e do respetivo saldo disponível, aumentando-o. Decorre deste entendimento que a reposição abatida aos pagamentos não seja tida como uma receita orçamental.


Os registos a efetuar na Contabilidade Financeira devem ser com as contas 2x, 3x, 4x ou 6x. A nivel de registos na Contabilidade Orçamental, estes são efetuados de forma automática pelo sistema e são os seguintes:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-55401346.png)


Desta forma, no ecrã relativo ao registo de uma nova NC deve ser indicado na respetiva checkbox que se trata de uma RAP. Todos os preenchimentos seguintes seguem a mesma lógica que uma Nota de Crédito convencional.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e86b55f0.png)

No momento do registo da AP, deixa de ser necessário associar uma factura pelo facto de se tratar de uma reposição abatida aos pagamentos. O valor deste documento será negativo.

Mais uma vez, aquando a realização do pagamento da AP criada, o sistema irá efetuar registos, automaticamente, na contabilidade orçamental, que serão os seguintes:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-39b58c60.png)

## 9. Anulação de Faturas P2/NC (AF)

Em conformidade com as recomendações da Autoridade Tributária e Aduaneira (AT), não é possível anular diretamente uma fatura. A anulação do movimento de uma fatura é feita através da emissão de uma nota de crédito. Sem reflexo para a contabilidade, o que se pretende com este tipo de documento é a regularização do mesmo, de modo a que o seu impacto no final seja nulo.

Este tipo de documento, proveniente do P2, DF, CF ou da NC (exceto RAP), obriga o utilizador a selecionar pelo menos uma fatura e uma nota de crédito com o objetivo do resultado final ter o valor de "0" para proceder ao registo de anulação. O objetivo deste documento é regularizar ambos os documentos selecionados sem que seja necessário efetuar registos contabilísticos.

Para aceder ao ecrã de registo da Anulação de Fatura (AF) deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a697fec9.png)

No ecrã aberto, o utilizador deve indicar os critérios de pesquisa de documento. Primeiro, deve indicar a entidade e de seguida deve clicar no TAB do teclado do seu computador para visualizar toadas as faturas por regularizar da entidade indicada ou pode indicar, nos campos respetivos, o número e o tipo de documento que pretende visualizar. Na janela de baixo irão aparecer todos os documentos encontrados que correspondem aos critérios de pesquisa inseridos.

Para efetuar o registo da AF, deve o utilizador selecionar os documentos P2 e/ou DF  e/ou CF **e** NC, clicando sobre os mesmos duas vezes. Para confirmar o registo, deve o utilizador clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a2cddb55.png)

O sistema irá gerar uma mensagem onde é indicado o número da AF registada.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-92452daa.png)

O utilizador pode agora imprimir a AF criada. Para tal deve, no ecrã de recolha de dados, indicar a entidade e número de documento. De seguida deve clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ef916b2c.png)

Na nova janela aberta, deve indicar os intervalos das entidades das quais pretende visualizar os documentos, as datas e os números dos documentos (FD e CC) que pretende visualizar. De seguida deve clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-05f2a540.png)

O aspeto do ficheiro PDF gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f0fb5277.png)


## 10. Crédito sobre Faturas  (CF)

Para aceder ao ecrã de recolha de dados relativos a crédito sobre faturas, deve o utilizador seguir o seguinte caminho na aplicação:

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

### 10.1. Importação de CF

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

## 11. Débito sobre Faturas (DF)

Para aceder ao ecrã de recolha de dados relativos a débito sobre faturas, deve o utilizador seguir o caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e056b915.png)

No ecrã que é aberto, deve o utilizador preencher os seguintes campos obrigatórios. De seguida deve clicar em "Gravar novo DF".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-790a7191.png)

No preenchimento destes campos obrigatórios, no caso do utilizador indicar um número de CP que não exista ainda, este pode ser criado nesse momento. Para tal, o sistema gere uma mensagem a indicar que o CP é inexistente e pede para inserir o Nº de CB.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-d17ee958.png)

No novo ecrã aberto, o utilizador deve preencher as contas e os movimentos respetivos.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a200cc59.png)

Findo o preenchimento das contas, o utilizador deve clicar em "Confirme".

Como o CM e CP tinham consumido o valor total do CB criado, o sistema criou as alterações aos documentos, nomeadamente a AL, AB e AM. Estas alterações são comunicadas ao utilizador através de uma mensagem como a seguidamente apresentada.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-43790ce8.png)

### 11.1 Importação DF

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

## 12. Listagem Despesa

Para abrir o ecrã relativo à listagem da despesa deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-4022c2fc.png)

Este menu permite ao utilizador obter um mapa de documentos possibilitando visualizar a sua relação e estado (regularizado ou por regularizar).  

Para tal, deve o utilizador indicar os critérios de pesquisa dos documentos a visualizar.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-6bd00b0b.png)

Primeiro deve indicar qual o Tipo de Documento Principal. Para o efeito, deve clicar por cima do campo a preencher e de seguida deve selecionar, do esquema do Fluxo de Despesa, o tipo de documento principal.

De seguida deve clicar no campo relativo ao "Tipo de documento secundário" e selecionar, do esquema, o tipo de documento que será o secundário.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/lista_despesa.gif)

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

|NÚMERO DOCUMENTO|CONTA|
|:--:|:--:|
| ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-99cf994b.png) | ![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-3c35318b.png) |  
