## Projeto: Carrossel de Destinos Turísticos

### Descrição

Este projeto é um carrossel de destinos turísticos implementado em HTML, CSS e JavaScript. Ele exibe uma lista de destinos com imagens, descrições e botões de ação para saber mais e acessar informações adicionais. O carrossel possui setas de navegação que permitem aos usuários navegar pelos itens da lista.

### Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

1. **index.html**: Contém a estrutura HTML do carrossel e a referência para os arquivos de estilo e script.
2. **style.css**: Define o estilo e a aparência do carrossel.
3. **script.js**: Contém a lógica de navegação do carrossel utilizando JavaScript.

### Funcionalidades

- **Navegação**: Botões "next" e "back" permitem aos usuários navegar pelos itens do carrossel.
- **Lista de Itens**: Cada item da lista exibe uma imagem, um título, uma descrição e dois botões de ação.
- **Miniaturas**: Além da lista principal, uma seção de miniaturas reflete os itens do carrossel para uma navegação visual rápida.

### Estrutura HTML

O arquivo HTML é estruturado da seguinte maneira:

- **Header**: Contém a navegação principal com links para Home, Informações e Fale Conosco.
- **Main Container**: Inclui duas principais seções:
  - **List**: Exibe os itens principais do carrossel.
  - **Thumb**: Exibe as miniaturas dos itens do carrossel.
- **Arrows**: Botões para navegação "next" e "back".

### Estilos CSS

O arquivo CSS define o layout e o estilo dos elementos HTML, incluindo:

- **Layout Responsivo**: Utiliza a fonte Poppins e é otimizado para diferentes tamanhos de tela.
- **Estilos de Botão**: Define a aparência dos botões de navegação e de ação nos itens.

### Lógica JavaScript

O arquivo script.js controla a funcionalidade do carrossel:

- **Seleciona Elementos HTML**: Utiliza `document.querySelector` para selecionar elementos necessários.
- **Eventos de Clique**: Define eventos de clique para os botões "next" e "back".
- **Função moveItemsOnclick**: 
  - Move o primeiro item da lista para o final ao clicar em "next".
  - Move o último item da lista para o início ao clicar em "back".
- **Manipulação DOM**: Atualiza a ordem dos itens na lista e nas miniaturas em resposta aos cliques nos botões de navegação.

### Como Usar

1. Clone o repositório ou faça o download dos arquivos.
2. Abra o arquivo `index.html` em um navegador web.
3. Use os botões de navegação para percorrer os diferentes destinos turísticos.

### Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão à internet para carregar fontes externas (Google Fonts)

### Contribuição

Se você quiser contribuir com este projeto, sinta-se à vontade para abrir um pull request ou reportar issues no repositório.

---

Este projeto foi desenvolvido para demonstrar um carrossel funcional utilizando tecnologias web básicas. É ideal para ser utilizado como base para projetos mais complexos ou como um exercício de aprendizagem em HTML, CSS e JavaScript.