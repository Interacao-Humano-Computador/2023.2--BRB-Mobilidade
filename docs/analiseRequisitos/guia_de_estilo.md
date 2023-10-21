# Guia de Estilo
## BRB Mobilidade (Estudantil)

## Visão Geral

Este guia de estilo estabelece as diretrizes de design e interação para o sistema BRB Mobilidade, com o objetivo de proporcionar uma experiência de usuário consistente, eficiente e agradável. Ele se destina a designers, desenvolvedores e todos os membros da equipe envolvidos na criação e manutenção da interface do usuário.

## Princípios de Design

1. **Usabilidade:** O BRB Mobilidade deve ser fácil de usar, eficiente e acessível para todos os usuários.

2. **Consistência:** Mantenha um design visual e de interação consistente em todo o sistema.

3. **Eficiência:** Minimize a quantidade de cliques e etapas necessárias para realizar tarefas.

4. **Feedback:** Forneça feedback claro e imediato ao usuário sobre suas ações.

5. **Acessibilidade:** Garanta que o sistema seja acessível a todos, em conformidade com as diretrizes de acessibilidade.

## Identidade Visual

### **Logotipo e Marca:**
A logo precisar ter o mesmo tamanho em todas as abas: (88 x 43)px
O posicionamento da logo deve estar alinhado acima e à esquerda da div(dicWidthLimit)
Clique aqui para fazer o download da logo

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%20cadastro.png?raw=true">
    <p>Figura 1: Logo (Fonte: Lucas, 2023)</p>
</div>

### **Esquema de Cores:**

|Cor|Código|Cor| Código|
|---|------|---|-------|
|Branco|(#FFFFFF)|Amarelo|(#F1C40F)|
|Ciano|(#57C3C3)|Verde|(#008000)|
|Azul Escuro|(#2C63A7)|Azul Leve|(#D9EDF7)|
|Azul Claro|(#009FE3)|Vermelho|(#B94A48)|
|Preto|(#000000)|Vermelho Claro|(#F2DEDE)|
|Cinza Escuro|(#494c50)|Cinza Claro|(#9c9d9f)|


- Cores de destaque:
  - Amarelo……....(#F1C40F)
  - Verde………….(#008000)
  - Azul Leve..……(#D9EDF7)

- Cores de erro:
	- Vermelho…….…..(#B94A48)
	- Vermelho Claro…(#F2DEDE)

<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%20cadastro.png?raw=true">
    <p>Figura 2: Paleta do sistema (Fonte: Lucas, 2023)</p>
</div>

### **Tipografia**

A tipografia é um elemento-chave na comunicação visual. Ela envolve a seleção cuidadosa de tipos de letra, tamanhos, cores e espaçamento para criar uma apresentação de texto coesa e impactante. A escolha da tipografia certa reflete identidade e ajuda a melhorar a legibilidade e a estética dos materiais. A consistência tipográfica é fundamental para fortalecer uma marca e mensagem.

    Fontes principais: Arial e Open Sans
    Fonte secundária: Reem Kufi
**Tamanhos de fonte:**

- Arial: 18px, 16px, 15px.
- Open Sans: 18px, 15px, 14px, 13px.
- Reem Kufi: 30px.

**Locais de Utilização:**

    Arial: Logo, Navbar principal.
    Open Sans: Subtítulos, Navbar secundário.
    Reem Kufi: Título na aba inicial

### **Ícones**
    Fonte: Font Awesome
Ícones: Seta; Arquivo; Interrogação; Interrogação vazado; Cartão; Adição; Dupla seta; Alerta; Cartão de identidade; Libras; Pessoa; Casa; Nuvem_upload, Check, Disquete.

#IMAGEM COM TODOS OS ÍCONES
<br>

<div style="text-align: center">
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/diagramas%20hta/Diagrama%20cadastro.png?raw=true">
    <p>Figura 2: Ícones utilizados (Fonte: Lucas, 2023)</p>
</div>


## Layout e Estrutura

O layout envolve a distribuição de elementos como texto, imagens e gráficos de maneira equilibrada e intuitiva, buscando transmitir informações de forma clara e atrativa.

  - **Grids e Layouts**

Nesse sistema utiliza-se 3 Grids principais, o de tela inicial, tela de informações, Tela de serviços/operações.
Os grids devem ser responsivos e compatíveis com os principais tamanhos/proporções de tela: 4:3, 21:9, 16:9.

#ADICIONAR CADA UM DOS GRIDS (Tela inicial, Tela Serviços/Operações, Tela de Informações)

  A altura varia de acordo com a quantidade de elementos na página

    ax-width: 1000px;
    margin-left: auto;
    margin-right: auto;

### **Navegação**
A interface tem duas barras de navegação, uma que fica visível antes de logar e continua visível após o login, e a outra que só será visível após o login

1° Barra de navegação (Principal)
Posicionada logo abaixo da div em que se encontra o “topo” do site, com a logo
Largura máxima: 1000px
Altura: 50px
Alinhamento dos itens: A esquerda
Itens: Início; Login; Acessibilidade Libras
Altura fixa dos itens: 35px
A largura dos itens é variável de acordo com o texto e os ícones neles contidos

2° Barra de navegação
Posicionada 5px abaixo da div(page_title)
Largura máxima: 1000px
Altura: 58px
Largura de cada item na barra: 92px
Itens: Serviços, Troca de Instituição, 2° Via, Extensão de Acesso, Troca de Endereço, Alteração de foto, Alteração de contato, Retirada do cartão, Minha frequência, Meus acessos, Liberar cartão

## Componentes de Interface

### **Botões**
#TABELA COM (NOME, IMAGEM DO BOTÃO, TAMANHO)
    - Todos os botões devem ser retangulares e com bordas arredondadas: 3px
    - Tipos de botão: Salvar, Anexar Arquivo, Registrar Solicitação, Nova solicitação, Adicionar, Remover, Consultar, Verificar Dados

#MEDIR O TAMANHO DOS BOTÕES
    - Tamanhos: [Descrição dos tamanhos de botões]
    - Estados de Interação: [Descrição dos estados de botões]

### **Formulários e Campos de Entrada:**

#TABELA COM (NOME, IMAGENS DO CAMPO DE ENTRADA, TAMANHO)
    - [Instruções sobre o design de formulários]

### **Alertas e Notificações:**
    - [Instruções para o design de alertas e notificações]

## Interatividade

- **Comportamentos de Elementos Interativos:**
    - [Descrever como elementos interativos devem se comportar]

- **Transições e Animações:**
    - [Instruções sobre o uso de transições e animações]

- **Feedback ao Usuário:**
    - [Descrever como fornecer feedback visual, sonoro ou de outra forma]

## Acessibilidade

- [Instruções detalhadas sobre como garantir a acessibilidade, incluindo o uso de rótulos, contrastes, etc.]

## Dispositivos e Resoluções Suportados

- [Listar dispositivos-alvo e resoluções de tela suportadas]

## Sugestões de Melhoria
Padronizar melhor as Fontes

| Versão | Data       | Modificação                             | Autor                         | Revisores                         |
| ------ | ---------- | --------------------------------------- | ----------------------------- | ----------------------------- |
|    1.0   |   21/10/2023   |   Criação do documento |  [Lucas Lobão](https://github.com/lucaslobao-18)| |