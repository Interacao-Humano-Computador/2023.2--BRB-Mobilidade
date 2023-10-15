### Introdução

A Análise Hierárquica de Tarefas (HTA) é uma metodologia usada para analisar tarefas complexas descompondo-as em elementos mais simples e hierarquicamente organizados. Essa abordagem visa identificar a estrutura das tarefas, relacionando objetivos gerais a sub-objetivos e ações específicas. A HTA é útil na análise de sistemas interativos, permitindo uma compreensão detalhada das tarefas executadas pelos usuários, o que pode orientar o design de sistemas mais eficazes e usáveis.

### Cadastrar-se

| Objetivos/Operações | Relações| Problemas e Recomendações|
| ------ | ------ | ------ |
|0. Acompanhar cadastro| 1>2 |**input:** formulário de login com CPF e senha         **feedback:** logar no sistema ou retornar mensagem "erro ao logar", usuário ou senha inválidos. **plano:** informar os dados de login e clicar em "logar" |
|1. Login| 1+2 |**plano:** informar CPF e senha|
|1.1 Adicionar CPF|     | |
|1.2 Adicionar senha|     | |
|2. Confirmar login|  1/2   | **input:** clique com o mouse **plano:** clicar do botão "logar", ou , "recuperar senha"|
|2.1 Clicar no botão "logar"| | **feedback:** logar no sistema ou retornr mensagem de erro caso os dados estajam incorretos  | |
|2.2 Recuperar senha|     | |


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
|1. Login| 1+2 |**plano:** informar CPF e senha|
|1.1 Adicionar CPF|     | |
|1.2 Adicionar senha|     | |
|2. Confirmar login|  1/2   | **input:** clique com o mouse **plano:** clicar do botão "logar", ou , "recuperar senha"|
|2.1 Clicar no botão "logar"| | **feedback:** logar no sistema ou retornr mensagem de erro caso os dados estajam incorretos  | |
|2.2 Recuperar senha|     | |

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%20acompanhar%20cadastro.png?raw=true">
    <p>Figura 1: Diagrama HTA da tarefa de acompanhar cadastro</p>
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
|2.1 Clicar checkbox para aceitar o termo|        | |
|2.2 Selecionar motivo da solicitação|        | |
|2.3 Adiciconar nome do estudante|        | |
|2.4 Adicionar email para contato|        | |
|2.5 Adicionar observação (opcional)|        | |
|2.6 Anexar documentos (Comprovante de pag, Boletim de ocorrência(em caso de perda ou roubo))| | **recomendação:** Somente é permitido envio de documentos em formato PDF e/ou arquivos de imagem (JPG,JPEG,GIF,BMP e PNG) de até 2 megabytes      | |
|3.0 Confirmar solicitação|    1>2     | |
|3.1 Clicar em registrar solicitação|        | **feedback:** cadastrar solicitação ou retorar mensagem de erro caso os dados estajam incorretos|

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%202via.png?raw=true">
    <p>Figura 2: Diagrama HTA da tarefa de 2°via</p>
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
|1.1 Navegar entre as páginas|  |**input:** cliques com o mouse em ícones de navegação|
|2.0 Nova solicitação| 1>2 |**input:** formulário com os dados da solicitação, aceitar termo, selecionar motivo, nome, email, observações, anexo de documentos. **feedback:** nova solicitação é cadastrada e fica visível na aba "Acompanhar solicitações"|
|2.1 Adicionar dados|1+2 |**plano:** adicionar ou selecionar os dados nas caixas de entrada|
|2.2 Clicar na checkbox para aceitar o termo|  |**recomendação:** a marcar a checkbox é requisito para solicitar a extensão|
|2.3 Selecionar motivo da solicitação|  ||
|2.4 Adicionar nome do estudante|  ||
|2.5 Adicionar email para contato|  ||
|2.6 Adicionar observação|  ||
|2.7 Adicionar documentos|  ||
|3. Confirmar solicitação| 1>2 |**plano:** clicar no ícone de "Registrar solicitação" **feedback:** Ou o sistema cadastra a nova solicitação, ou o sistema retorna uma mensagem de erro.|
|3.1 Clicar em Registrar solicitação|  ||

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%20extensao%20de%20acesso.png?raw=true">
    <p>Figura 3: Diagrama HTA da tarefa de extensão de acesso</p>
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
|0. Troca de instituição| 1/2 |**input:** formulário para solicitação de troca, incluindo anexo do documento que comprova o vínculo com a instituição. **plano:** escolher entre acompanhar solicitações ou fazer uma nova solicitação|
|1. Nova solicitação| 1>2 ||
|1.1 Adicionar matrícula|  ||
|1.2 Adicionar instituição de ensino| ||
|1.3 Selecionar modalidade| ||
|1.4 Selecionar curso|  ||
|1.5 Selecionar série, período e ano|  ||
|1.6 Escrever uma observação|  ||
|1.7 Anexar um documento de comprovação (declaração de passe, declaração de vínculo, grade horária com data)|  ||
|2.0 Acompanhar solicitacão| 1>2 ||
|2.1 Posso navegar entre as páginas|  ||
|3.0 Salvar solicitação|  ||

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%20troca%20de%20institui%C3%A7%C3%A3o.png?raw=true">
    <p>Figura 4: Diagrama HTA da tarefa de troca de instituição</p>
</div>

## Histórico de versão

| Versão | Data       | Modificação                             | Autor                         | Revisores                         |
| ------ | ---------- | --------------------------------------- | ----------------------------- | ----------------------------- |
|    1.0   |   14/10/2023   |   Criação do documento |  [Fause Carlos](https://github.com/FauseSkyWalker)|Fause|
|    1.1   |   14/10/2023   |   Adição dos diagramas de HTA |  [Amanda](https://github.com/Amandaaaaabreu) e [Artur Jackson](https://github.com/artur-jack) | Felipe |
|    1.2   |   14/10/2023   |   Adição das tabelas de HTA |  [Amanda](https://github.com/Amandaaaaabreu) e [Artur Jackson](https://github.com/artur-jack) | Juan |

## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

