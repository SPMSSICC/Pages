<div class="cabecalho"><img src="https://spmssicc.github.io/pages/img/logos/SPMS2016B_272x105.png">

Checklist SNC-AP: <span style="font-size:.9em">Tarefas a executar</span></div>

No sentido de facilitar os processos internos de cada instituição e no âmbito da parametrização e organização do novo sistema informático centralizado em SNC-AP, são descritas as seguintes tarefas a realizar por ordem sequencial.

![](https://spmssicc.github.io/pages/markdown/check_list_mig.assets/check_list_mig-98480d72.png)

<div style="padding-top:20px">
<label class="container"> 1. Garantir os requisitos informáticos <input type="checkbox"> <span class="checkmark"></span></label>
</div>

<div style="padding-left:40px"> Para utilização do sistema, cada posto de trabalho necessita de:
</br></br>
- Ligação à RIS (Rede Informática da Saúde);</br>
- Java 32 ou 64 bit, versão 7 ou versão 8 até ao update 121 (inclusivé);</br>
- Internet Explorer até à versão 11 com Java ativado;</br>
- Adicionar o endereço http://10.20.1.172 às exceções do Java, através do menu Security > Edit SiteList
</div>

<div style="padding-top:20px">
<label class="container"> 2. Envio da informação a ser integrada no SICC SNC-AP <input type="checkbox"> <span class="checkmark"></span></label>
</div>

<div style="padding-left:40px"> Devem as entidades preencher os seguintes ficheiros com os dados a migrar para o SICC SNC-AP.
</div>

|Informação| Manual > Migração de dados p/SICC SNC-AP | Descarregar Ficheiro |
|:--|:--|:--|
|**Entidades** | Consultar <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=61-entidades' target='_blank'>Capítulo 6.1 Entidades</a>| <a href='https://spmssicc.github.io/pages/markdown/docs_excel/ENTIDADE.csv'>Ficheiro</a> |
|**Tipos de Entidades**   |Consultar <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=62-tipos-de-entidades' target='_blank'> Capítulo 6.2 Tipos de Entidades </br> </a>  | <a href='https://spmssicc.github.io/pages/markdown/docs_excel/TTIPOENT.csv'>Ficheiro </a>  |
|**Fatores de Aglutinação**   |Consultar <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=63-factores-de-aglutina%C3%A7%C3%A3o' target='_blank'> Capítulo 6.3 Fatores de Aglutinação</a>    | <a href='https://spmssicc.github.io/pages/markdown/docs_excel/TFACAGLU.csv'> Ficheiro </a>   |
|**Plano de Contas**   | Consultar <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=64-plano-de-contas' target='_blank'>Capítulo 6.4 Plano de Contas</a>  |<a href='https://spmssicc.github.io/pages/markdown/docs_excel/PCONTAS.csv'>Ficheiro </a>   |
|**Centros de Custo**   | Consultar <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=65-centros-de-custos' target='_blank'>Capítulo 6.5 Centros de Custos</a>  |<a href='https://spmssicc.github.io/pages/markdown/docs_excel/CCUSTOS.csv'> Ficheiro </a>   |
|**Classificadores Económicos**   |Consultar <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=69-contabilidade-p%C3%BAblica' target='_blank'>Capítulo 6.9 Contabilidade Pública</a>  |<a href='https://spmssicc.github.io/pages/markdown/docs_excel/CPUBLICA.csv'> Ficheiro</a>   |


>**NOTA:** Solicita-se que seja dada a devida atenção aos **formatos e nomes dos ficheiros** aquando a gravação dos mesmos. As características dos ficheiros podem ser consultadas no Capítulo 6 - Estrutura da informação a carregar, em Migração de dados p/SICC SNC-AP, do menu SNC-AP disponível também <a href='https://spmssicc.github.io/pages/?doc=cer_migracao_sicc&anchor=6-estrutura-da-informa%C3%A7%C3%A3o-a-carregar' target='_blank'> aqui </a>_


<div style="padding-top:20px">
<label class="container"> 3. Inserção/Alteração dos Dados relativos à Instituição <input type="checkbox"> <span class="checkmark"></span></label>
</div>

<div style="padding-left:40px">Devem as entidades verificar/alterar os dados relativos à instituição.
</br>Esta parametrização pode ser visualizada neste menu:</div>

![](https://spmssicc.github.io/pages/markdown/check_list.assets/check_list-8a443183.png)


<div style="padding-top:20px">
<label class="container"> 4. Verificar dados de Entidades <input type="checkbox"> <span class="checkmark"></span></label>
</div>
<div style="padding-left:40px">
Após a migração da informação dos Clientes e Fornecedores - Entidades, Tipos de Entidades e Fatores de Aglutinação, devem as instituições validar a informação carregada.

</br></br>Para verificar as <b>entidades</b> carregadas, deve ser seguido o seguinte caminho:</div>

![](https://spmssicc.github.io/pages/markdown/check_list_mig.assets/check_list_mig-cc066e43.png)

<div style="padding-left:40px"> Caso seja necessário efetuar alguma alteração à informação carregada, ou seja necessário adicionar/remover alguma entidade deve ser aplicado o procedimento descrito no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=41-gest%C3%A3o-de-entidades' target='_blank'>Capítulo 4.1.</a>_ da secção Parametrização do Manual de Utilizador SICC SNC-AP.

</br></br>Para verificar os <b>tipos de entidades</b> carregados, deve ser seguido o seguinte caminho:</div>

![](https://spmssicc.github.io/pages/markdown/check_list_mig.assets/check_list_mig-5dbab324.png)

<div style="padding-left:40px"> Caso seja necessário efetuar alguma alteração à informação carregada deve ser aplicado o procedimento descrito no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=24-tipos-de-entidade' target='_blank'>Capítulo 2.4.</a>_ da secção Parametrização do Manual de Utilizador SICC SNC-AP.

</br></br>Para verificar os <b>fatores de aglutinação</b> carregados, deve ser seguido o seguinte caminho:</div>

![](https://spmssicc.github.io/pages/markdown/check_list_mig.assets/check_list_mig-ba8fcd80.png)

<div style="padding-left:40px"> Caso seja necessário efetuar alguma alteração à informação carregada deve ser aplicado o procedimento descrito no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=23-factores-de-aglutina%C3%A7%C3%A3o' target='_blank'>Capítulo 2.3.</a>_ da secção Parametrização do Manual de Utilizador SICC SNC-AP.</div>


<div style="padding-top:20px">
<label class="container"> 5. Verificar o Plano de Contas <input type="checkbox"> <span class="checkmark"></span></label>
</div>
<div style="padding-left:40px">
Após a migração do Plano de Contas, devem as entidades verificá-lo, no sentido de avaliar a sua coerência.

</br>Para verificar o plano de contas, deve ser seguido o seguinte caminho:</div>

![](https://spmssicc.github.io/pages/markdown/check_list.assets/check_list-5bfbffc6.png)

<div style="padding-left:40px">O Plano de Contas poderá ser exportado para ficheiro CSV, para uma melhor análise.</div>
![](https://spmssicc.github.io/pages/markdown/check_list.assets/check_list-a887560b.png)

<div style="padding-left:40px">O aspeto do ficheiro CSV exportado é o seguinte:</div>
![](https://spmssicc.github.io/pages/markdown/check_list.assets/check_list-bbb92825.png)

<div style="padding-left:40px"><span style="font-weight:bold">Desdobramento de Contas</span>

 </br>Após a verificação do Plano de Contas, pode ser necessário efetuar o desdobramento de contas. A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=desdobramento-de-contas' target='_blank'>Capítulo 3.1.1.</a>_ da secção Parametrização do Manual de Utilizador SNC-AP.
</div>

<div style="padding-top:20px">
<label class="container">6. Verificar os Centros de Custos<input type="checkbox"> <span class="checkmark"></span></label></div>

<div style="padding-left:40px"> Após a migração do ficheiro correspondente aos centros de custos da instituição, deve a entidade verificar se estes estão de acordo com o pretendido. Caso seja necessário efetuar alguma alteração, este processo deve ser efetuado no seguinte menu: </div>

![](https://spmssicc.github.io/pages/markdown/check_list_mig.assets/check_list_mig-c5f281a6.png)

<div style="padding-left:40px">A descrição do processo de alteração aos centros de custos pode ser consultada no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=322-centros-de-custo' target='_blank'>Capítulo 3.2.2.</a>_ da secção Parametrização do Manual de Utilizador SNC-AP.</div>

<div style="padding-top:20px">
<label class="container">7. Verificar os Classificadores Económicos<input type="checkbox"> <span class="checkmark"></span></label></div>

<div style="padding-left:40px"> Após a migração do ficheiro correspondente aos classificadores económicos da instituição, deve a entidade verificar se estes estão de acordo com o pretendido. Caso seja necessário efetuar alguma alteração, este processo deve ser efetuado no seguinte menu: </div>

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-18ba7857.png)


>**NOTA:** Todas os classificadores económicos criados ou alterados devem ser associados às respetivas contas no menu de plano de contas.  

<div style="padding-left:40px"> A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=312-classificadores-econ%C3%B3micos' target='_blank'>Capítulo 3.1.2.</a>_ da secção Parametrização do Manual de Utilizador SNC-AP. </div>

<div style="padding-top:20px">
<label class="container">8. Parametrizar a Chave Orçamental<input type="checkbox"> <span class="checkmark"></span></label></div>

<div style="padding-left:40px">A Chave Orçamental mais utilizada no orçamento da entidade deve ser parametrizada.
</br>Para aceder ao ecrã de parametrização deve ser seguido o seguinte caminho:</div>

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-5a565b7c.png)

<div style="padding-left:40px">A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=12-exerc%C3%ADcios' target='_blank'>Capítulo 1.2.</a>_ da secção Parametrização do Manual de Utilizador SNC-AP.

Como a chave orçamental é composta por vários elementos, deve verificar cada um deles nestes menus:</div>

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-508ed546.png)

<div style="padding-left:40px">A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=313-chave-or%C3%A7amental' target='_blank'>Capítulo 3.1.3.</a>_ da secção Parametrização do Manual de Utilizador SNC-AP. </div>

<div style="padding-top:20px">
<label class="container">9. Parametrização de Contas à Ordem das Instituições Bancárias<input type="checkbox"> <span class="checkmark"></span></label></div>

<div style="padding-left:40px">As instituições bancárias devem ter as contas parametrizadas.
</br>Para aceder ao ecrã de parametrização deve ser seguido o seguinte caminho:</div>

![](https://spmssicc.github.io/pages/markdown/check_list.assets/check_list-eb8ddf91.png)

![](https://spmssicc.github.io/pages/markdown/check_list.assets/check_list-81d9caca.png)

<div style="padding-left:40px">A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=parametrizacao&anchor=25-institui%C3%A7%C3%B5es-banc%C3%A1rias' target='_blank'>Capítulo 2.5.</a>_ da secção Parametrização do Manual de Utilizador SNC-AP. </div>

<div style="padding-top:20px">
<label class="container">10. Introduzir, no sistema, o Orçamento Anual<input type="checkbox"> <span class="checkmark"></span></label></div>

<div style="padding-left:40px">Após ter parametrizado o sistema, deve a entidade, registar o orçamento anual no seguinte menu:</div>

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-8570877f.png)

>**NOTA:** Este registo também poderá ser efetuado através da importação de ficheiro CSV de acordo com o manual.  

<div style="padding-left:40px"> A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=orcamento&anchor=11-recolha-de-propostas-or%C3%A7amentais' target='_blank'>Capítulo 1.1.</a>_ da secção Orçamental do Manual de Utilizador SNC-AP. </div>

<div style="padding-top:20px">
<label class="container">11. Introduzir, no sistema, o Orçamento dos Fundos Disponíveis LCPA<input type="checkbox"> <span class="checkmark"></span></label></div>

<div style="padding-left:40px">Após ter sido introduzido o orçamento anual, deve agora ser registado o orçamento LCPA no seguinte menu:</div>

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-4582f3fc.png)

<div style="padding-left:40px"> A descrição deste processo poderá ser consultada no <a href='https://spmssicc.github.io/pages/?doc=orcamento&anchor=2-fundos-dispon%C3%ADveis-lpca' target='_blank'>Capítulo 2.</a>_ da secção Orçamental do Manual de Utilizador SNC-AP. </div>


<!-- <div style="padding-top:20px">
<label class="container">9. Assegurar as Ligações a outros Sistemas de Informação<input type="checkbox"> <span class="checkmark"></span></label></div>
<div style="padding-left:40px">As entidades devem assegurar que os outros Sistemas de Informação contemplem as contas do novo normativo contabilístico SNC-AP.

Informamos ainda que o sistema RHV está a ser atualizado pela SPMS com as definições enviadas pela ACSS.

<div class="description"> Todas as ligações são efetuadas pelos layouts descritos no <a href='https://spmssicc.github.io/pages/?doc=ciclo_despesa&anchor=13-liga%C3%A7%C3%B5es-de-outras-aplica%C3%A7%C3%B5es' target='_bblank'>Capítulo 13.</a>_ da secção Ciclo de Despesa do Manual de Utilizador SNC-AP.</div> -->

##### Efetuar Registos

Após terem sido terminadas as tarefas descritas, a entidade passa a estar pronta para iniciar os registos contabilísticos em SNC-AP.

 A descrição deste processo poderá ser consultada nas secções <a href='https://spmssicc.github.io/pages/?doc=ciclo_despesa&anchor=ciclo-de-despesa' target='_blank'>Ciclo de Despesa</a>_ e <a href='https://spmssicc.github.io/pages/?doc=ciclo_receita' target='_blank'>Ciclo de Receita</a>_ do Manual de Utilizador SNC-AP.


<div style="background-color:#29615D; padding:10px; margin-top:30px; width:100%;border:5px">

<span style="font-weight:bold; text-align:center;color:white">NOTAS adicionais</span></div>

</br>Com a implementação do SNC-AP foram efetuadas algumas alterações ao sistema nomeadamente:

</br><span style="color:#29615D; font-weight:bold">1.Os registos efetuados no menu de operações diversas (OD) respeitam unicamente os lançamentos contabilísticos de fluxos económicos.</span>

</br><span style="color:#29615D; font-weight:bold">2.As designadas rubricas financeiras foram alteradas para os códigos iniciados por 99. Dessa forma os registos contabilisticos relacionados com caixa devem ser efetuados na conta especifica 111 CAIXA (e não nas rubricas financeiras).</span>
