# devstartfranciscojunior
# Viagens Landing Page (Projeto TripMe)

Este projeto é uma landing page (página de aterrissagem) com tema de viagens, criada como um desafio para praticar conceitos fundamentais de HTML semântico e CSS moderno, incluindo a integração com frameworks de front-end como o Bootstrap.

A página apresenta um design limpo e responsivo, focado em "fisgar" o interesse do visitante com um banner atraente e navegação interna direta para as seções principais de informação.

## Tecnologias Utilizadas

* **HTML5:** Estruturação semântica utilizando tags modernas como `<header>`, `<nav>`, `<main>`, `<section>` e `<footer>`.
* **CSS3:** Estilização personalizada para sobrepor o Bootstrap e criar os elementos únicos do design, como o banner com *overlay* (sobreposição de texto), cores personalizadas e transições suaves.
* **Bootstrap 5 (via CDN):** Utilizado para a estrutura principal do layout (componente Navbar, sistema de Grid via `.container`, classes utilitárias de espaçamento e tipografia).
* **Normalize.css (via CDN):** Incluído para garantir uma renderização padronizada e consistente entre diferentes navegadores.

## Requisitos Cumpridos

Este projeto atende a todas as especificações mínimas solicitadas no desafio:

1.  **Banner Principal:** A página possui um banner principal dentro da tag `<main>`, utilizando uma `background-image` (imagem de fundo) de um vilarejo e texto `<h1>` sobreposto (overlay).
2.  **Navegação Semântica:** Uma tag `<nav>` do Bootstrap, fixa no topo, permite a navegação principal.
3.  **Três Seções:** A página contém as três seções de conteúdo necessárias, identificadas por IDs:
    * `#minha-viagem`
    * `#nos-encontre`
    * `#conselhos`
4.  **Navegação Interna:** Os links na barra de navegação são âncoras (`<a href="#id-da-secao">`) que direcionam o usuário suavemente (via `scroll-behavior: smooth`) para a seção correspondente na mesma página.
5.  **Links "Voltar ao Topo":** Cada seção de conteúdo possui um link/botão (`<a href="#home">`) que permite ao usuário retornar rapidamente ao topo da página (header).
6.  **Efeitos de Hover:** Todos os elementos navegáveis (os links da navbar e os botões "Voltar ao Topo") mudam visualmente de aparência ao passar o mouse por cima (efeito `:hover`), conforme exigido.

## Como Executar

Este projeto consiste apenas em arquivos front-end estáticos e não requer instalação de dependências, pois todas as bibliotecas (Bootstrap e Normalize) são carregadas via CDN.

1.  Clone ou faça o download deste repositório.
2.  Certifique-se de que os dois arquivos, `index.html` e `style.css`, estejam na mesma pasta.
3.  Abra o arquivo `index.html` diretamente em qualquer navegador web moderno (como Google Chrome, Firefox ou Edge).

Para desenvolvimento, recomenda-se utilizar a extensão **Live Server** no Visual Studio Code para visualizar as alterações em tempo real.
