# Ligações de outros Sistemas de Informação

Este capítulo pretende descrever o processo de importação de dados provenientes de outras aplicações, no sentido de interligar vários departamentos da entidade. As aplicações em questão permitem a gestão de dados referentes a:

- Pessoal;
- Stocks;
- Imobilizados;
- Faturação de Devedores;
- Farmácias;
- SISO/Reembolsos;
- MCDT.

A importação de dados destas aplicações, no sistema SICC /SNC - AP,  pode ser feita via ficheiros de formato TXT.
O _layout_ geral destes ficheiros, isto é, de todos os ficheiros TXT referentes a estas importações, é igual para todas as ligações disponíveis neste menu. No entanto, os campos que são preenchidos no ficheiro para importação, variam consoante o tipo de ligação e o tipo de documento que importam - que é definido pela referência do ficheiro.

Na imagem abaixo está representado um exemplo de dois ficheiros, referências 101 (Ligação Pessoal) e 211 (Ligação Gestão de Stocks), onde estão apresentados campos que são preenchidos nos dois ficheiros (por exemplo: Conta Débito) e outros que apenas são preenchidos por um deles.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-162effc4.png)

>**Nota:** Apenas pode ser produzido um ficheiro TXT por referência. </br> No ficheiro TXT, de uma dada referência, podem haver várias linhas por processo de aquisição.


 </br>Ao longo dos próximos subcapítulos será descrito, com detalhe, todo o fluxo de trabalho necessário para que a importação dos dados seja bem sucedida bem como a estrutura dos ficheiros para cada tipo de importação.

> Recomenda-se o uso da tecla **_TAB_** para a navegação pelos campos dos ecrãs do sistema. Esta forma de navegação garante que todos os campos obrigatórios sejam preenchidos e validados, permitindo o posterior desbloqueio de outros campos.


## 1. Ligações de Pessoal

Para importar dados relativos ao Pessoal, o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3f6487e6.png)

</br> No ecrã referente às importações de dados de pessoal, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-367d7da0.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro a importar e verificar se este cumpre os requisitos.
Caso ocorram erros, é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser validado novamente.

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-1279a825.png)

É possível guardar a listagem de erros de duas formas:
- Em formato CSV, disponível através da seleção do botão "Ficheiro Erros CSV", em que o utilizador deve escolher o caminho no seu computador onde pretende guardar o ficheiro.
- Em formato PDF, disponível através da seleção do botão "Ficheiro Erros PDF" que terá o seguinte aspeto:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-bc712cc6.png)

</br>Quando o ficheiro não contém erros, os elementos do ficheiro a importar ficam visíveis nas duas janelas do ecrã. Após esta validação dos elementos do ficheiro, para importar os dados nele contemplados, o utilizador deve clicar no botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-b42d6c95.png)

Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)


O utilizador pode ainda, selecionando o botão "Ligações", obter um documento PDF com os elementos carregados no sistema.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9a398c82.png)

Para a importação de dados de pessoal, podem ser importados ficheiros com as referências **101 e 102**. Os ficheiros de **referência 101** importam dados relativos a documentos do tipo **CB, CP e P2**. Os ficheiros de **referência 102** importam dados relativos a documentos do tipo **OD**. Estes ficheiros devem obedecer ao critério dos campos estipulados que estão apresentados seguidamente:

### 1.1. Referência 101

|Campo| Posição |Observações|
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

### 1.2. Referência 102
|Campo|Posição |Observações|
|:---:|:---:|:---|
|Ref.   |1 - 3 (3)  | Indicar a referência do ficheiro. Neste caso específico a referência é **102**.   |
|Entidade   |  12 - 19 (8) | A numeração das entidades, para todas as contas iniciadas por 63, deve ser iniciada por 9963 e terminada com o indicativo do mês. Por exemplo:  </br> 9963**001** - janeiro </br>9963**002** - fevereiro </br> ...</br>9963**012** - dezembro    |
|Nº OD  | 20 - 27 (8)  | A numeração dos documentos deve ser iniciada pela conta - 63 - seguindo-se do mês - 01 - e terminada com dígitos sequenciais - 001. Por exemplo: </br> 6301**001** - documento 1 do mês de janeiro </br> 6301**002** - documento 2 do mês de janeiro </br> 63**02**001 - documento 1 do mês de fevereiro.  |
|Data Doc.   |  52 - 59 (8) | Deve ser indicada a data do documento no seguinte formato: **DDMMAAAA**  |
|Conta Débito   | 60 - 109 (50)  | As contas a débito devem ser indicadas **sem pontos** e devem ser iniciadas pelo dígito **6**.   |
|Conta Crédito   | 110 - 159 (50)   | As contas a crédito devem ser indicadas **sem pontos** e devem ser iniciadas pelo dígito **2**.  |
|Importância   |160 - 177 (18)   | Deve ser indicada a importância.  |
|Sinal   |  178 (1)  | Deve ser indicado o sinal da importância (- ou +)  |
|Centro de Custo   | 179 - 188 (10)  | Deve ser indicado o centro de custo.    |


<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/101.sncap'">Descarregar TXT</button>
</div>

### 1.3. Contas a crédito

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

>**Nota:** As contas a crédito devem ser sempre contas de **MOVIMENTO**.

Em caso de se pretender eliminar uma relação, o utilizador deve selecionar uma linha, clicando sobre a mesma duas vezes, e clicar no botão "-Abater".

O utilizador também pode guardar esta tabela num ficheiro CSV. Para este efeito, deve no campo respetivo colocar o diretório do seu computador onde pretende guardar o ficheiro. De seguida deve apenas clicar em "Ficheiro".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4fb86652.png)

O aspeto do ficheiro a ser guardado será como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-18f168ee.png)


### 1.4. Processamento de Vencimentos

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


## 2. Ligações de Gestão de Stocks

A informação que deve ser enviada entre o departamento financeiro e o departamento de logística pode ser observada no seguinte esquema. Os ficheiros a serem importados no sistema, os que são referidos no esquema, são detalhadamente descritos ao longo deste capítulo.

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1ffc568a.png)

### 2.1. Referências genéricas
Para importar dados relativos às referências genéricas dos Stocks o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9cfa4d6c.png)

</br> No ecrã referente às importações de dados de gestão de stocks, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-85fc4216.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá validar o ficheiro a ser importado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos do ficheiro ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser validado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ciclo_despesa.assets/ciclo_despesa-acf32195.png)

> **Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da gestão de Stocks, é possível importar ficheiros com as referências  **201, 203, 204, 205, 206, 207, 210, 211 e 214**.

 A descrição dos campos para cada uma das referências é apresentada seguidamente.

#### 2.1.1. Referência 201
Esta referência importa dados relativos a documentos do tipo **CB** proveniente dos Stocks. Para ficheiros de referência 201 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)   | 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/201.sncap'">Descarregar TXT</button>
</div>

#### 2.1.2. Referência 203
Ficheiros de referência 203 importam dados relativos a documentos do tipo **P1**. Para ficheiros de referência 203 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| NºCP| NºP1| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|20 - 27 (8) |28 - 39 (12)|52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/203.sncap'">Descarregar TXT</button>
</div>

#### 2.1.3. Referências 204, 205, 206 e 207
Ficheiros destas referências importam dados relativos a documentos do tipo **OD**. Para ficheiros de referência 204-207 os campos que devem estar preenchidos são:

|   | Ref.    | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   | Centro Custo |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Posição (Comprimento) | 1 - 3 (3) | 52 - 59 (8) | 60 - 109 (50)  | 110 - 159 (50)  | 160 - 177 (18) | 178 (1) | 179 - 188 (10) |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/204.sncap'">Descarregar TXT</button>
</div>

#### 2.1.4. Referência 210
Ficheiros de referência 210 importam dados relativos a documentos do tipo **P2**. Para ficheiros de referência 210 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição |Ent.|NºCP|NºP2| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo| Nº dias Data Vencimento |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   |1 - 3 (3)   | 4 - 11 (8)  | 12 - 19 (8)  | 20 - 27 (8)  |40 - 51 (12)   | 52 - 59 (8)  |60 - 109 (50)   |110 - 159 (50)   |160 - 177 (18)   |178 (1)   |179 - 188 (10)   |230 - 232 (3)   |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/210.sncap'">Descarregar TXT</button>
</div>

#### 2.1.5. Referência 211
Ficheiros de referência 211 importam dados relativos a documentos do tipo **P2** provenientes de P1. Para ficheiros de referência 211 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição |Ent.|NºCP|NºP1|NºP2| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo| Nº dias Data Vencimento |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   |1 - 3 (3)   | 4 - 11 (8)  | 12 - 19 (8)  | 20 - 27 (8)  |28 - 39 (12)| 40 - 51 (12)   | 52 - 59 (8)  |60 - 109 (50)   |110 - 159 (50)   |160 - 177 (18)   |178 (1)   |179 - 188 (10)   |230 - 232 (3)   |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/211.sncap'">Descarregar TXT</button>
</div>

#### 2.1.6. Referência 214
Ficheiros de referência 214 importam dados relativos a documentos do tipo **CM**.Para ficheiros de referência 214 os campos que devem estar preenchidos são:

|   | Ref. | Nº Proc. Aquisição | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   | Nº dias Data Vencimento |Nota de encomenda|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:--:|
|Posição (Comprimento)|1 - 3 (3)|4 - 11 (8) |52 - 59(8) |60 - 109 (50)|110 - 159 (50)|160 - 177 (18)|178 (1) |230 - 232(3)   | 250 - 269(10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/214.sncap'">Descarregar TXT</button>
</div>

### 2.2. Refª 202 (Compromissos Assumidos)
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

## 3. Ligações de Gestão de Imobilizado

Para importar dados relativos aos imobilizados o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-9e5e2d6d.png)

</br> No ecrã referente às importações de dados de imobilizado, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-4534011e.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-eff4a5ac.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>Para importar ficheiros relativos ao imobilizado, devem ser importados os ficheiros de referência  **301, 302, 303, 304, 305, 306 e 307**. A descrição dos campos para cada uma das referências é apresentada seguidamente.

### 3.1. Referência 301
Ficheiros de referência 301 importam dados relativos a documentos do tipo **CB**. Para ficheiros de referência 301 os campos que devem estar preenchidos são:

|   | Ref.  | NºProc.Aquisição | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)|52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/301.sncap'">Descarregar TXT</button>
</div>

### 3.2. Referência 302
Ficheiros de referência 302 importam dados relativos a documentos do tipo **CP**. Para ficheiros de referência 302 os campos que devem estar preenchidos são:

|   | Ref.  |Ent.| NºCP |NºCM| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)|20 - 27 (8)|43 - 51 (9)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/302.sncap'">Descarregar TXT</button>
</div>

### 3.3. Referência 303
Ficheiros de referência 303 importam dados relativos a documentos do tipo **P1**. Para ficheiros de referência 303 os campos que devem estar preenchidos são:

|   | Ref.  |Ent.| NºCP |NºP1| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) | 1 - 3 (3)  |12 - 19 (8)|20 - 27 (8)|28 -  39 (12)| 52 - 59 (8)  | 60 - 109 (50)  | 110 - 159 (50)  |160 - 177 (18)   |  178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/303.sncap'">Descarregar TXT</button>
</div>

### 3.4. Referências 304, 305, 306, 307
Ficheiros destas referências importam dados relativos a documentos do tipo **OD**. Para ficheiros de referências 304 - 307 os campos que devem estar preenchidos são:

|     | Ref.    | Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   | Centro Custo |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Posição (Comprimento) | 1 - 3 (3) | 52 - 59 (8) | 60 - 109 (50)  | 110 - 159 (50)  | 160 - 177 (18) | 178 (1) | 179 - 188 (10) |

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/304.sncap'">Descarregar TXT</button>
</div>


>**NOTA:** Para importar OD relativas a **amortizações** a referência do ficheiro a importar deve ser **307**.


## 4. Ligações de Faturação

### 4.1. Ligações de Faturação de Devedores
Para importar dados relativos à faturação de devedores o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-eedb0f0e.png)

</br> No ecrã referente às importações de dados de faturas de devedores, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-2812f762.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-896bab67.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da faturação, é possível importar ficheiros de referência **401**. A descrição dos campos da referência é apresentada seguidamente. Estes ficheiros importam dados relativos a documentos do tipo FD.

#### 4.1.1. Referência 401
Para ficheiros de referência 401 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| NºP2| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| 40 - 51 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|
<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/401.sncap'">Descarregar TXT</button>
</div>

### 4.2. Ligação de Notas de Crédito a Clientes
Para importar dados relativos à faturação de devedores o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-b818652a.png)

</br> No ecrã referente às importações de dados de faturas de devedores, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-5988d28e.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da faturação, é possível importar ficheiros de referência **905** que importam documentos do tipo **CC**. A descrição dos campos da referência é apresentada seguidamente:

|   | Ref.  | Ent.| Nº CC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) | 1 - 3 (3)|12 - 19 (8)|28 - 39 (12)| 52 - 59 (8)|60 - 109 (50)|110 - 159 (50)|160 - 177 (18)|178 (1) |179 - 188 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/905.sncap'">Descarregar TXT</button>
</div>

## 5. Ligações de Farmácias

Para importar dados relativos às Farmácias o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-0629654e.png)

</br> No ecrã referente às importações de dados de farmácias, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-a508277b.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.
</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-a611c017.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso de farmácias, é possível importar ficheiros com as referências  **702, 703, 704 e 706**.
A descrição dos campos para cada uma das referências é apresentada seguidamente.

>**Nota:** Alguns ficheiros variam a sua estrutura para entidades do tipo ARS e ULS. A descrição dos campos destes ficheiros é apresentada separadamente para cada referência.


### 5.1. Referência 702
Ficheiros de referência 702 importam dados relativos a documentos do tipo **P2**. Para ficheiros de referência 702 os campos que devem estar preenchidos são:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 -  128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/702.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento) |1 - 3 (3)|4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 82 (20)  | 83 - 102 (20)  |103 - 120 (18)   |  121 (1) |122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/702_ars.sncap'">Descarregar TXT</button>
</div>

### 5.2. Referência 703
Ficheiros de referência 703 importam dados relativos a documentos do tipo **OD**. Para ficheiros de referência 703 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| NºOD| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| 40 - 51 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/703.sncap'">Descarregar TXT</button>
</div>

### 5.3. Referência 704
Ficheiros de referência 704 importam dados relativos a documentos do tipo **NC**. Para ficheiros de referência 704 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.| Nº NC/Série| Data Doc. | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| 28 - 39 (12)| 52 - 59 (8)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/704.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | Ent.| Nº NC/Série| Data Doc. | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |12 - 19 (8)| **28 - 42 (15)**| 55 - 62 (8)  | 83 - 102 (20)  |103 - 120 (18)   |  121 (1) |122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/704_ars.sncap'">Descarregar TXT</button>
</div>

### 5.4. Referência 706
Ficheiros de referência 706 importam dados relativos a documentos do tipo **DF**. Para ficheiros de referência 706 os campos que devem estar preenchidos são:

|   | Ref.  | NºProc.Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/706.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 82 (20)  | 83 - 102 (20)  |103 - 120 (18)   |  121 (1) |122 - 131 (10)|

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

## 6. Ligações do SISO/Reembolsos

### 6.1. Ligações de faturas
Para importar dados relativos às faturas de SISO/Reembolsos o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets//mu_snc_ap-585d2317.png)

</br> No ecrã referente às importações de dados de SISO/Reembolsos, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-cecb77a8.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.

</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-b87b6060.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da ligação SISO/Reembolsos, é possível importar ficheiros de referência  **501**. A descrição dos campos da referência é apresentada seguidamente. Ficheiros desta referência importam dado relativos a documentos do tipo **P2**.

</br>**Referência 501**

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº P1/P2| Data Doc. | Conta Débito | Conta Crédito | Importância| Sinal| Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|40 - 51 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/501.sncap'">Descarregar TXT</button>
</div>

### 6.2. Exportação de Pagamentos
Para exportar pagamentos o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f629ba94.png)
_Em atualização_

### 6.3. Importação de Entidades
Para importar dados relativos às entidades de SISO/Reembolsos o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-c3ae6905.png)
_Em atualização_

## 7. Ligações dos MCDT

Para importar dados relativos a MCDT o utilizador deve seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4637c493.png)

</br> No ecrã referente às importações de dados de MCDT, o utilizador deve:

1. Selecionar do diretório o ficheiro TXT a ser importado;
2. Indicar a chave orçamental que será associada a todos os documentos carregados;
3. Selecionar o botão "Ver/Testar Ficheiro".

![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-70b5f387.png)

</br> Ao selecionar o botão "Ver/Testar Ficheiro" o sistema irá percorrer o ficheiro carregado e verificar se este cumpre os requisitos. Quando o ficheiro não contém erros, os elementos ficam visíveis no ecrã. No caso do ficheiro conter erros é dada uma mensagem ao utilizador e é produzido um relatório numa caixa criada para o efeito. Nestes casos, os erros devem ser corrigidos e o ficheiro deve ser testado novamente.

</br>Após validação dos elementos do ficheiro o utilizador deve selecionar o botão "Importar Ligação".
![](https://spmssicc.github.io/pages/markdown/ligacoes_si.assets/ligacoes_si-55fe2f0b.png)

>**Nota:** A funcionalidade dos botões disponíveis neste ecrã é igual aos descritos em 3.1.1.

</br>Para confirmar a importação dos dados, o sistema gera uma mensagem informativa com a indicação abaixo descrita.
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1150b5aa.png)

</br>No caso da gestão de imobilizado, é possível importar ficheiros com as referências  **902, 903, 904, 905, 906 e 908**. A descrição dos campos para cada uma das referências é apresentada seguidamente.

>**Nota:** Alguns ficheiros variam a sua estrutura para entidades do tipo ARS e ULS. A descrição dos campos destes ficheiros é apresentada separadamente para cada referência.


### 7.1. Referência 902
Ficheiros de referência 902 importam dados relativos a documentos do tipo **P2**. Para ficheiros de referência 902 os campos que devem estar preenchidos são:

Caso Geral:

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/902.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br> Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | NºProc. Aquisição| Ent.| NºCP|Nº P1/P2/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 82 (20)  | 83 - 102 (20)  |103 - 120 (18)   |  121 (1) |122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/902_ars.sncap'">Descarregar TXT</button>
</div>

### 7.2. Referência 903
Ficheiros de referência 903 importam dados relativos a documentos do tipo **OD**. Para ficheiros de referência 903 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.|NºOD| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|40 - 51 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/903.sncap'">Descarregar TXT</button>
</div>

### 7.3. Referência 904
Ficheiros de referência 904 importam dados relativos a documentos do tipo **NC**. Para ficheiros de referência 904 os campos que devem estar preenchidos são:

|   | Ref.  | Entidade|Nº NC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)|12 - 19 (8)|28 - 39 (12)| 52 - 59 (8)|60 - 79 (20)| 80 - 99 (20)  |100 - 117 (18)| 118 (1)|119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/904.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | Ent.|Nº NC/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)|12 - 19 (8)|**28 - 42 (15)**| 55 - 62 (8)|63 - 82 (20)| 83 - 102 (20)  |103 - 120 (18)| 121 (1)|122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/904_ars.sncap'">Descarregar TXT</button>
</div>


### 7.4. Referência 905
Ficheiros de referência 905 importam dados relativos a documentos do tipo **CC**. Para ficheiros de referência 905 os campos que devem estar preenchidos são:

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
|Posição (Comprimento) | 1 - 3 (3)|12 - 19 (8)|**28 - 42 (15)**| 55 - 62 (8)|63 - 82 (20)|83 - 102 (20)|103 - 120 (18)|121 (1) |122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/905_ars.sncap'">Descarregar TXT</button>
</div>

### 7.5. Referência 906
Ficheiros de referência 906 importam dados relativos a documentos do tipo **DF**. Para ficheiros de referência 906 os campos que devem estar preenchidos são:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/906.sncap'">Descarregar TXT</button>
</div>

</br>**ARS e ULS**
</br> Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  |NºProc. Aquisição| Ent.| NºCP|Nº DF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  |4 - 11 (8)| 12 - 19 (8)|20 - 27 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 82 (20)  | 83 - 102 (20)  |103 - 120 (18)   |  121 (1) |122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/906_ars.sncap'">Descarregar TXT</button>
</div>

### 7.6. Referência 908
Ficheiros de referência 908 importam dados relativos a documentos do tipo **CF**. Para ficheiros de referência 908 os campos que devem estar preenchidos são:

|   | Ref.  | Ent.|Nº CF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|28 - 39 (12)| 52 - 59 (8)  | 60 - 79 (20)  | 80 - 99 (20)  |100 - 117 (18)   |  118 (1) |119 - 128 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/908.sncap'">Descarregar TXT</button>
</div>

</br> **ARS e ULS**
</br>Para entidades do tipo ARS e ULS, ficheiros desta referência devem ter os seguintes campos preenchidos:

|   | Ref.  | Ent.|Nº CF/Série| Data Doc. | Conta Débito | Conta Crédito | Importância  | Sinal   |Centro Custo|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Posição (Comprimento)   | 1 - 3 (3)  | 12 - 19 (8)|**28 - 42 (15)**| 55 - 62 (8)  | 63 - 82 (20)  | 83 - 102 (20)  |103 - 120 (18)   |  121 (1) |122 - 131 (10)|

<div style="height:40px">
<button id=descarregar type="button" onclick="location.href='https://spmssicc.github.io/pages/markdown/docs_txt/908_ars.sncap'">Descarregar TXT</button>
</div>
