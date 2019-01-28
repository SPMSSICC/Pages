# Gestão de Perfis de Acesso

Este menu serve para o responsável de uma instituição possa gerir os acessos dos utilizadores ao sistema SICC SNC-AP bem como as funcionalidades disponíveis para os mesmo.

Seguidamente está descrito o processo de criação, definição e atribuição dos perfis de acesso, bem como estão descritas novas funcionalidades disponíveis apenas aos responsáveis de cada organismo.

O menu Gestão de Perfis de Acesso encontra-se disponível no menu principal da aplicação "Utilitários".

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-0e96a5c3.png)

Neste menu o responsável/supervisor pode:

1. definir os grupos/perfis de acesso;
2. definir as permissões para cada grupo/perfil;
3. criar e gerir os utilizadores do sistema SICC SNC-AP.

## 1 Gestão de Grupos

Para iniciar a gestão de perfis de acesso ao sistema SICC SNC-AP, o gestor do sistema de uma entidade deve, em primeiro lugar, definir os grupos/perfis do sistema.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-94f8ac5b.png)

Esta gestão de grupos/perfis pode ser efetuada a qualquer altura ao longo do exercício, permitindo assim a adaptação dos perfis mediante a necessidade do organismo.

No momento da disponibilização deste menu, alguns grupos/perfis já foram criados podendo, em caso de necessidade, serem alterados. Trata-se dos seguintes perfis:
1.	Supervisor
2.	Contabilidade
3.	Tesouraria
4.	Consulta
5.	GERAL

### 1.1 Criar novo Grupo

Para criar um novo grupo/perfil, deve o utilizador efetuar os seguintes passos:

1.	Clicar em “+Novo”
2.	Indicar o Código do grupo. Este deve ser diferente dos que já estão inseridos na tabela apresentada;
3.	Premir na tecla TAB do teclado do computador;
4.	Indicar o Nome do novo grupo/perfil;
5.	Clicar em “Confirmar”.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-2c095d39.png)

### 1.2 Abater Grupo

Para abater um grupo, basta ao utilizador posicionar o cursor em cima da linha do grupo a abater e clicar em “- Abater”. Para finalizar deve-se clicar em “Confirmar”.

>**NOTA**: Não podem ser abatidos grupos que estejam atribuídos a utilizadores. Nestes casos, deve-se primeiro atribuir um outro grupo ao utilizador em questão e de seguida abater o grupo pretendido.


## 2 Gestão de Privilégios

O passo seguinte é da atribuição dos privilégios (permissões) a cada grupo/perfil existente no sistema.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-3a18e480.png)

Aquando a disponibilização deste menu, os grupos já se encontram parametrizados. Isto é, já foram atribuídos os privilégios a cada grupo. No entanto, cada organismo pode alterar estas permissões consoante a sua necessidade.

As permissões possíveis são:

**Alteração** – Permite ao utilizador efetuar/alterar registos, produzir  e importar ficheiros, etc;

**Consulta** – Permite ao utilizador visualizar ecrãs do sistema, pesquisar informação dentro dos ecrãs e produzir ficheiros (listagens e mapas);

**S/A** – O utilizador não tem acesso ao ecrã na sua totalidade.

O grupo/perfil Supervisor, sendo a figura máxima do sistema, é parametrizado centralmente e tem acesso ao sistema total podendo alterar, criar ou eliminar qualquer informação na aplicação.
Para os restantes grupos do sistema, o responsável pode alterar os privilégios, através da seleção da respetiva _checkbox_, nos menus com fundo branco (menus que resultam num ecrã).

>**NOTA**: Os menus com o fundo cinzento não podem ser alterados.

Assim, no topo do ecrã de gestão de privilégios está indicado o grupo a parametrizar. Desta forma, apenas se pode parametrizar um grupo de cada vez.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-d79f484f.png)

No fundo do ecrã, encontra-se a legenda dos privilégios possíveis.

No final da parametrização dos privilégios para um determinado grupo/perfil, deve o utilizador clicar em “Confirmar” para que o sistema grave as alterações efetuadas.

</br>O aspeto do ecrã de gestão de privilégios é o seguinte:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-0e72e571.png)

O utilizador pode guardar esta informação num ficheiro de formato CSV. Para o efeito, deve selecionar a diretoria do seu computador onde pretende guardar esta informação e para produzir o ficheiro, deve clicar em “Gerar CSV”.

O aspeto do ficheiro CSV criado é o seguinte:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-5b55511e.png)

No ficheiro CSV gerado, os menus que apresentam a célula em branco (como no caso de Configurações para o grupo Contabilidade na imagem abaixo) significa que os utilizadores que têm o perfil de Contabilidade atribuído, não têm acesso ao ecrã de Configurações.

Nos casos quando o acesso é negado a um menu completo, no ficheiro é indicado “Sem acesso".

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-fcfd9b06.png)

## 3 Utilizadores

De seguida, pode o supervisor gerir os utilizadores do sistema SICC SNC-AP, criando/eliminando os mesmos e gerindo os seus perfis de acesso à aplicação.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-d42f7fcb.png)

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-f189382e.png)

### 3.1 Criar novo Utilizador

Para criar um utilizador novo, deve o Supervisor efetuar os seguintes procedimentos, preenchendo os respetivos campos obrigatórios.

1 - Clicar em “+Novo”;

2 - Indicar o Nome de Utilizador;

3 - Premir na tecla TAB;

4 - Indicar a Password. A palavra chave deve ser composta por 10 caracteres e deve conter 3 dos seguintes 4 conjuntos de caracteres:

        - minúsculas
        - MAIÚSCULAS
        - algarismos
        - ! " # $ % & ' ( ) * + , - . / : ; < = > ? @ [\ ] ^_


5 - Indicar o Email do utilizador;

6 - Indicar o Grupo/perfil;

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-517ca3c7.png)

7 - Indicar o Estado do utilizador. Este pode ser: Ativo – O utilizador pode aceder à aplicação, Bloqueado – o utilizador não tem acesso à aplicação ou Expirado – o utilizador não tem acesso à aplicação.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-62993283.png)

8	- Pode também ser indicada a data de bloqueio do utilizador. Isto é, o dia a partir do qual o utilizador deixa de ter acesso à aplicação. Este campo não é obrigatório.

9 - Para finalizar, deve clicar em "Confirmar".

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-e7a7c7b5.png)

Caso seja necessário, o utilizador pode produzir o ficheiro de formato CSV com a listagem de todos os utilizadores do sistema SICC SNC-AP da sua Instituição. Para o efeito, deve indicar a diretoria onde pretende guardar o ficheiro gerado e por fim, deve clicar em “Gerar CSV”.

O aspeto do ficheiro gerado é o seguinte:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-b91c61ce.png)

## 4 Gestão do sistema

Este menu – Gestão do Sistema – permite gerir determinados dados do sistema, designadamente os ficheiros importados (TXT, CSV e de Transferências Bancárias) e parametrizações de contas no sistema. Ao longo da evolução do SICC, serão acrescentadas outras funcionalidades a este menu.


### 4.1 Expurgo de Ficheiros

Este submenu permite ao utilizador **expurgar** ficheiros de formatos TXT, CSV assim como os ficheiros de transferência bancária.


Para aceder a este submenu, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-466cd264.png)

#### 4.1.1 Expurgo de TXT

Este menu permite ao utilizador expurgar ficheiros do formato TXT (ficheiros provenientes de ligações de outros SI).

No ecrã aberto, deve o utilizador, em primeiro lugar, pesquisar o ficheiro que pretende expurgar.
Para pesquisar os ficheiros TXT, é necessário indicar os seguintes parâmetros:

- o **intervalo de entidades** para as quais foram efetuados lançamentos através do ficheiro;
- a **data contabilística** que foi indicada aquando a integração do ficheiro TXT;
- a **referência** do ficheiro a expurgar (101, 102, 201, 202, 214, 305, 405, etc).

Para efetuar a pesquisa propriamente dita, deve o utilizador clicar em “Calcular”.

No quadro “Incluir detalhe”, o utilizador pode definir o detalhe do ficheiro que pretende visualizar.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-51b8190c.png)

Os resultados de pesquisa serão apresentados no quadro do ecrã, como apresentado seguidamente. Deve o utilizador **validar** os dados do ficheiro e, para finalizar este processo, deve clicar em **“Expurgar”**.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-175d77ad.png)

Para confirmar o expurgo do ficheiro, o sistema irá enviar a seguinte mensagem:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-0dfb91ff.png)

#### 4.1.2 Expurgo de CSV

Este menu permite ao utilizador expurgar ficheiros do formato CSV.
No ecrã aberto, deve o utilizador selecionar, com a ajuda do botão de ajuda, o ficheiro que pretende expurgar.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-a26c1ba2.png)

Da lista de ficheiros integrados no sistema, o utilizador deve selecionar o pretendido e clicar em OK.
De seguida, no ecrã principal de expurgo, deve clicar em “Calcular”. Isto irá possibilitar a visualização do detalhe do ficheiro selecionado.
Após a validação do ficheiro, deve o utilizador clicar em “Expurgar” para eliminar o ficheiro e todos os documentos por ele integrados no sistema.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-d2a00ce3.png)

Para confirmar o expurgo do ficheiro, o sistema irá enviar uma mensagem semelhante à enviada aquando o Expurgo de TXT.


#### 4.1.3 Expurgo de Transferências Bancárias

Este menu permite ao utilizador expurgar ficheiros de Transferência Bancária.

Para selecionar o ficheiro a expurgar, o utilizador pode indicar os critérios de pesquisa, nomeadamente:

- Identificador do ficheiro de transferência (ID);
- Número de sequência;
- Identificador IGCP;
- Primeira data;
- Última data.


Caso o utilizador pretenda **visualizar todos os ficheiros** constantes no sistema, basta clicar em “Pesquisar ficheiros”. Desta forma, o quadro superior, ficará preenchido com todos os ficheiros de transferência bancária gerados e importados no sistema.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-63ad243a.png)

O quadro inferior do ecrã permite visualizar o detalhe do ficheiro selecionado, isto é, os documentos que estão associados ao ficheiro de transferência bancária selecionado.

Para expurgar o ficheiro, deve o utilizador clicar em "<span style="color:red">X</span>".

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-ed9a42e5.png)

Ao clicar em “Anular Transferência”, o sistema irá solicitar uma confirmação do expurgo, com uma mensagem semelhante à apresentada seguidamente:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-34ae210d.png)

Para confirmar o expurgo, basta confirmar. O sistema irá emitir uma mensagem de confirmação do expurgo.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-738b15c5.png)

Caso seja necessário **reutilizar a numeração da sequência do ficheiro abatido**, deve o utilizador ir ao menu: Parametrizações > Tabelas Genéricas > Instituições bancárias e alterar, no respetivo campo, o próximo número de sequência.
s
![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-7c7e4991.png)

### 4.2 Gestão Contabilizações Automáticas

Este menu permite ao utilizador associar as contas a crédito dos documentos, como faturas conferidas dos fornecedores, com as contas a débito dos cabimentos constantes nos ficheiros TXT, integrados no sistema através de ligações de Pessoal, Farmácia e SISO.  

>**NOTA**: Ao disponibilizar este menu, o botão “Contas a crédito” que se encontra presente nos ecrãs de ligações anteriormente mencionadas deixa de existir.


Ao selecionar este menu, irá ser aberto o seguinte ecrã na aplicação:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-2429f71d.png)

Estas associações apresentadas, podem ser editadas, abatidas ou podem também ser adicionadas novas.
Para adicionar uma relação nova, o utilizador deve clicar sobre o botão "+Novo", preencher o novo campo disponível com as contas respetivas e por fim deve confirmar a alteração carregando no botão "Confirmar". O utilizador pode consultar as contas existentes no sistema através do botão ajuda.
Esta tabela ficará guardada e poderá sempre ser editada pelo utilizador.

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-079f811f.png)

>**NOTA**: As contas a crédito devem ser sempre contas de **MOVIMENTO**.


Em caso de se pretender eliminar uma relação, o utilizador deve selecionar uma linha, clicando sobre a mesma duas vezes, e clicar no botão "-Abater".
O utilizador também pode guardar esta tabela num ficheiro CSV. Para este efeito, deve colocar, no respetivo campo, o diretório do seu computador onde pretende guardar o ficheiro. De seguida deve apenas clicar em "Ficheiro".

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-880849a7.png)

O aspeto do ficheiro a ser guardado será como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/gestao_perfis.assets/gestao_perfis-cb7ea5fb.png)
