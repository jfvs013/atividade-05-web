# Projeto Pessoal: Jacson Francisco Viana Santos - Portfólio Web

**Nome:** Jacson Francisco Viana Santos

**Descrição:** Esta atividade faz parte da disciplina de Desenvolvimento Web I. O objetivo é aplicar e consolidar os conhecimentos adquiridos em HTML e CSS, desenvolvendo um website pessoal com múltiplos conteúdos, demonstrando proficiência na estruturação e estilização de páginas web, além de atender aos requisitos mínimos de um projeto web funcional e responsivo.

**Resumo do Projeto:**
Este projeto é um website pessoal dedicado a Jacson Francisco Viana Santos, estudante de Bacharelado em Sistemas de Informação. O site tem como objetivo apresentar sua trajetória acadêmica, habilidades técnicas, experiências profissionais e projetos, além de fornecer uma galeria de fotos, vídeos relacionados à sua formação e uma seção de contato.

## Estrutura do Projeto:

O website é composto pelas seguintes páginas principais:

* **`index.html` (Página Inicial)**
    * **Propósito:** Apresenta uma visão geral e introdutória sobre Jacson Francisco, seu perfil acadêmico atual e paixões.
    * **Conteúdo:** Inclui uma breve biografia, destacando sua formação no BSI e sua paixão por tecnologia e desenvolvimento web. Uma imagem centralizada serve como elemento visual de destaque.

* **`curriculo.html` (Currículo)**
    * **Propósito:** Detalha a formação acadêmica, habilidades técnicas e experiências profissionais de Jacson Francisco.
    * **Conteúdo:** Organizado em tabelas claras, abrange seções para `Técnico em Informática Integrado ao Ensino Médio`, `Bacharelado em Sistemas de Informação`, `Habilidades e Ferramentas`, `Idiomas` e `Projetos e Experiências`. Tabelas são utilizadas para listar matérias/aulas e habilidades, enquanto listas (`<ul>`) detalham as atividades em projetos/estágios.

* **`galeria.html` (Galeria)**
    * **Propósito:** Oferece uma coleção de imagens relacionadas ao perfil de Jacson Francisco.
    * **Conteúdo:** Exibe uma galeria de fotos, permitindo aos usuários visualizarem aspectos visuais relacionados à sua jornada acadêmica e pessoal.

* **`videos.html` (Saiba mais: Formação acadêmica no IFNMG.)**
    * **Propósito:** Compila vídeos relevantes sobre a formação acadêmica oferecida pelo IFNMG, que é a instituição de ensino de Jacson.
    * **Conteúdo:** Apresenta vídeos incorporados do YouTube que contextualizam e aprofundam o conhecimento sobre os cursos de informática do IFNMG, oferecendo uma perspectiva dinâmica.

* **`contato.html` (Contato)**
    * **Propósito:** Permite que os visitantes do site entrem em contato com Jacson Francisco através de um formulário.
    * **Conteúdo:** Contém um formulário completo com diversos controles de entrada, incluindo campos para nome, e-mail, assunto (com um seletor `select`), preferência de contato (com `radio buttons`), área de texto para mensagem e um checkbox para aceite de termos de privacidade.

## Recursos e Design:

* **Navegação Fixa:** Um sistema de cabeçalho duplo e fixo foi implementado: uma faixa superior (`.faixa`) com o título principal do site e uma faixa inferior (`.faixa2`) contendo o menu de navegação principal. Ambas permanecem visíveis ao rolar a página para facilitar a navegação entre as seções.
* **Design Responsivo:** A meta tag `viewport` e o CSS são cuidadosamente configurados para garantir que o site se adapte a diferentes tamanhos de tela (desktop, tablet, celular), proporcionando uma boa experiência de usuário em qualquer dispositivo.
* **Centralização de Conteúdo:** O conteúdo principal de todas as páginas é centralizado horizontalmente, com margens aparentes, através da classe `.main-content` e configurações de `margin: 0 auto;`.
* **CSS Centralizado:** Todos os estilos são gerenciados em um único arquivo `style.css` dentro de uma pasta `css` para garantir consistência visual e fácil manutenção.
* **Imagens Organizadas:** Todas as imagens utilizadas no site estão armazenadas em uma pasta `images`.
* **Formulário Completo:** A página de contato inclui um formulário com mais de 5 controles, demonstrando o uso de diferentes tipos de `input`, `select` e `textarea`.

## Recursos e Aspectos Técnicos Utilizados na Criação do Site:

Este projeto foi desenvolvido utilizando as linguagens de marcação e estilização web fundamentais: HTML5 para a estrutura do conteúdo e CSS3 para o design e apresentação visual.

### 1. Estrutura e Semântica HTML5:

O HTML5 foi utilizado para construir a base do site, focando em uma estrutura semântica e acessível.

**Tags Estruturais Principais:**

* `<!DOCTYPE html>`: Declara o tipo de documento como HTML5.
* `<html>`: Elemento raiz de todas as páginas, com atributo `lang="pt-br"` para indicar o idioma do conteúdo.
* `<head>`: Contém metadados da página.
    * `<meta charset="UTF-8">`: Define a codificação de caracteres para UTF-8, garantindo a exibição correta de caracteres especiais.
    * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Essencial para responsividade, informa ao navegador como controlar as dimensões da viewport, garantindo que o site se adapte a diferentes tamanhos de tela.
    * `<title>`: Define o título da página exibido na aba do navegador, específico para cada seção do site.
    * `<link rel="stylesheet" href="style.css">`: Vincula o arquivo CSS externo para estilização.
* `<body>`: Contém todo o conteúdo visível da página.

**Tags de Conteúdo e Agrupamento:**

* `<div>`: Amplamente utilizado para agrupar e organizar seções do conteúdo, como `faixa`, `faixa2`, `main-content`, `rodape`, `container-pagina-inicial`, `container-curriculo`, `container-galeria`, `container-videos`, `container-contato`, `secao-curriculo`, `secao-especificacao`, `galeria-fotos`, `galeria-item`, `videos-grid`, `video-item`, `video-embed`, `formulario-contato`, `form-grupo`, `radio-grupo`, `checkbox-grupo`.
* `<h1>`, `<h2>`, `<h3>`: Usadas para títulos e subtítulos, seguindo uma hierarquia de importância para o conteúdo em cada página.
* `<p>`: Para parágrafos de texto.
* `<ul>`, `<li>`: Utilizadas para listas não ordenadas, notavelmente para o menu de navegação (`.faixa2 ul`), para listar habilidades e para detalhar experiências em `curriculo.html`.
* `<a>`: Para links de navegação entre páginas e para redirecionamento externo (como para WhatsApp, Instagram), com atributos `href` para o destino, `target="_blank"` para abrir em nova aba e `rel="noopener noreferrer"` para segurança em links externos.
* `<img>`: Para incorporar imagens no layout, com o atributo `src` para o caminho da imagem e `alt` para texto alternativo (importante para acessibilidade).
* `<table>`, `<tr>`, `<td>`: Utilizadas para estruturar dados tabulares na página `curriculo.html` (Matérias, Habilidades, Idiomas).
* `<iframe>`: Para incorporar vídeos externos (do YouTube) na página `videos.html`, com atributos como `src` para o link do vídeo, `frameborder`, `allow` e `allowfullscreen`.
* `<form>`, `<label>`, `<input>`, `<select>`, `<option>`, `<textarea>`, `<button>`: Utilizados para criar o formulário de contato em `contato.html`, garantindo interatividade e coleta de dados.

### 2. Estilização CSS3:

O CSS3 é o pilar do design visual do site, garantindo uma apresentação coesa e responsiva.

**Arquivo Único:**

* Todo o estilo é gerenciado a partir do arquivo `style.css`.

**Importação de Fontes:**

* Fontes externas (`Open Sans` e `Roboto Slab`) são importadas do Google Fonts usando `@import url()`. Uma terceira fonte (`Arial`) é usada para a navegação.

**Seletores Utilizados:**

* **Seletores de Tipo:** `html`, `body`, `p`, `h1`, `h2`, `h3`, `img`, `ul`, `li`, `a`, `table`, `tr`, `td`, `iframe`, `form`, `label`, `input`, `select`, `textarea`, `button`.
* **Seletores de Classe:** Amplamente utilizados para aplicar estilos específicos a elementos com classes como `faixa`, `faixa2`, `centralizar`, `text-center`, `main-content`, `container-pagina-inicial`, `container-curriculo`, `container-galeria`, `container-videos`, `container-contato`, `rodape`, `rodape-container`, `rodape-secao`, `redes-sociais-lista`, `rodape-info`, `copyright`, `secao-curriculo`, `curriculo-img`, `specs-table`, `secao-especificacao`, `galeria-fotos`, `galeria-item`, `galeria-autor`, `videos-grid`, `video-item`, `video-embed`, `video-titulo`, `video-autor`, `formulario-contato`, `form-grupo`, `radio-grupo`, `checkbox-grupo`, `botao-enviar`.
* **Seletores de Pseudoclasse:** `:hover` para efeitos interativos (links de navegação, itens de galeria, botões), `:focus` para campos de formulário e `.ativo` para destacar a página atual na navegação. `:nth-child(even)` para estilização de linhas alternadas em tabelas.
* **Seletores Combinadores:** `faixa h1`, `faixa h2`, `faixa2 ul`, `faixa2 ul li`, `faixa2 ul li a`, `specs-table tr`, `specs-table tr:last-child`, `specs-table tr:nth-child(even)`, `specs-table td`, `specs-table td:first-child`, `specs-table td:last-child`, `radio-grupo input[type="radio"]`, `checkbox-grupo label`.

**Propriedades CSS Principais:**

* **Layout e Posicionamento:** `display` (com `flex` para layouts fluidos e responsivos em cabeçalho, navegação, galeria, vídeos e formulário, além de `block` e `inline-block`), `flex-direction`, `justify-content`, `align-items`, `gap` (para espaçamento entre itens flex), `margin`, `padding`, `width`, `height`, `max-width`, `min-height` (para o corpo e `textarea`), `position` (`fixed` para cabeçalho e menu), `top`, `left`, `z-index` (para camadas dos elementos fixos), `overflow` (hidden).
* **Tipografia:** `font-family` (com três fontes distintas), `font-size`, `color`, `font-weight`, `text-align`, `text-decoration` (para links), `line-height`.
* **Caixas e Bordas:** `background-color` (com uso de três cores principais: `#004080` (azul escuro), `#333` (cinza escuro) e `white` / `#f8f8f8` / `#fcfcfc` (tons de branco/claro), `border`, `border-bottom`, `border-radius`, `box-shadow` (para dar profundidade a elementos como contêineres, cabeçalho e itens de galeria/vídeo), `outline` (para foco de formulário).
* **Modelo de Caixa:** `box-sizing: border-box;` aplicado globalmente ou em elementos específicos como formulários, para facilitar o controle de padding e largura.
* **Transições:** `transition` para animações suaves ao interagir com elementos (links da navegação, itens de galeria/vídeo, botões de formulário).
* **Transformações:** `transform: translateY(-5px);` para o efeito de "levantar" em itens de galeria/vídeo ao passar o mouse.
* **Responsividade Específica para Vídeos:** `padding-bottom: 56.25%;` dentro de `.video-embed` para manter a proporção 16:9 dos vídeos incorporados.
* **Outros:** `list-style: none;` (para remover marcadores de lista), `scroll-padding-top` (para rolagem suave abaixo do cabeçalho fixo), `resize: vertical;` para `textarea`.
