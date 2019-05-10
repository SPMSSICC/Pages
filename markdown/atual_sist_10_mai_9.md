<div style="width:100%; height:30px"><span onclick="loadMdDoc('atualizacoes', ['btnMenu'],'', null)" class="voltar">Voltar</span></div>

# Atualizações no SICC - 10 de maio de 2019


- Atualização das fórmulas dos mapas DFC, DDORC, DODES e DTAS;
- Atualização do Balancete da Contabilidade Orçamental;
- Atualização da produção do CPLC e do BA de forma a converter o plano local do organismo para o plano selecionado pelo utilizador (Plano Central ou Plano Setorial do MS);

>**NOTAS:** Para produzir os ficheiros para a **UNILEO** e **TC** deve ser selecionada a opção Plano Central

> Para produzir os ficheiros para **ACSS** deve ser selecionado o Plano Setorial do MS

**Alerta-se que para que os ficheiros sejam construídos corretamente deve-se garantir a coerência do plano de contas. Para o efeito deverá ser executado o diagnóstico 501 no sentido de verificar, entre outras incoerências, quais as contas que apresentam acumulações incorretas e se existem contas do tipo acumulação sem contas movimento.**  

- Acrescentada funcionalidade para gerar um ficheiro de formato CSV com os Plano Central, Setorial do MS e Local;

![](https://spmssicc.github.io/pages/markdown/atual_sist_10_mai_9.assets/atual_sist_10_mai_9-fbacc516.png)

Esta funcionalidade está disponível no ecrã do CPLC - Ficheiros S3CP e produz um ficheiro com a informação dos três planos.
De referir que, esta relação entre os planos tem por base o plano de contas local, isto é, se no plano setorial do MS existir uma conta que não foi contemplada no plano local, esta conta não irá aparecer no ficheiro.
Para verificar quais as contas que não foram consideradas no plano local, devem executar o diagnóstico 501.
