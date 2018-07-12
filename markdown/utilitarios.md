# Utilitários (em atualização)

## 1. Abertura de um novo Ano
Para aceder ao ecrã relativo aos documentos que a entidade pretende transportar para o novo ano, deve seguir o seguinte caminho:

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-0d8416c8.png)

No ecrã aberto, deve o utilizador selecionar os documentos que pretende que transitem de ano e indicar os anos. Por fim deve clicar no botão "Converter".

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-1be269bc.png)

Para confirmar que a conversão dos documentos está concluída, o sistema irá gerar uma mensagem como a apresentada seguidamente:

![](https://spmssicc.github.io/pages/markdown/mu_snc_ap.assets/mu_snc_ap-b79dbb41.png)

## 2. Gestão Diagnósticos

Este menu permite ao utilizador identificar incoerências na parametrização e/ou documentação, através de opções disponibilizadas pelo sistema.

Para aceder ao menu de Gestão Diagnósticos, deve o utilizador seguir o seguinte caminho na aplicação:

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-b26eb551.png)

Na janela aberta deve o utilizador indicar o diagnóstico pretendido e de seguida deve clicar em "Executar Diag."

Para visualizar os diagnósticos disponíveis no sistema, o utilizador deve clicar no botão redondo. Será aberta uma nova janela onde estará apresentada a lista de diagnósticos disponíveis. Deve o utilizador selecionar o diagnóstico pretendido clicando duas vezes sobre o mesmo ou em "OK".

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-228bcc84.png)

>**Nota:** Caso o diagnóstico já tenha sido executado anteriormente, ao selecioná-lo, o ecrã ficará preenchido com os resultados obtidos na última execução. Neste caso, para atualizar o diagnóstico, deve clicar em "Executar Diag."

Ao longo dos próximos subcapítulos são descritos, detalhadamente, os diagnósticos que o utilizador pode executar.

### 2.1 501 Plano de contas

Este diagnóstico valida todo o plano de contas local da instituição confrontando o mesmo com o plano de contas central da Unileo e da ACSS, quer a nível de conteúdo quer a nível de estrutura (desdobramentos).

Ao executar o diagnóstico, o ecrã fica preenchido com o resultado do mesmo. Cada linha preenchida apresenta uma incoerência encontrada numa determinada conta, sendo que, se uma conta apresentar mais do que uma incoerência, essa conta irá aparecer tantas vezes quantas incoerências apresentar.

Seguidamente está apresentado o ecrã após uma execução de diagnóstico.

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-8573ea5c.png)

Na tabela seguinte é apresentada a informação contemplada em cada campo (coluna) da janela.

| Campo  | Informação contemplada            |
|:-------|:----------------------------------|
| #      | Código da incoerência/validação.  |
| Ano    | Ano do documento.                 |
| Conta  | Conta que apresenta incoerências. |
| Campo1 | Designação da conta.              |
| Data   | Data de execução do diagnóstico.  |

</br>Neste diagnóstico, são efetuadas várias validações ao plano, sendo que cada validação tem um código atribuído com um determinado significado. Segue abaixo a lista de validações efetuadas neste diagnóstico e os respetivos significados:

| Código | Significado                                           |
|:------:|:------------------------------------------------------|
|   8    | Conta de acumulação igual à conta.                    |
|   40   | Contas que acumulam para contas de movimento.         |
|   41   | Contas de acumulação que não existem.                 |
|   42   | Contas de acumulação que não têm contas de movimento. |
|   46   | Conta com Acumulação incoerente no plano ACSS.        |
|   47   | Conta com Acumulação incoerente no plano Unileo.      |
|   48   | Conta ACSS em falta no plano local.                   |
|   49   | Conta Unileo em falta no plano local.                 |
|   50   | Conta Ano plano ACSS e M no plano local.              |
|   51   | Conta A no plano Unileo e M no plano local.           |
|   52   | Desdobramento ilegal no plano ACSS.                   |
|   53   | Desdobramento ilegal no plano Unileo.                 |
<!-- ![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-fdc397d6.png) -->

</br>Este resultado de diagnóstico pode ser exportado para um ficheiro CSV. O aspeto do ficheiro CSV é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-a611173d.png)

Após a execução do diagnóstico, a instituição deve avaliar o resultado obtido e a ação a ter perante o mesmo. Deve-se dar uma especial atenção a desdobramentos mal efetuados pois estas incoerências podem influenciar peças contabilísticas. Para verificar se as contas que apresentam incoerências nos desdobramentos apresentam movimentos deve ser executado o diagnóstico 506, descrito posteriormente.

### 2.2 502 Lançamentos iniciais de 2018 com conversão inválida SNC-AP

Este diagnóstico permite identificar documentos iniciais com lançamentos efetuados em POCMS que, ao transitarem para o ano 2018, convertem para contas SNC-AP de **acumulação** ou **inexistentes** no plano de contas local.

Ao executar o diagnóstico, o ecrã fica preenchido com as incoerências encontradas que podem ser exportadas para ficheiro CSV.

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-92f08a52.png)

Na tabela seguinte é apresentada a informação contemplada em cada campo (coluna) da janela.

| Campo    | Informação contemplada                                                                                                          |
|:---------|:--------------------------------------------------------------------------------------------------------------------------------|
| #        | Código da incoerência. "45 - Lançamentos iniciais de 2018 com conversão inválida SNC-AP (para conta de acumulação/inexistente)" |
| Entidade | Entidade àqual pertence o documento.                                                                                            |
| Tipo     | Tipo de documento inicial: FD, P2, P1, NC, etc...                                                                               |
| Ano      | Ano do documento.                                                                                                               |
| Número   | Número do documento.                                                                                                            |
| Serie    | Série do documento.                                                                                                             |
| Conta    | Conta SNC-AP para a qual foi convertida a conta POCMS. (esta conta é a que é de acumulação ou não existe no plano)              |
| Campo1   | Conta POCMS que foi convertida para uma conta SNC-AP incorreta.                                                                 |
| Campo2   | Descrição da incoerência e ação que deve ser adotada para ultrapassar a situação.                                               |
| Campo4   | Valor lançado a débito na conta em questão.                                                                                     |
| Campo5   | Valor lançado a crédito na conta em questão.                                                                                    |
| Data     | Data de execução do diagnóstico.                                                                                                |

</br> O aspeto do ficheiro exportado é como o do apresentado seguidamente.

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-ee91e74f.png)


### 2.3 503 Faturas com classificador inválido ou sem classificador ou sem financeiras ou sem conversão SNC-AP em 2018

Este diagnóstico permite verificar todas as faturas (de anos anteriores e do exercício corrente) que tenham classificadores inválidos ou inexistentes, que não tenham rubricas financeiras associadas e/ou que apresentam contas com conversões para SNC-AP mal efetuadas.

Ao executar o diagnóstico, o ecrã fica preenchido com as incoerências encontradas que podem ser exportadas para um ficheiro CSV.

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-b8c1ef00.png)

Na tabela seguinte é apresentada a informação contemplada em cada campo (coluna) da janela.

|Campo | Informação contemplada|
|:--|:--|
|#   | Código da incoerência: "54 - Faturas com classificador inválido/sem classificador/sem financeira/sem conversão SNC-AP em 2018"  |
|Entidade    | Entidade àqual pertence o documento.  |
|Tipo    | Tipo de documento inicial: FD, P2, P1, CC, etc...  |
|Ano    | Ano do documento.    |
|Numero    | Número do documento.   |
|Serie    | Série do documento.   |
|Campo1    |Descrição da incoerência. Neste diagnóstico podem ser apresentadas as seguintes incoerências: </br></br> - Documento com contas sem conversão para SNC-AP. Atualizar conversão para SNC-AP</br>- Documento com contas sem conversão para SNC-AP. Pedir correcção</br>- Classificador XX.XX.XX (R/D) inválido</br>- Sem rubrica financeira no valor de xxxx</br>- Sem classificador no valor de xxxx</br>- Documento no valor de xxxx faltam yyyy|
|Data    | Data da realização do diagnóstico.    |

</br>O aspeto do ficheiro CSV produzido é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-05a7a08f.png)


### 2.4 506 Valida o plano de contas local contra o plano central

Este diagnóstico percorre o plano de contas local identificando as incoerências encontradas quando confrontado com o plano de contas central do Ministério das Finanças (MF) e/ou do Ministério da Saúde (MS). Para além deste resultado, este diagnóstico permite também identificar se as contas que apresentam incoerências possuem movimentos.

Ao executar o diagnóstico, o ecrã fica preenchido com as incoerências encontradas que podem ser exportadas para um ficheiro CSV.

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-e61f8ad0.png)

Na tabela seguinte é apresentada a informação contemplada em cada campo (coluna) da janela.

| Campo  | Informação contemplada                                                            |
|:-------|:----------------------------------------------------------------------------------|
| #      | Código da incoerência: "55 - Valida plano de contas local contra o plano central  |
| Conta  | Conta que apresenta incoerências de acumulação.                                   |
| Campo1 | Movimentos na conta.                                                              |
| Campo2 | Identificação do Plano Central (MF ou MS)                                         |

</br>O aspeto do fixheiro CSV é como o do apresentado seguidamente:

![](https://spmssicc.github.io/pages/markdown/utilitarios.assets/utilitarios-63a68569.png)
