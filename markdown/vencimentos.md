# Processamento de Vencimentos

Relativamente ao processamento dos vencimentos em SNC-AP, e como principais alterações ao normativo contabilístico anterior (POCMS), deverá ser tido em atenção o que diz a CNC através das FAQ’s n.º 1 e 17:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-fd8542a8.png)

</br>Fonte: http://www.cnc.min-financas.pt/faqs_publico.html

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-f77a04e9.png)

</br>Fonte: http://www.cnc.min-financas.pt/faqs_publico.html

</br>No manual de implementação do SNC-AP (2ª versão), no Capítulo 4 – Normas e Contabilidade Pública, no âmbito da NCP 26 – Contabilidade e Relato Orçamental, em resposta à questão 2.17:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-7e164ce0.png)

</br>Fonte: http://www.cnc.min-financas.pt/pdf/SNC_AP/MANUAL%20DE%20IMPLEMENTACAO_SNC_AP_Versao2_HomologadoSEO.pdf

</br> De referir também a NCP 19 – Benefícios dos empregados, também referida no Manual de implementação (2ª versão), que menciona como benefícios de curto prazo:
![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-742828a7.png)

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3d84f42f.png)

</br>Fonte: http://www.cnc.min-financas.pt/pdf/SNC_AP/MANUAL%20DE%20IMPLEMENTACAO_SNC_AP_Versao2_HomologadoSEO.pdf

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

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-3c442d01.png)

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
