# Guia de Estilo

## BRB Mobilidade (Estudantil)

## Introdução

Este guia de estilo estabelece as diretrizes de design e interação para o sistema BRB Mobilidade, com o objetivo de proporcionar uma experiência de usuário consistente, eficiente e agradável. Ele se destina a designers, desenvolvedores e todos os membros da equipe envolvidos na criação e manutenção da interface do usuário.

## Princípios de Design

1. **Usabilidade:** O BRB Mobilidade deve ser fácil de usar, eficiente e acessível para todos os usuários.

2. **Consistência:** Mantenha um design visual e de interação consistente em todo o sistema.

3. **Eficiência:** Minimize a quantidade de cliques e etapas necessárias para realizar tarefas.

4. **Feedback:** Forneça feedback claro e imediato ao usuário sobre suas ações.

5. **Acessibilidade:** Garanta que o sistema seja acessível a todos, em conformidade com as diretrizes de acessibilidade.

## Identidade Visual

A identidade visual é um conjunto de elementos visuais, como logotipos, cores, tipografia e elementos gráficos, que representam a personalidade e valores de uma marca ou empresa. Uma identidade visual bem definida contribui para a construção da confiança, a diferenciação no mercado e a criação de uma imagem sólida da marca.

Apresentaremos alguns padrões a serem seguidos nesses elementos:

### **Logotipo e Marca**

1. A logo precisar ter o mesmo tamanho em todas as abas: (88 x 43)px
2. Não deve ser alterado as cores da logo

</br>

<div style="text-align: center">
    <p>Figura 1: Logo (Fonte: BRB Mobilidade, 2023)</p>  
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/logo_BRBmobilidade.png?raw=true" style="width: 80%">
</div>

### **Esquema de Cores**

<p>Tabela 1: Paleta de cores (Fonte: Lucas, 2023)</p>

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

</br>

<div style="text-align: center">
    <p>Figura 2: Paleta do sistema (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/tabela_cores.png?raw=true">
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

**Ícones:** Seta, Arquivo, Interrogação, Interrogação vazado, Cartão, Adição, Dupla seta, Alerta, Cartão de identidade, Libras, Pessoa, Casa, Nuvem_upload, Check, Disquete.

</br>

<div style="text-align: center">
<p>Figura 3: Ícones utilizados (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/icons2.png?raw=true">
</div>

## Layout e Estrutura

O layout envolve a distribuição de elementos como texto, imagens e gráficos de maneira equilibrada e intuitiva, buscando transmitir informações de forma clara e atrativa.

### Grids

O termo "grid" se refere a uma estrutura de grade usada para organizar elementos em um layout de página, como em design gráfico, design de interface de usuário e design de sites. Sendo assim uma ferramenta essencial para criar layouts consistentes e harmônicos, garantindo que os elementos da página estejam alinhados e posicionados de maneira equilibrada.

Nesse sistema utiliza-se 3 Grids principais, o de tela inicial, tela de informações, Tela de serviços/operações.

- Os grids devem ser responsivos e compatíveis com os principais tamanhos/proporções de tela: 4:3, 21:9, 16:9.

</br>
<div style="text-align: center">

<p>Figura 4: Grid página inicial (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/grid/tela_inicial.png?raw=true">
</br>

<p>Figura 5: Grid da página de informações (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/grid/info.png?raw=true">

</br>

<p>Figura 6: Grid das páginas de serviços e operações (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/grid/serv_op.png?raw=true">
    
</div>

### **Navegação**

A interface tem duas barras de navegação, uma que fica visível antes de logar e continua visível após o login, e a outra que só será visível após o login

1° Barra de navegação (Principal)

- Posicionada logo abaixo da div em que se encontra o “topo” do site, com a logo
- Largura máxima: 1000px
- Altura: 50px
- Alinhamento dos itens: A esquerda
- Itens: Início; Login; Acessibilidade Libras
- Altura fixa dos itens: 35px
- A largura dos itens é variável de acordo com o texto e os ícones neles contidos

</br>

<div style="text-align: center">
<p>Figura 7: Barra de navegação principal (Fonte: BRB Mobilidade, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/grid/nav_1.png?raw=true">
</div>

</br>

2° Barra de navegação

- Posicionada 5px abaixo da div(page_title)
- Largura máxima: 1000px
- Altura: 58px
- Largura de cada item na barra: 92px
- Itens: Serviços, Troca de Instituição, 2° Via, Extensão de Acesso, Troca de Endereço, Alteração de foto, Alteração de contato, Retirada do cartão, Minha frequência, Meus acessos, Liberar cartão.

</br>

<div style="text-align: center">
<p>Figura 8: Barra de navegação secundária (Fonte: BRB Mobilidade, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/grid/nav2.png?raw=true">
</div>

## Componentes de Interface

### **Botões**

Os botões presentes na figura abaixo representam todos os tipos de botões do sistema, além de representar também o seu "estado", por exemplo, quando o cursor não está sobre o botão "Registrar solicitação"", ele fica com a coloração azul, mas, quando o cursor está sobre ele, a cor fica em cinza escuro.

Além dessa classe de botões, temos também esse modelo do botão "salvar", que é um botão estático, não varia com a passagem do cursor sobre ele. Por último, uma checkbox padrão, utilizada para aceitar termos dentro do sistema.
</br>
<div style="text-align: center">
<p>Figura 9: Botões referência (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/botoes/botoes.png?raw=true">
</div>

1. Todos os botões devem ser retangulares
2. As bordas são arredondadas em 5px

Tipos de botão: Salvar, Anexar Arquivo, Registrar Solicitação, Nova solicitação, Adicionar, Remover, Consultar, Verificar Dados

### **Formulários e Campos de Entrada**

A imagem abaixo representa todos os tipos de campo de informação presentes no sistema:
</br>
<div style="text-align: center">
<p>Figura 10: Botões referência (Fonte: Lucas, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/Form/campos_form.png?raw=true">
</div>
</br>

1. Os campos de seleção devem ter o preenchimento na cor branca, e uma mensagem na cor cinza escrito "selecionar..." para que as pessoas compreendam mais facilmente a funcionalidade

2. Os campos de texto são preenchidos na cor branca, entretando, não há nada escrito dentro do campo.

3. Campos obrigatórios devem ter um "*" após o título

4. Os campos para inserção de datas devem possuir um pequeno calendário, para que a pessoa selecione a data por meui de cliques, sem precisar digitá-las

### **Alertas e Notificações**

<div style="text-align: center">
</br>
<div style="text-align: center">
<p>Figura 12: Alertas  (Fonte: Artur, 2023)</p>
    <img src="https://github.com/Interacao-Humano-Computador/2023.2--BRB-Mobilidade/blob/main/docs/assets/guia_estilo/alertas/alertas.png?raw=true">
</div>
</br>

## Interatividade

### **Comportamentos de Elementos Interativos**

### Campos de texto

- **Transições e Animações:**
    1. As bordas do campo recebem um pouco de sombra, para evidenciar que o campo estã selecionado
    2. Campos de "Selecionar..." devem ter um dropdown, que mostra as opções disponíveis quando recebe um clique com o mouse
    3. Os itens da lista dropdown mudam de cor quando o mouse passa por cima

### Botões

- **Transições e Animações:**
    1. Mudança de cor ao passar o mouse sobre alguns botões (não todos)

### Barras de navegação

- **Transições e Animações:**
    1. Mudança de cor ao passar o mouse por cima de cada item

## Acessibilidade

A acessibilidade em sistemas interativos refere-se à prática de tornar produtos digitais, como aplicativos e websites, acessíveis a pessoas com deficiências, incluindo visuais, auditivas e motoras. Isso envolve o uso de recursos como descrições de imagens, legendas de vídeo, teclados virtuais, entre outros, para garantir que todos possam usar e interagir com esses sistemas de forma inclusiva, promovendo igualdade de acesso à informação e funcionalidades.

Após uma breve análise por inspecção no site do BRB Mobilidade e também utilizando a ferramenta WAVE(Web Accessibility Evaluation Tools), foi possível identificar alguns pontos positivos e negativos sobre a acessibidade no site

**Pontos positivos:**

1. Áudiodescrição das páginas
2. O site dá suporte para leitores de tela

**Pontos negativos:**

1. O sistema não suporta navegação pelo teclado
2. Alguns elementos tem um contraste muito baixo em relação ao plano de fundo, por exemplo, a barra de navegação principal

## Compatibilidade

1. O sistema deve ser compatível tanto com Smartphones quanto Desktops
2. Deve funcionar nos principais navegadores (Chrome, Safari, Opera, Edge e Firefox)

</br>

| Versão | Data       | Modificação                             | Autor                         | Revisores                         |
| ------ | ---------- | --------------------------------------- | ----------------------------- | ----------------------------- |
|    1.0   |   21/10/2023   |   Criação do documento |  [Lucas Lobão](https://github.com/lucaslobao-18)|[Artur Jack](https://github.com/artur-jack)|