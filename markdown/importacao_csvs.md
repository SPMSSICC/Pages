# IMPORTAÇÃO DE CSVs

## 1. Introdução

Este capítulo pretende demonstrar as novas funcionalidades da aplicação SICC, bem como especificar a funcionalidade do botão “importar” por vários submenus do sistema, demonstrando ao utilizador o seu modo de utilização. O procedimento de importação é exatamente igual em todos os processos, sendo que o resultado esperado difere com os tipos de documentos criados.

Cada capítulo irá abordar uma funcionalidade em particular demonstrando ao utilizador o fluxo de trabalho necessário para completar uma determinada tarefa de importação de ficheiros CSV. Desta forma, o documento está estruturado da seguinte forma:

-   PO: Propostas Orçamentais;
-   CB e CM - Cabimentos e Compromissos;
-   CP - Comprometidos;
-   P1 e P2 - Processado em conferência e Processado conferido;
-   AM, AB e AL - Alterações;
-   CE - Credores p/ execução Orçamental;
-   AP - Autorização de Pagamento;
-   PG - Pagamento;
-   OD - Operações Diversas.

## 2. Âmbito

Este manual descreve a forma de importação de ficheiros CSV. em várias telas do Sistema SICC, bem como demonstra as respetivas posições nas ligações para esta extensão de ficheiro, aplicadas a cada submenu concretamente. O documento será revisto e atualizado à medida que novas funcionalidades sejam adicionadas à aplicação ou caso as funcionalidades existentes sejam alteradas e essa alteração implique a atualização do manual. O procedimento é efetuado nas mesmas telas onde se fazem registos manuais, no entanto com a nova ferramenta de “importar”.

## 3. PO

Ao utilizador que fica responsável pelas importações dos ficheiros CSV. tem de obedecer ao instituído nas posições das ligações (*Layout’s*).
No caso deste primeiro capítulo, vamos assim demonstrar as etapas que o utilizador terá de percorrer até à conclusão da importação.
Para importar dados de um arquivo de texto usando o Microsoft Office Excel: O utilizador pode abrir o arquivo de texto no Excel ou importar o arquivo de texto como um intervalo de dados externos.
Os formatos de arquivo de texto usados com frequência:
Arquivos de texto com valores separados por vírgulas (.CSV), nos quais o caracter vírgula (,) geralmente separa cada campo de texto.

![imagem3](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image3.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PO_POCMS.csv'">Descarregar CSV</button>
</div>

Findo o preenchimento do respetivo ficheiro de integração, o utilizador deve guardar o caminho do documento com a respetiva extensão anteriormente referida.
![imagem4](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image4.png)

Menu:

![imagem5](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image5.png)

Submenu:

![imagem6](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image6.png)


No submenu acima referido, é onde o utilizador tem de fazer a importação do ficheiro, pressionando para o efeito o botão![botão_importar](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/botão_importar.png).

Nova tela surge, sendo que o utilizador tem de escolher o caminho para chegar ao ficheiro criado nos passos anteriores.

![imagem7](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image7.png)

O utilizador para verificar a integração do ficheiro, terá para o efeito de pressionar “ver/testar Ficheiro”. Ao carregar, o ficheiro CSV. corre em background podendo dar um de dois resultados:

Erro no ficheiro:

![imagem8](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image8.png)

Caso esta situação aconteça, o Responsável pela integração tem de verificar a natureza do erro, corrigir, gravar e proceder de novo ao teste do ficheiro. As mensagens de erro aparecem sempre que se verifique uma incompatibilidade entre a estrutura do ficheiro com as validações do SICC.

Após correção desses mesmos erros, o resultado esperado é:

***Ficheiro Testado e pronto para importação:***

![imagem9](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image9.png)

**Nota:**
Aquando da criação do Orçamento Ordinário, o utilizador tem a possibilidade de ver os valores importados e respetivos aos totais das Receitas e Despesas.

Se o ficheiro apresentar o aspeto acima demonstrado, quer dizer que não foram detetados problemas entre a estrutura do ficheiro, sendo que nesta etapa o utilizador pode fazer a importação, pressionando para o efeito o botão ![botão_importa_ligação](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/botão_importa_ligação.png).

Uma nova mensagem surge e o ficheiro integrado, dando-se assim como encerrado o carregamento.

![imagem10](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image10.png)

## 4. CB e CM

Conforme mencionado no capítulo anterior, os vários lançamentos no sistema SICC, obedecem a uma determinada estrutura, a qual tem de ser respeitada para a integração dos mesmos ficheiros. Neste segundo capítulo é demonstrada assim a estrutura para os Cabimentos e para os Compromissos.

Cabimentos:

![imagem11](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image11.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CB_POCMS.csv'">Descarregar CSV</button>
</div>

Compromissos:

![imagem12](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image12.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CM_POCMS.csv'">Descarregar CSV</button>
</div>

Menu:

![imagem13](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image13.png)

Submenu:

![imagem14](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image14.png)

**Nota:**
Escolher o separador do Cabimento (CB) ou do Compromisso (CM), sendo que ambos têm a possibilidade de Importação

Como explicado anteriormente, as telas de importação funcionam de igual forma em todos os ecrãs, sendo que podem acontecer duas situações:
-   Erro no ficheiro;
-   Ficheiro testado e pronto para importação;

![imagem15](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image15.png)

**Nota:**
O Processo de importação é em todo igual ao explicado no capítulo anterior. Realçando no entanto que qualquer erro que aconteça durante o processo terá de ser revisto, salvo e sujeito a novo teste de verificação de documento. Enquanto existirem mensagens de erro não resolvidas o sistema não completa a importação.

## 5. CP

![imagem16](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image16.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CP_POCMS.csv'">Descarregar CSV</button>
</div>

Menu:
![imagem17](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image17.png)

Submenu:
![imagem18](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image18.png)

![imagem19](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image19.png)


**Nota:**
O Processo de importação é em todo igual ao explicado no capítulo anterior. Realçando no entanto que qualquer erro que aconteça durante o processo terá de ser revisto, salvo e sujeito a novo teste de verificação de documento. Enquanto existirem mensagens de erro não resolvidas o sistema não completa a importação.

## 6. P1 e P2

Neste capítulo pretende-se demonstrar a criação dos ficheiros de importação relativos ao P1 e P2. Desta forma, abaixo demonstrado, encontram-se as estruturas dos ficheiros CSV. com as respetivas obrigatoriedades de preenchimento assinaladas a Bold/Negrito.

**P1**
![imagem20](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image20.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P1_POCMS.csv'">Descarregar CSV</button>
</div>

**P2**
![imagem21](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image21.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/P2_POCMS.csv'">Descarregar CSV</button>
</div>

Para integração dos ficheiros criados no passo anterior, deve o utilizador usar o seguinte caminho:

Menu:
![imagem22](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image22.png)

Abaixo, encontram-se as telas relativas à importação dos ficheiros CSV. Conforme mencionado anteriormente, os procedimentos de importação são idênticos em todos os tipos de documento, pelo que a nível de efeitos de manual, são somente demonstradas as telas que o utilizador tem de usar.
Submenu:

**P1**
![imagem23](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image23.png)

**P2**
![imagem24](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image24.png)

Para efeitos de manual, é demonstrada a tela de importação do P2, onde o utilizador faz a importação do ficheiro CSV. As recomendações e notas evidenciadas anteriormente servem de igual forma para este capítulo.

![imagem25](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image25.png)

## 7. AM, AB e AL

De forma abrangente, neste capítulo pretende-se demonstrar as telas das posições nas ligações CSV. para as possíveis alterações a serem realizadas no sistema SICC.

-   Alterações de CB (AM);
-   Alterações de CM (AB);
-   Alterações de CP (AL).

Os menus para estas alterações encontram-se no seguinte caminho:

![imagem26](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image26.png)

Os ficheiros de integração são os seguintes:

**AM**

![imagem27](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image27.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AM_POCMS.csv'">Descarregar CSV</button>
</div>

**AB**

![imagem28](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image28.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AB_POCMS.csv'">Descarregar CSV</button>
</div>

**AL**

![imagem29](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image29.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AL_POCMS.csv'">Descarregar CSV</button>
</div>

**Nota:**
O Processo de importação é em todo igual ao explicado no capítulo anterior. Realçando no entanto que qualquer erro que aconteça durante o processo terá de ser revisto, salvo e sujeito a novo teste de verificação de documento. Enquanto existirem mensagens de erro não resolvidas o sistema não completa a importação.

## 8. CE

De igual forma aos capítulos anteriores, o procedimento de importação é idêntico, no entanto e na elaboração do ficheiro CSV. No entanto e neste caso específico, constatamos que para o carregamento do CE (conforme imagem abaixo), o ficheiro pode conter vários tipos de documentos gerados em passos anteriores e que entrarão todos em conjunto na integração (ao contrário da individualidade de tipos de documentos demonstrados anteriormente).

![imagem30](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image30.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/CE_POCMS.csv'">Descarregar CSV</button>
</div>

Menu:

![imagem31](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image31.png)

Submenu:

![imagem32](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image32.png)

Nova tela surge, sendo que o utilizador tem de escolher o caminho para chegar ao ficheiro criado com extensão CSV.

![imagem33](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image33.png)

O utilizador para verificar a integração do ficheiro, terá para o efeito de pressionar “ver/testar Ficheiro”. Igualmente ao explicado anteriormente, ao carregar, o ficheiro CSV., o mesmo corre em background podendo dar um de dois resultados:

Erro no ficheiro:

![imagem34](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image34.png)

Caso esta situação aconteça, o Responsável pela integração tem de verificar a natureza do erro, corrigir, gravar e proceder de novo ao teste do ficheiro. As mensagens de erro aparecem sempre que se verifique uma incompatibilidade entre a estrutura do ficheiro com as validações do SICC.
O segundo resultado é:

Ficheiro Testado e pronto para importação:

![imagem35](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image35.png)

Se o ficheiro apresentar o aspeto acima demonstrado, quer dizer que não foram detetados problemas entre a estrutura do ficheiro, sendo que nesta etapa o utilizador pode fazer a importação, pressionando para o efeito o botão![botão_importa_ligação](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/botão_importa_ligação.png).

![imagem36](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image36.png)

Uma nova mensagem surge e o ficheiro integrado, dando-se assim como encerrado o carregamento dos CE's.

## 9. AP

Neste capítulo e de igual maneira ao procedimento de importação do CE (conforme imagem abaixo), o ficheiro pode conter vários tipos de documentos gerados no passo anterior (CE), sendo que neste caso em concreto e para realização da AP, necessitamos de dados como a conta bancária e o IBAN. A atribuição do Nº da AP é também definida pelo utilizador.

![imagem37](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image37.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/AP_POCMS.csv'">Descarregar CSV</button>
</div>

**Nota:**
A categoria de motivo é de preenchimento obrigatório quando existam contas bancárias e IBAN associados. Desta forma, a numeração da categoria deve ser preenchida pelo utilizador, conforme a tabela abaixo demonstrada:

![imagem38](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image38.png)

Menu:

![imagem39](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image39.png)

Submenu:

![imagem40](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image40.png)

Procedimento igual aos efetuados anteriormente, em que o utilizador escolhe o ficheiro CSV no diretório de origem.

![imagem41](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image41.png)

De igual forma, o carregamento na fase de testar o ficheiro pode apresentar erros, pelo que a responsabilidade de quem cria é a de corrigir, salvar e carregar novamente.
Neste caso, e visto que anteriormente já foram demonstrados *Logs* de erros, demonstramos somente o resultado do carregamento.

**Ficheiro Testado e pronto para importação:**
![imagem42](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image42.png)


Se o ficheiro apresentar o aspeto acima demonstrado, quer dizer que não foram detetados problemas entre a estrutura do ficheiro, sendo que nesta etapa o utilizador pode fazer a importação, pressionando para o efeito o botão! [botão_importa_ligação](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/botão_importa_ligação.png).

![imagem43](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image43.png)

Uma nova mensagem surge e o ficheiro integrado, dando-se assim como encerrado o carregamento das AP’s.

## 10. PG

Este é o último capítulo referente ao processo da despesa, pelo que a ultima fase é a correspondente ao Pagamento. Desta forma, depois de escolhidas as entidades na AP, neste processo efetiva-se o pagamento. Para o efeito, novo ficheiro CSV. é criado com a estrutura abaixo demonstrada.

![imagem44](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image44.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/PG_POCMS.csv'">Descarregar CSV</button>
</div>

Menu:

![imagem45](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image45.png)

Submenu:

![imagem46](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image46.png)

O procedimento é semelhante aos efetuados anteriormente, em que o utilizador escolhe o ficheiro CSV no diretório de origem.

![imagem47](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image47.png)

O carregamento na fase de testar o ficheiro pode apresentar erros, pelo que a responsabilidade de quem cria é a de corrigir, salvar e carregar novamente.

Caso o ficheiro no teste/ver ficheiro não produza erros, o resultado é o abaixo demonstrado:

![imagem48](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image48.png)

Nova mensagem é despoletada pelo Sistema, dando-se assim como findo o carregamento. Poderá o utilizador constatar a sua integração através de uma consulta.

![imagem49](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image49.png)

## 11. OD

A importação das operações diversas (OD), em nada difere dos procedimentos de importação demonstrados anteriormente.
Desta forma, o utilizador terá somente de proceder ao preenchimento não esquecendo que para uma conta 6*, 7* ou 3* é obrigatória a atribuição de um centro de custo.

![imagem50](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image50.png)

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_excel/OD_POCMS.csv'">Descarregar CSV</button>
</div>

Menu:

![imagem51](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image51.png)

Submenu:

![imagem52](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image52.png)

De acordo com o que tem vindo a ser demonstrado o utilizador terá de escolher o caminho onde tem o ficheiro CSV. para importação.

![imagem53](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image53.png)

Para verificar se a informação do ficheiro está correta, deve o utilizador ver/testar o ficheiro para validar. Caso existam mensagens de erro, as mesmas serão despoletadas na tela de log. de erros no canto inferior direito.

![imagem54](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image54.png)

A mensagem de importação concluída surgirá no sistema, sendo que para o efeito, o utilizador tem a possibilidade de proceder á consulta dos registos que acabou de importar.

![imagem55](https://spmssicc.github.io/pages/markdown/importacao_csvs.assets/image55.png)
