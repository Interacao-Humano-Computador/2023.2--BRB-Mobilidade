### Introdução

A Análise Hierárquica de Tarefas (HTA) é uma metodologia usada para analisar tarefas complexas descompondo-as em elementos mais simples e hierarquicamente organizados. Essa abordagem visa identificar a estrutura das tarefas, relacionando objetivos gerais a sub-objetivos e ações específicas. A HTA é útil na análise de sistemas interativos, permitindo uma compreensão detalhada das tarefas executadas pelos usuários, o que pode orientar o design de sistemas mais eficazes e usáveis.

### Técnicas Utilizadas

Para identificar as tarefas de usuário foram utilizadas duas técnicas: observação direta e cenários.

A observação direta envolveu a observação de cada tarefa, em geral, essa técnica é utilizada para observar o usuário utilizando o sistema, mas no nosso caso, foi a nossa própria utilização do sistema que foi embasou a análise. Isso permitiu identificar as tarefas que os usuários realizam naturalmente, com base em suas ações e comportamentos "reais".

Além disso, os cenários foram criados para descrever situações hipotéticas em que os usuários utilizariam o site para atingir seus objetivos. Os cenários detalharam as ações necessárias, informações relevantes e eventuais obstáculos que os usuários poderiam encontrar.

### Como ler os diagramas?
Um objetivo é a abstração mais geral de uma atividade que o usuário vá realizar, ele é representado por um retângulo no diagrama. Os subobjetivos são os objetivos derivados do que está acima dele, e é representado da mesma maneira que o objetivo, entretanto, se esse subobjetivo representa a menor parte da derivação hierárquica e não tem mais nenhuma ação abaixo dessa, isso significa que esse subobjetivo é uma operação. Nesse sentido, o retângulo que representa uma  operação recebe um traço logo abaixo dele.

Além de definirmos o que é cada ação, também precisamos demonstrar a ordem em que essas são realizadas, para isso utilizamos alguns símbolos (1>2, 1+2, 1/2).

- **1>2:** Significa que os próximos subobjetivos/operações precisam ser executados(as), um após ao outro, em sequência.
- **1+2:** Significa que os próximos subobjetivos/operações podem ser executados(as) de forma paralela, não importando a ordem .
- **1/2:** Significa uma escolha, o usuário deve optar um uma das ações

<br>

<div style="text-align: center">
    <p>Figura 1: Elementos do Diagrama HTA </p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/legenda_HTA.jpeg?raw=true" width=75%>
    <p>Fonte: (Barbosa, Silva, B.S.; Interação Humano-Computador, 2010, p. 193 - “Análise Hierárquica de Tarefas”, figura 6.1) </p>
</div>

### Cadastrar-se

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Cadastre-se| 1>2 |**input:** formulário de cadastro dados pessoais, estudantis, endereço e contatos **feedback:** cadastrar no sistema ou retornar mensagem de erro. **plano:** validar se o CPF já não está cadastrado, recolher todas as informações necessárias para o cadastro, cadastrar ou reportar inconsistências dos dados do formulário e em relação aos dados presentes nas bases de dados do governo.|
|1. Adicionar Dados|1+2|**Plano:** Preencher os campos do formulário **input:** caracteres ou cliques com o mouse para selecionar opções|
|1.1 Adicionar CPF|     |**input:** teclado|
|1.2 Adicionar nome|     |**input:** teclado| |
|1.3 Adicionar data de nascimento|     |**input:** teclado|
|1.4 Selecionar sexo|     |**input:** clique (mouse)|
|1.5 Adicionar nome da mãe  |     |**input:** teclado|
|1.6 Adicionar nome do pai |     |**input:** teclado|
|1.7 Selecionar estado civil  |     |**input:** clique (mouse)|
|1.8 Adicionar documento de identificação|     |**input:** teclado|
|1.9 Adicionar número do documento  |     |**input:** teclado|
|1.10 Selecionar orgão emissor  |     |**input:** busca com o teclado + clique (mouse)|
|1.11 Selecionar UF  |     |**input:** clique (mouse)|
|1.12 Adicionar nome dos responsáveis (Caso seja menor de idade)|     |**input:** teclado|
|1.13 Adicionar RG dos responsáveis  (Caso seja menor de idade)|     |**input:** teclado|
|1.14 Selecionar orgão emissor dos responsáveis  (Caso seja menor de idade) |     |**input:** busca com o teclado + clique (mouse)|
|1.15 Selecionar UF dos responsáveis  (Caso seja menor de idade) |     |**input:** clique (mouse)|
|1.16 Adicionar número de telefone  |     |**input:** teclado|
|1.17 Adicionar CEP||**input:** teclado|
|1.18 Adicionar logradouro|     |**input:** teclado|
|1.19 Adicionar n* da residência |     |**input:** teclado|
|1.20 Adicionar bairro|     |**input:** teclado|
|1.21 Adicionar complemento |     |**input:** teclado|
|1.22 Selecionar cidade |     |**input:** clique (mouse)|
|1.23 Adicionar matrícula |     |**input:** teclado|
|1.24 Adicionar instituição de ensino |     |**input:** Busca com o Teclado + clique (mouse)|
|1.25 Selecionar modalidade |     |**input:** clique (mouse)|
|1.26 Selecionar curso |     |**input:** Busca com o Teclado + clique (mouse)|
|1.27 Selecionar (Série, período, ano) |     |**input:** clique (mouse)|
|1.28 Anexar todos os documentos comprobatórios (RG, declaração de vínculo, RG do responsável…) |     |**input:** arquivos do dispositivo (pdf,jpeg,jpg,pnj,gif)|
|1.29 Adicionar e-mail |     |**input:** teclado|
|1.30 Adicionar nome de login (cpf obrigatoriamente) |     |**input:** teclado|
|1.31 Adicionar senha |     |**input:** teclado|
|1.32 Adicionar confirmação de senha|     |**input:** teclado|
|2. Finalizar |     |**input:** clicar com o mouse no botão "FInalza", **Feedback:** Cadastrar o usuário no sistema ou reportar falha no cadastro|

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Diagrama%20cadastro.png?raw=true">
    <p>Figura 2: Diagrama HTA da tarefa de cadastrar-se (Fonte: Lucas, 2023)</p>
</div>

### Acompanhar cadastro

Esta atividade permite que o usuário se registre e consiga realizar o cadastro e a criação de sua conta no site e no acesso ao benefício de transporte 

Adicionar login(cpf)
Adicionar senha
Clicar em “Logar”
Clicar em opção “recuperar senha”
Recuperar Senha

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Acompanhar cadastro| 1>2 |**input:** formulário de login com CPF e senha         **feedback:** logar no sistema ou retornar mensagem "erro ao logar", usuário ou senha inválidos. **plano:** informar os dados de login e clicar em "logar" |
|1. Login| 1+2 |**plano:** informar CPF e senha **Feedback:** Logar ou bloquear acesso|
|1.1 Adicionar CPF|     |**input:** teclado|
|1.2 Adicionar senha|     |**input:** teclado|
|2. Confirmar login|  1/2   | **input:** clique com o mouse **plano:** clicar do botão "logar", ou , "recuperar senha"|
|2.1 Clicar no botão "logar"| | **feedback:** logar no sistema ou retornar mensagem de erro caso os dados estajam incorretos  | |
|2.2 Recuperar senha|     |**plano:** Redirecionar para o processo de recuperar senha|

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Diagrama%20acompanhar%20cadastro.png?raw=true">
    <p>Figura 3: Diagrama HTA da tarefa de acompanhar cadastro (Fonte: Artur Jackson e Amanda, 2023)</p>
</div>

### 2° via

Na tarefa Segunda via, o usuário possui a possibilidade de realizar um pedido de segunda via do seu benefício de transporte ṕublico, além de conseguir acompanhar o processo de solicitação que foi aberta

O processo de abertura envolve algumas etapas como:

Clicar checkbox para aceitar o termo
Selecionar motivo da solicitação
Adicionar nome do estudante
Adicionar email para ctt
Adicionar observação 
Anexar documentos (Comprovante de pag, Boletim de ocorrência(em caso de perda ou roubo))

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Segunda via |     1/2   | **input:** formulário para solicitação da segunda via, incluindo anexo do comprovante de pagamento e do boletim de ocorrência. **plano:** escolher entre acompanhar solicitações ou fazer uma nova solicitação |
|1.0 Acompanhar solicitações  | 1>2  | **feedback:** lista com as solicitações ativas|
|1.1 Posso navegar entre as páginas  |        |**input:** cliques com o mouse em ícones de navegação |
|2.0 Nova solicitação|   1>2      |**input:** formulário com os dados da solicitação, aceitar termo, selecionar motivo, nome, email, observações, anexo de documentos. **feedback:** nova solicitação é cadastrada e fica visível na aba "Acompanhar solicitações"|
|2.1 Clicar checkbox para aceitar o termo|        |**input:** clique(mouse)|
|2.2 Selecionar motivo da solicitação|        |**input:** clique(mouse)|
|2.3 Adiciconar nome do estudante|        |**input:** teclado|
|2.4 Adicionar email para contato|        |**input:** teclado|
|2.5 Adicionar observação (opcional)|        |**input:** teclado|
|2.6 Anexar documentos (Comprovante de pag, Boletim de ocorrência(em caso de perda ou roubo))| | **recomendação:** Somente é permitido envio de documentos em formato PDF e/ou arquivos de imagem (JPG,JPEG,GIF,BMP e PNG) de até 2 megabytes      | |
|3.0 Confirmar solicitação|    1>2     |**plano:** finalizar a solicitação, registrando-a no sistema|
|3.1 Clicar em registrar solicitação|        | **input:** clique(mouse) **feedback:** cadastrar solicitação ou retorar mensagem de erro caso os dados estajam incorretos|

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Diagrama%202via.png?raw=true">
    <p>Figura 4: Diagrama HTA da tarefa de 2°via (Fonte: Artur Jackson e Amanda, 2023)</p>
</div>

### Extensão de Acesso

A tarefa de extensão de acesso tem como principal objetivo possibilitar que o usuário realiza uma abertura de processo para garantir um aumento na quantidade de acessos mensais, além de ser possível acompanhar o procedimento do processo, o processo de abertura envolve

Clicar checkbox para aceitar o termo
Sel motivo da solicitação
Adicionar nome do estudante
Adicionar email para ctt
Adicionar observação (opcional)
Anexar documentos (Declaração de matrícula)
Clicar em Registrar solicitação

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Extensão de acesso| 1/2 |**input:** formulário para solicitação de extensão, incluindo anexo do documento que comprova a necessidade de extensão. **plano:** escolher entre acompanhar solicitações ou fazer uma nova solicitação|
|1.0 Acompanhar solicitações| 1>2 |**feedback:** lista com as solicitações ativas|
|1.1 Navegar entre as páginas|  |**input:** clique(mouse)|
|2.0 Nova solicitação| 1>2 |**input:** formulário com os dados da solicitação, aceitar termo, selecionar motivo, nome, email, observações, anexo de documentos. **feedback:** nova solicitação é cadastrada e fica visível na aba "Acompanhar solicitações"|
|2.1 Adicionar dados|1+2 |**plano:** adicionar ou selecionar os dados nas caixas de entrada|
|2.2 Clicar na checkbox para aceitar o termo|  |**input:** clique(mouse) **recomendação:** a marcar a checkbox é requisito para solicitar a extensão|
|2.3 Selecionar motivo da solicitação|  |**input:** clique(mouse)|
|2.4 Adicionar nome do estudante|  |**input:** teclado|
|2.5 Adicionar email para contato|  |**input:** teclado|
|2.6 Adicionar observação|  |**input:** teclado|
|2.7 Anexar documentos|  |**input:** arquivos do dispositivo (pdf,jpeg,jpg,pnj,gif)|
|3. Confirmar solicitação| 1>2 |**plano:** clicar no ícone de "Registrar solicitação" **input:** clique(mouse) **feedback:** Ou o sistema cadastra a nova solicitação, ou o sistema retorna uma mensagem de erro.|
|3.1 Clicar em Registrar solicitação|  ||

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Diagrama%20extensao%20de%20acesso.png?raw=true">
    <p>Figura 5: Diagrama HTA da tarefa de extensão de acesso (Fonte: Artur Jackson e Amanda, 2023)</p>
</div>

### Troca de Instituição

A atividade de troca de instituição tem como objetivo permitir que o usuário realize o recadastramento da nova instituição de ensino na qual ele pertence, para realizar este processo são necessários

Adicionar matrícula
Adicionar instituição de ensino
Selecionar modalidade 
Selecionar curso
Selecionar (Série, período, ano)
Escrever uma observação
Anexar um documento de comprovação (declaração de passe, declaração de vínculo, grade horária com data)

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Troca de instituição| 1/2 |**input:** formulário para solicitação de troca, incluindo anexo do documento que comprova o vínculo com a instituição. **plano:** escolher entre acompanhar solicitações ou fazer uma nova solicitação, visualizar a lista de solicitações e responder formulário|
|1. Nova solicitação| 1>2 |**input:** formulário com os dados da solicitação,matrícula, instituição de ensino, modalidade, selecionar curso, (série, período, ano), observações, anexo de documentos. **plano:** inserir/selecionar as informações em cada um dos campos disponíveis|
|1.1 Inserir Dados|  |**input:** teclado + clique(mouse)|
|1.1.1 Adicionar matrícula e instituição de ensino| |**input:** busca(teclado) + clique(mouse)|
|1.1.2 Selecionar modalidade, curso, série, período e ano| |**input:** busca(teclado) + clique(mouse)|
|1..1.3 Escrever uma observação|  |**input:** teclado|
|1..1.4 Anexar um documento que comprove o vínculo|  |**input:** arquivos do dispositivo (pdf,jpeg,jpg,pnj,gif)|
|1.2 Salvar solicitação|  |**input:** clique(mouse) **feedback:** cadastrar a solictação ou, retornar erro caso os dados do formulário estejam incorretos|
|2.0 Acompanhar solicitacão| 1>2 |**feedback:** lista com as solicitações ativas||
|2.1 Navegar entre as páginas|  |**input:** clique(mouse)|


<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Troca_instituicaoHTA.jpeg?raw=true">
    <p>Figura 6: Diagrama HTA da tarefa de troca de instituição (Fonte: Artur Jackson e Amanda, 2023)</p>
</div>

### Liberar cartão

Esta atividade permite que o usuário libere o cartão para começar a utilizá-lo.

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Liberar Cartão| 1>2 |**input:** formulário com o código do cartão e código do usuário **feedback:** O cartão é liberado, ou então, uma mensagem de erro aparece, caso os dados informados estejam incorretos ou por algum outro motivo. **plano:** informar os dados e confirmar a ação |
|1. Preencher Formulário| 1+2 |**plano:** informar o código do cartão e o código do usuário |
|1.1 Inserir código do cartão|     |**input:** teclado|
|1.2 Inserir código do usuário|     |**input:** teclado|
|2. Clicar em "Verificar Dados"|      | **input:** clique com o mouse **Feedback:** Mensagem dizendo que o cartão foi liberado, ou, um alerta de erro dizendo que não foi possível fazer a liberação|

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Diagrama_liberar_cartao.png?raw=true">
    <p>Figura 7: Diagrama HTA da tarefa de liberar cartão(Fonte: Lucas, 2023)</p>
</div>

### Alterar Foto

A atividade de alterar foto tem como objetivo permitir que o usuário realize a troca da foto do mesmo, para registro no sistema e uso na carteirinha.



| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
| 0. Alterar Foto | 1>2 | **input**: clique em "Nova solicitação **plano**: realizar nova solicitação |
| 1. Nova Solicitação | 1+2 | **plano**: realizar uma solicitação de nova foto  |
| 1.1 Digitar Observação |  | **input**: teclado |
| 1.2 Clicar em "Anexar Arquivo" |  | **input**: foto |
| 2. Clicar em "Salvar" |  | **input**: clique mouse |


<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas_hta/Diagrama_alterar_foto.png?raw=true">
    <p>Figura 8: Diagrama HTA da tarefa de alterar foto(Fonte: Felipe, 2023)</p>
</div>

### Trocar Endereço

Esta atividade permite que o usuário consiga trocar o endereço

- Adicionar login(cpf)
- Adicionar senha
- Clicar em “Logar”
- Clicar em opção “trocar endereço”
- Trocar endereço

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Troca de endereço| 1/2 |**input:** formulário para solicitação de troca, incluindo anexo do documento que comprova o vínculo com o endereço **plano:** fazer uma nova solicitação|
|1 Inserir Dados|  |**input:** teclado + clique(mouse)|
|1.1 Número do CEP| |**input:** busca(teclado) |
|1.2 Logradouro| |**input:** busca(teclado) |
|1.3 Número da residência|  |**input:** teclado|
|1.4 Bairro| |**input:** teclado|
|1.5 Complemento||**input:** teclado|
|1.6 Bairro||**input:** teclado + clique(mouse)|
|1.7 Complemento||**input:** teclado|
|1.8 Anexar um documento que comprove o vínculo|  |**input:** arquivos do dispositivo (pdf,jpeg,jpg,pnj,gif)|
|1.9 Salvar solicitação|  |**input:** clique(mouse) **feedback:** cadastrar a solictação ou, retornar erro caso os dados do formulário estejam incorretos|

<div style="text-align: center">
    <img src="-">
    <p>Figura 9: Diagrama HTA da tarefa de troca de endereço (Fonte: Juan Pablo, 2023)</p>
</div>


### Meus Acessos

Esta atividade permite que o usuário consiga visualizar os acessos que ele possui, além de poder visualizar o histórico de acessos que ele já utilizou.

- Adicionar login(cpf)
- Adicionar senha
- Clicar em “Logar”
- Clicar em opção “Meus acessos”
- Visualizar acessos

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Meus acessos| 1/2 |**input:** data de início e data de fim, caso o usuário deseje ver os acessos realizados em um período específico **plano:** inserir datas|
|1. Navegar entre as páginas|  |**input:** clique(mouse)|
|2. Consultar por período de tempo|  |**input:** clique(mouse)|
|2.1.1 Inserir data de início|  |**input:** teclado|
|2.1.2 Inserir data de fim|  |**input:** teclado|
|2.2 Clicar em "Consultar"|  |**input:** clique(mouse) **Feedback:** Acessos do período definido são apresentados |

<div style="text-align: center">
    <img src="../../assets/diagramas_hta/HTA_MeusAcessos.png">
    <p> Figura 10: Diagrama HTA da tarefa de Meus Acessos (Fonte: Arthur Sousa, 2023)</p>
</div>


## Histórico de versão

| Versão | Data       | Modificação                             | Autor                         | Revisores                         |
| ------ | ---------- | --------------------------------------- | ----------------------------- | ----------------------------- |
|    1.0   |   14/10/2023   |   Criação do documento |  [Fause Carlos](https://github.com/FauseSkyWalker)|Felipe|
|    1.1   |   14/10/2023   |   Adição dos diagramas de HTA |  [Amanda](https://github.com/Amandaaaaabreu) e [Artur Jackson](https://github.com/artur-jack) | Felipe |
|    1.2   |   14/10/2023   |   Adição das tabelas de HTA |  [Amanda](https://github.com/Amandaaaaabreu) e [Artur Jackson](https://github.com/artur-jack) | Juan |
|    1.3   |   15/10/2023   |  Atualização das tabelas HTA  | [Lucas](https://github.com/lucaslobao-18) e [Amanda](https://github.com/Amandaaaaabreu) |Artur|
|    1.3   |   15/10/2023   |  Atualização das tabelas HTA  | [Felipe](https://github.com/FHansen98) |Lucas|
|    1.4   |   06/11/2023   |  Atualização das tabelas HTA  | [Arthur Sousa](https://github.com/arthurrsousa) |Lucas|


## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.
