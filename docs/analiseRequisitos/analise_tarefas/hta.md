### Introdução

A Análise Hierárquica de Tarefas (HTA) é uma metodologia usada para analisar tarefas complexas descompondo-as em elementos mais simples e hierarquicamente organizados. Essa abordagem visa identificar a estrutura das tarefas, relacionando objetivos gerais a sub-objetivos e ações específicas. A HTA é útil na análise de sistemas interativos, permitindo uma compreensão detalhada das tarefas executadas pelos usuários, o que pode orientar o design de sistemas mais eficazes e usáveis.

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
|2.1 Clicar checkbox para aceitar o termo|        |**input:** clique(mouse)|
|2.2 Selecionar motivo da solicitação|        |**input:** clique(mouse)|
|2.3 Adiciconar nome do estudante|        |**input:** teclado|
|2.4 Adicionar email para contato|        |**input:** teclado|
|2.5 Adicionar observação (opcional)|        |**input:** teclado|
|2.6 Anexar documentos (Comprovante de pag, Boletim de ocorrência(em caso de perda ou roubo))| | **recomendação:** Somente é permitido envio de documentos em formato PDF e/ou arquivos de imagem (JPG,JPEG,GIF,BMP e PNG) de até 2 megabytes      | |
|3.0 Confirmar solicitação|    1>2     |**plano:** finalizar a solicitação, registrando-a no sistema|
|3.1 Clicar em registrar solicitação|        | **input:** clique(mouse) **feedback:** cadastrar solicitação ou retorar mensagem de erro caso os dados estajam incorretos|

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
|0. Troca de instituição| 1/2 |**input:** formulário para solicitação de troca, incluindo anexo do documento que comprova o vínculo com a instituição. **plano:** escolher entre acompanhar solicitações ou fazer uma nova solicitação, visualizar a lista de solicitações e responder formulário|
|1. Nova solicitação| 1>2 |**input:** formulário com os dados da solicitação,matrícula, instituição de ensino, modalidade, selecionar curso, (série, período, ano), observações, anexo de documentos. **plano:** inserir/selecionar as informações em cada um dos campos disponíveis|
|1.1 Adicionar matrícula|  |**input:** teclado|
|1.2 Adicionar instituição de ensino| |**input:** busca(teclado) + clique(mouse)|
|1.3 Selecionar modalidade| |**input:** clique(mouse)|
|1.4 Selecionar curso|  |**input:** busca(teclado) + clique(mouse)|
|1.5 Selecionar série, período e ano|  |**input:** clique(mouse)|
|1.6 Escrever uma observação|  |**input:** teclado|
|1.7 Anexar um documento que comprove o vínculo|  |**input:** arquivos do dispositivo (pdf,jpeg,jpg,pnj,gif)|
|2.0 Acompanhar solicitacão| 1>2 |**feedback:** lista com as solicitações ativas||
|2.1 Navegar entre as páginas|  |**input:** clique(mouse)|
|3.0 Salvar solicitação|  |**input:** clique(mouse) **feedback:** cadastrar a solictação ou, retornar erro caso os dados do formulário estejam incorretos|

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
|    1.3   |   15/10/2023   |  Atualização das tabelas HTA  | [Lucas](https://github.com/lucaslobao-18) e [Amanda](https://github.com/Amandaaaaabreu) |Artur|

## Bibliografia

> BARBOSA, Simone; DINIZ, Bruno. Interação Humano-Computador. Editora Elsevier, Rio de Janeiro, 2010.

