<div class="cabecalho"><img src="https://spmssicc.github.io/pages/img/logos/SPMS2016B_272x105.png">
Orçamental (em atualização)</div>

Este menu permite ao utilizador carregar o orçamento ordinário, económico e o LCPA. Permite também a produção de respetivos mapas, de receita e de despesa para controlo orçamental.   

> Recomenda-se o uso da tecla **_TAB_** para a navegação pelos campos dos ecrãs do sistema. Esta forma de navegação garante que todos os campos obrigatórios sejam preenchidos e validados permitindo o posterior desbloqueio de outros campos.

## 1. Orçamento Anual
Para registar as dotações através do carregamento do Orçamento anual o utilizador deve seguir o caminho:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8570877f.png)

### 1.1. Recolha de Propostas Orçamentais

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f63301e8.png)

O formulário para recolha de propostas orçamentais é composto por:

| Opção | Descrição |
|:----|:----------|
| Ano | Exercício a que diz respeito a informação da instituição|
| Orçamento Ordinário | A seleção desta opção apenas deve ser feita se se tratar de carregamento de um orçamento ordinário ![img_orç_ordinario.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_orç_ordinario.png) |
| Alteração Orçamental | A seleção de sta opção apenas deve ser feita se se tratar de registo de uma alteração orçamental. Ao selecionar, automaticamente aparece o número de lançamento o qual se pretende alterar. ![img_alteracao_orc_num_lancamento.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_alteracao_orc_num_lancamento.png) |
| Atividade/Departamento | Identificação do tipo de Atividade/Departamento. Na seleção do botão de ajuda, o utilizador carregando no círculo ![img_radio_unselected.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_radio_unselected.png) pode obter uma listagem de todos os tipos de Atividades/Departamentos existentes|
| Data | Data àqual se faz o carregamento do orçamento ordinário ou a alteração orçamental |
| Observações | Campo de observações onde estão ou devem ser colocadas todas as informações pretendidas pelo utilizador|
| Data aprovação | Data quando o orçamento foi aprovado |
| Confirme | Ao clicar neste botão, abrirá a proposta orçamental a ser carregada com identificação dos classificadores económicos e valores a integrar|

</br>Neste ecrã, o utilizador deve decidir os valores a constarem na proposta do orçamento através da inserção dos montantes de receita ou despesa pelos vários itens de orçamento.
Nesta etapa, o utilizador que efetua o carregamento tem de ter em conta a divisão pelas respetivas rubricas orçamentais. Nesta fase deve verificar se o total das receitas é igual ao total das despesas.

#### 1.1.1. Orçamento Ordinário

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/Criacao_orcamento.gif)

É importante referir que o botão "Desdobrar conta", permite desdobrar os classificadores económicos e permite o registo de diferentes chaves orçamentais.
Ao clicar no "Confirme", o sistema criará assim de forma automática um novo ecrã, com a criação da PO.
O utilizador tem de proceder à aprovação, através do botão "Aprovar". Assim dá indicação ao sistema que os valores anteriormente carregados, fazem parte do orçamento ordinário.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a4492ed6.png)

</br>Após o processo de aprovação, novo ecrã surge, sendo que agora só existe a possibilidade de “Anular aprovação”, “Consulta” ou “Sair”.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a9aedb21.png)

|Botão| Descritivo|
|:----|:----------|
|Gravar Alterações|Este botão permite gravar alterações que tenham sido necessárias de ajustar|
|Consulta|Este botão permite ao utilizador consultar os valores carregados de orçamento, bem como os respetivos classificadores económicos|
|Abater|Este botão permite eliminar uma entidade. Após carregar neste botão, o utilizador, tem de carregar no botão Confirmar de forma a que a informação seja validada e gravada|
|Sair|Este botão permite ao utilizador sair do ecrã corrente|

##### Importação PO
Este processo de carregamento do Orçamento Ordinário bem como das alterações do mesmo pode ser efetuado através da importação de ficheiro em formato CSV.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-dbcbf021.png)

Uma nova janela irá abrir onde o utilizador deve escolher do diretório de origem, o ficheiro que pretende importar. Seguidamente, deve testar se a estrutura do ficheiro selecionado é correta através da seleção do botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1832d719.png)

Quando o ficheiro tem a estrutura correta, os campos do ecrã aparecem preenchidos com os elementos do ficheiro importado.
Por fim o utilizador deve confirmar a importação através da seleção do botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-505866f0.png)
No caso do ficheiro ter erros, estes são reportados na janela criada para o efeito. Estes erros têm de ser corrigidos e o ficheiro tem de ser novamente testado.
</br>O ficheiro CSV a ser importado deve ter o seguinte aspeto:


![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-a7726889.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PO_SNCAP.csv'">Descarregar CSV</button>
</div>

##### Alteração Orçamental

É **imperativo**, por parte do Departamento responsável, analisar a necessidade da modificação e os motivos que originam as alterações orçamentais que possam ocorrer, tendo em conta o enquadramento legal para a alteração orçamental pretendida.
Posteriormente, esta informação (Alteração orçamental) será carregada em SIGO para decisão (aprovação/rejeição) da DGO (Direção-Geral do Orçamento). Aquando o recebimento da deliberação da DGO, estão reunidas as condições para o carregamento do Orçamento no SICC SNC-AP.

</br>No ecrã e para efeitos de registo, ao selecionar "Alteração Orç", de forma automática surge o “Número de Lançamento” que se pretende para proceder ao registo da nova alteração.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ba2a79c7.png)

>**Nota:** Para navegar entre os campos e para desbloquear botões do ecrã, deve utilizar a tecla **TAB**

Selecionando a “Nova alteração”, o sistema de forma automática gera novo ecrã, no qual mostra todos os classificadores económicos com valores a 0, onde se pode registar a alteração orçamental com os montantes pretendidos. No seguinte exemplo, foi retirado valor parcial do carregado inicialmente na rubrica de "Representação" para a rubrica de "Ajudas de custo". Findas as alterações, deverá confirmar.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-a00e2e44.png)

Após a confirmação surge novo ecrã com a informação que a alteração orçamental com o número de lançamento “1” é existente em sistema. Poderá assim o utilizador fazer a “Consulta” ou “Abater” o registo da alteração orçamental.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f229ceb3.png)

Se as alterações estão validadas, o próximo passo é de “Aprovar” para que o sistema assuma os novos valores propostos.

##### Importação de Alteração Orçamental

Para importar uma alteração orçamental, deve ser utilizado o mesmo _layout_ que para importação de um orçamento ordinário.

Deve-se ter em atenção que no campo "Nº PO" deve estar indicado 1, 2, etc consoante o número da alteração a efetuar.

Pretendo-se carregar uma alteração orçamental, no ficheiro devem constar apenas rubricas que serão alteradas com as respetivas alterações. Segue abaixo um exemplo de alterações:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-44da4a20.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PO_SNCAP.xlsx'">Descarregar CSV</button>
</div>

#### 1.1.2. Consulta de Contabilidade

É possível proceder à “Consulta” e verificar o resultado das alterações geradas nos passos anteriores.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-453ceda9.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c362c238.png)

### 1.2. Mapas Orçamentais

De modo a analisar os orçamentos da despesa/receita, o utilizador pode aceder oa seguinte menu:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7a5287c2.png)


#### 1.2.1 Mapas - Orçamento de Despesa/Receita

Nos mapas, os ecrãs são idênticos na construção dos relatórios. Desta forma, o seguinte menu e respetivos submenus, permitem ao utilizador fazer uma análise ao Orçamento da despesa.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-65cce466.png)

Ao clicar, surge o ecrã abaixo e que permite proceder à escolha do tipo de informação que pretende analisar, podendo para o efeito fazer várias combinações possíveis.

##### Orçamento de Despesa

![img_38.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_38.png)

| Campo | Obrigatoriedade | Descrição |
|:----|:---------|:---------|
| Exercício | Obrigatório | Exercício a que dizem respeito as informação da instituição|
| Proposta | Obrigatório | Seleção de um dos campos: ![img_39.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_39.png) |
| Orçamento | Obrigatório | Seleção de um dos campos: ![img_40.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_40.png) Ao selecionar a “Alteração Orçamental”, surge automaticamente para preenchimento: ![img_41.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_41.png) |
| Financiamento | Obrigatório | Seleção de um dos campos: ![img_42.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_42.png) |
| Atividades/Departamento | Obrigatório | Seleção de um dos campos: ![img_43.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_43.png) |
| Pri. Data | Obrigatório ||
| Últ. Data | Obrigatório ||

|Botão|Descrição|
|:----|:---------|
|Ficheiro|Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido.</br>![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-aed34711.png)|
|Imprimir|Este botão permite que o utilizador gere relatório diretamente no ecrã|


O exemplo seguinte, demonstra um relatório de alteração orçamental gerada em passos anteriores, evidenciando os respetivos itens financeiros e respetivos valores.

![img_46.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_46.png)


## 2. Fundos disponíveis (LPCA)

Neste processo, e através do caminho abaixo indicado, será demonstrado o processo de registo dos Fundos disponíveis (LCPA).


![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4582f3fc.png)

Entende-se por Fundos Disponíveis, as verbas disponíveis a curto prazo. Incluem, quando aplicável e desde que tenha sido comprometido ou gasto:

1. A dotação corrigida líquida de cativos, relativa aos três meses seguintes;
2. As transferências ou subsídios com origem no Orçamento do Estado, relativos aos três meses seguintes;
3. A receita efetiva própria que tenha sido cobrada, ou recebida como adiantamento;
4. A previsão da receita efetiva própria a cobrar nos três meses seguintes;
5. O produto de empréstimos contraídos nos termos da lei (as transferências ainda não efetuadas decorrentes de programas e projetos do QREN e de outros programas estruturais, cujas faturas se encontrem liquidadas e devidamente certificadas ou validadas);
6. Outros montantes autorizados nos termos do artigo 4.º da LCPA.

![img_8a.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_8a.png)

Nos próximos passos, vai ser demonstrado o processo de criação dos fundos disponíveis. Neste ecrã, o utilizador deve escolher:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-05d65587.png)


| Opção | Descrição |
|:----|:----------|
| Ano | Exercício a que dizem respeito as informação da instituição|
| Mês | Seleção do mês para carregamento dos fundos|
| Alteração | Seleção do número de alteração que se pretende|
| Data | - - - - - - |
| Observações | Campo de observações onde estão ou devem ser colocadas todas as informações pretendidas pelo utilizador|
| Diretório (...) | Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido. </br> ![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_11.png) |
| Novo Orçamento | Este botão permite a gravar alterações que tenham sido necessárias de ajustar|
| Produção de mapa em CSV | Esta opção permite a produção do mapa em ficheiro com extensão CSV|
| Consulta | Este botão permite ao utilizador consultar os valores carregados dos fundos disponíveis|
| Sair | Este botão permite ao utilizador sair do ecrã corrente|

</br>Após o preenchimento dos campos atrás referidos, e sendo que se trata de um Novo Orçamento, o ecrã que surge é o de preenchimento dos valores de orçamento de fundos próprios.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-51e69794.png)

A previsão de receitas próprias é corrigida do desvio negativo apurado entre as previsões efetuadas nos meses anteriores e as receitas efetivamente cobradas.

No final de cada mês, o utilizador ao Confirmar, surge no ecrã a indicação de:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4840cf40.png)

Para validar, que o sistema efetua um controle dos fundos criados, não permitindo a criação de Compromissos com valor superior aos Fundos Disponiveis, fica o exemplo abaixo:

#### 2.1.1. Criação de Cabimento

O processo de criação de cabimentos e compromissos encontra-se detalhado no ponto 3.1 do documento.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3243dd2d.png)

#### 2.1.2. Verificação prévia de fundos disponíveis

O sistema efetua no processo de despesa, uma verificação de fundos que atribui um número sequencial e valida a realização de compromisso assumido por parte da gestão de compras.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-909cca06.png)

Mensagem do sistema indicando que as importâncias inseridas não correspondem aos valores dos fundos criados.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fc10784d.png)

### 2.2. Mapas (LPCA)

#### 2.2.1. Tabela 1 – Fundos disponíveis

O utilizador neste processo, tem a possibilidade de extrair relatórios do sistema com base nas informações e valores introduzidos nos passos anteriores.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-e49b6f4a.png)

|Botão|Descrição|
|:----|:---------|
|Extrato|Este botão permite gravar alterações que no diretório escolhido pelo utilizador|
|XML|Esta opção permite a produção do mapa em ficheiro com extensão XML|
|Mapa|Este botão permite ao utilizador consultar diretamente o mapa no ecrã. ![img_32.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_32.png)|
|Sair|Este botão permite ao utilizador sair do ecrã corrente|


- Qualquer uma das extrações permite ao utilizador ter o controlo dos Fundos disponíveis através de relatórios que espelham a atividade e fundos utilizados.

|Opção|Descrição|
|:----|:---------|
|Ano|Exercício a que dizem respeito as informação da instituição|
|Mês|Seleção do mês para carregamento dos fundos. ![img_mes_janeiro.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_mes_janeiro.png)|
|Diretório|Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido.</br> ![img_33.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_33.png)|

#### 2.2.2. Tabela 4 - (SPA’s): Passivos/ Contas a pagar

De igual modo à extração dos mapas anteriores, o utilizador nesta Tabela, usa o mesmo procedimento.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-ac87b689.png)

|Botão|Descrição|
|:----|:---------|
|Extrato|Esta opção permite a produção do mapa em ficheiro CSV|
|XML|Esta opção permite a produção do mapa em ficheiro XML|
|Mapa|Este botão permite ao utilizador consultar diretamente o mapa no ecrã. ![img_35.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_35.png)|
|Sair|Este botão permite ao utilizador sair do ecrã corrente|


- Qualquer uma das extrações permite ao utilizador ter o controlo dos Fundos disponíveis através de relatórios que espelham a atividade e fundos utilizados.


|Opção|Descrição|
|:----|:---------|
|Ano|Exercício a que dizem respeito as informação da instituição|
|Mês|Seleção do mês para carregamento dos fundos. ![img_mes_janeiro.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_mes_janeiro.png)|
|Diretório|Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido.</br> ![img_36.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_36.png)|


## 3. Mapas de Execução Orçamental

Relativamente a este processo, o Mapa de Execução Orçamental da Despesa e Mapa de Execução Orçamental da Receita, têm como finalidade permitir o controlo da execução orçamental da despesa e receita durante o exercício:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-871fecbd.png)

Para tal, as opções no ecrã permitem imprimir os formulários (gerando PDF), bem como, a extração para formato CSV, tendo o utilizador de definir o caminho para gravação do ficheiro.

### 3.1. Controlo Orçamental - Despesa

![img_48.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_48.png)

|Campo|Obrigatoriedade|Descrição|
|:----|:--------------|:---------|
|Exercício|Obrigatório|O utilizador deverá introduzir o ano do exercício pretendido, no formato AAAA. Por exemplo “2015”. Por defeito, é atribuído ao campo o ano corrente|
|Primeira Conta|Obrigatório|O utilizador deve indicar a primeira conta a partir da qual (inclusive) pretende obter as informações. Por defeito, o sistema utiliza a primeira conta existente|
|Última Conta|Obrigatório|O utilizador deve indicar a última conta até à qual (inclusive) pretende obter as informações. Por defeito, o sistema utiliza a última conta existente|
|Data|Obrigatório|O utilizador deve colocar a Data de Contabilização até à qual pretende incluir os dados (por defeito, o sistema coloca a data atual)|

Carregando no botão "Imprimir" o sistema irá gerar um PDF com o seguinte formato:

![img_49.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_49.png)

Este relatório, permite ao utilizador visualizar os conteúdos da informação do mapa diretamente no ecrã, incluindo as alterações orçamentais efetuadas anteriormente.
O procedimento do mapa 7.2 é idêntico ao explicado anteriormente, sendo apenas diferente o resultado final, dependendo de estarmos na receita ou na despesa.

![img_50.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_50.png)

- Irá ser incluída a chave orçamental neste mapa

### 3.2. Mapa - Alterações Orçamentais Despesa/Receita

Os Mapas das Alterações Orçamentais da Despesa e Alterações orçamentais da Receita têm por finalidade evidenciar as alterações orçamentais existentes durante o exercício depois da dotação e previsão iniciais:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6f71eb5c.png)

Ao clicar, é mostrado o ecrã abaixo e que permite proceder à escolha do tipo de informação que pretende analisar, podendo para o efeito fazer várias combinações possíveis.

![img_52.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_52.png)

|Campo|Obrigatoriedade|Descrição|
|:---|:---|:---|
|Exercício|Obrigatório|Exercício a que dizem respeito as informação da instituição|
|Proposta|Obrigatório|Seleção de um dos campos: ![img_valores_proposta_orcamental.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_valores_proposta_orcamental.png)|
|Orçamento|Obrigatório|Seleção de um dos campos: ![img_alteracao_orcamental.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_alteracao_orcamental.png) Ao selecionar a “Alteração Orçamental”, surge automaticamente para preenchimento: ![img_num_alt_orcamental.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_num_alt_orcamental.png)|
|Financiamento|Obrigatório|Seleção de um dos campos: ![img_56.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_56.png)|
|Atividades/Departamento|Obrigatório|Seleção de um dos campos: ![img_57.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_57.png)|
|Pri. Data|Obrigatório|Definir a data de início da pesquisa|
|Últ. Data|Obrigatório|Definir a data final da pesquisa|

|Botão|Descrição|
|:---|:---|
|Ficheiro|Este botão permite ao utilizador escolher o diretório de gravação do Excel que irá ser produzido.![img_57a.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_57a.png) ![img_57b.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_57b.png)|
|Imprimir|Este botão permite que o utilizador gere relatório diretamente no ecrã|
|Sair|Este botão permite que o utilizador saia do ecrã e regresse ao menu inicial|

O exemplo seguinte, demonstra um relatório de alteração orçamental gerada em passos anteriores, evidenciando os respetivos itens financeiros e respetivos valores.

![img_54.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_54.png)

O procedimento destes mapas é idêntico ao explicado anteriormente, sendo apenas diferente o resultado final, dependendo de estarmos na receita ou na despesa.

![img_55.png](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/img_55.png)

## 4. Orçamento Económico

Este menu permite à instituição introduzir no sistema o orçamento económico. Para tal, deve o utilizador seguir o caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-15b7a60d.png)

### 4.1. Propostas Orçamentais Económicas

No ecrã aberto, deve o utilizador percorrer os campos do ecrã até ao campo "Data:" com a tecla TAB. Após a indicação da data, deve o utilizador clicar em "Novo Orçamento".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4df2e660.png)

No novo ecrã aberto, o utilizador deve introduzir a conta e indicar o respetivo valor no campo Despesa ou Receita, consoante a conta introduzida.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6a70e5fb.png)

>**NOTA:** A navegação entre os campos deve ser efetuada com a tecla TAB.

Para introduzir uma nova linha, deve o utilizador clicar em cima da linha vazia e efetuar o processo de registo já descrito.

Para finalizar, deve clicar em "Confirme".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/orc_econ.gif)

Para aprovar o Orçamento introduzido, o utilizador deve premir a tecla TAB até o botão "Aprovar" ficar disponível. De seguida deve clicar nele.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-6a86bef1.png)

### 4.2. Importação PE

O Orçamento Económico pode ser importado através do carregamento de um ficheiro CSV.

Deve, para o efeito, o utilizador clicar no botão "Importar", disponível na parte inferior do ecrã de recolha do orçamento.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-c24e2386.png)

Na nova janela aberta, o utilizador deve selecionar o ficheiro a importar do diretório do seu computador e, de seguida, deve clicar em "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-99f75ffd.png)

Quando o ficheiro tem a estrutura correta, os campos do ecrã aparecem preenchidos com os elementos do ficheiro importado.
Por fim o utilizador deve confirmar a importação através da seleção do botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-d4737d43.png)

No caso do ficheiro ter erros, estes são reportados na janela criada para o efeito. Estes erros têm de ser corrigidos e o ficheiro tem de ser novamente testado.
</br>O ficheiro CSV a ser importado deve ter o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-34975321.png)


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PE_SNCAP.csv'">Descarregar CSV</button>
</div>

### 4.3. Mapas de controlo

#### 4.3.1. Orçamento de Compras

Para produzir o mapa de controlo do orçamento de compras deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-9fc57c2b.png)

No ecrã aberto, deve o utilizador indicar que valores do orçamento serão incluídos no mapa, o tipo de orçamento (ordinário ou a alteração), o intervalo dos meses a serem incluídos e o departamento.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-1c4014f4.png)

Após terem sido indicados os parâmetros, o utiliazdor pode guardar o mapa num ficheiro CSV ou PDF.

Para gerar o ficheiro CSV, deve ser selecionado o diretório e de seguida deve-se clicar em "Ficheiro CSV".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-66e5741a.png)

O aspeto do ficheiro gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-ca7a942e.png)

Para gerar o mapa em formato PDF, deve o utilizador clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-a3d3589f.png)

O aspeto do ficheiro PDF gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-bbd094d2.png)

#### 4.3.2. Orçamento Económico - Custos

Para produzir o mapa de controlo do orçamento económico relativo a custos deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-e87edba7.png)

No ecrã aberto, deve o utilizador indicar que valores do orçamento serão incluídos no mapa, o tipo de orçamento (ordinário ou a alteração), o intervalo dos meses a serem incluídos e o departamento.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-41334625.png)

Após terem sido indicados os parâmetros, o utilizador pode guardar o mapa num ficheiro CSV ou PDF.

Para gerar o ficheiro CSV, deve ser selecionado o diretório e de seguida deve-se clicar em "Ficheiro CSV".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-bcccc830.png)

O aspeto do ficheiro gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-b4e8dba1.png)

Para gerar o mapa em formato PDF, deve o utilizador clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-4b6db435.png)

O aspeto do ficheiro PDF gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-f5ab0c8d.png)

#### 4.3.3. Orçamento Económico - Proveitos

Para produzir o mapa de controlo do orçamento económico relativo a custos deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-27c2f95e.png)

O processo de produção do mapa é igual ao descrito em 4.3.2.

#### 4.3.4. Orçamento de Investimento

Para produzir o mapa de controlo do orçamento económico relativo a custos deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-6a466170.png)

No ecrã aberto, deve o utilizador indicar que valores do orçamento serão incluídos no mapa, o tipo de orçamento (ordinário ou a alteração), o intervalo dos meses a serem incluídos e o departamento.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-9dc61bf9.png)

Após terem sido indicados os parâmetros, o utilizador pode guardar o mapa num ficheiro CSV ou PDF.

Para gerar o ficheiro CSV, deve ser selecionado o diretório e de seguida deve-se clicar em "Ficheiro CSV".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-f86d04ed.png)

O aspeto do ficheiro CSV gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-e5f67f53.png)

Para gerar o mapa em formato PDF, deve o utilizador clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-56200c5c.png)

O aspeto do ficheiro PDF gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-1edc3502.png)

#### 4.3.5. Orçamento de Financeiro

Para produzir o mapa de controlo do orçamento de compras deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-4d2511e4.png)

No ecrã aberto, deve o utilizador indicar que valores do orçamento serão incluídos no mapa, o tipo de orçamento (ordinário ou a alteração), o intervalo dos meses a serem incluídos e o departamento.

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-1fa50585.png)

Após terem sido indicados os parâmetros, o utilizador pode guardar o mapa num ficheiro CSV ou PDF.

Para gerar o ficheiro CSV, deve ser selecionado o diretório e de seguida deve-se clicar em "Ficheiro CSV".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-84bffb60.png)

O aspeto do ficheiro gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-02b35956.png)

Para gerar o mapa em formato PDF, deve o utilizador clicar em "Imprimir".

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-ac987fb1.png)

O aspeto do ficheiro PDF gerado é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/orcamento.assets/orcamento-87910c39.png)
