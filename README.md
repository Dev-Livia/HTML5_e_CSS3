
# 1° Módulo do curso de HTML e CSS

O primeiro módulo do curso de **HTML e CSS** do professor **Gustavo Guanabara** aborda os seguintes tópicos:

### 1. Como a Internet Chega na Minha Casa?
- **Explicação sobre a infraestrutura da internet e como ela é distribuída até chegar aos lares dos usuários:** A internet é composta por uma vasta rede de infraestruturas que conectam dispositivos globalmente. A conexão até sua casa envolve várias etapas:
  - **Provedores de Serviços de Internet (ISPs):** São as empresas que fornecem acesso à internet e utilizam tecnologias como fibra óptica, cabo coaxial ou DSL para conectar sua casa.
  - **Infraestrutura de Rede:** Inclui cabos submarinos, fibras ópticas e torres de comunicação que transmitem dados em alta velocidade.
  - **Distribuição Local:** O sinal da internet chega ao seu modem ou roteador, que distribui a conexão para seus dispositivos via Wi-Fi ou cabos Ethernet.

### Como a Internet Funciona?
- **Descrição do funcionamento da internet, incluindo conceitos de servidores, clientes e protocolos de comunicação:** A internet opera com base no modelo cliente-servidor:
  - **Servidores:** Computadores que armazenam e disponibilizam conteúdo, como sites e serviços.
  - **Clientes:** Dispositivos que acessam o conteúdo armazenado nos servidores, como navegadores web.
  - **Protocolos de Comunicação:** Regras como HTTP (Hypertext Transfer Protocol) e HTTPS (HTTP Secure) que definem como os dados são enviados e recebidos entre clientes e servidores.
  - **Endereços IP e DNS:** Cada dispositivo tem um endereço IP único, e o DNS (Domain Name System) traduz nomes de domínio em endereços IP, facilitando a navegação.

### O Que é Domínio e Hospedagem?
- **Definição de domínio e hospedagem, e como eles são fundamentais para que um site esteja disponível na internet:**
  - **Domínio:** É o nome de um site, como `www.exemplo.com`, que torna o acesso ao site mais fácil para os usuários.
  - **Hospedagem:** Refere-se ao serviço que armazena os arquivos e dados do site em servidores, tornando-o acessível na internet. Sem hospedagem, um site não pode ser acessado pelos usuários.

### A Diferença Entre HTML, CSS e JavaScript
- **Explicação das funções e diferenças entre HTML, CSS e JavaScript, e como essas tecnologias se complementam no desenvolvimento web:**
  - **HTML (HyperText Markup Language):** Usado para estruturar o conteúdo de uma página web. Define a estrutura e o conteúdo dos elementos na página.
  - **CSS (Cascading Style Sheets):** Utilizado para estilizar e formatar a apresentação de uma página web. Controla a aparência visual dos elementos HTML.
  - **JavaScript:** É uma linguagem de programação que adiciona interatividade e funcionalidades dinâmicas às páginas web. Permite criar animações, validar formulários e responder a ações dos usuários.

### Front-end, Back-end e Full Stack
- **Introdução aos conceitos de front-end, back-end e desenvolvedor full stack, com ênfase nas responsabilidades e tecnologias associadas a cada área:**
  - **Front-end:** Refere-se ao desenvolvimento da parte do site que os usuários veem e com a qual interagem. Inclui HTML, CSS e JavaScript.
  - **Back-end:** Envolve o desenvolvimento da parte do servidor e a lógica do aplicativo. Responsável pelo gerenciamento de dados, autenticação e operações no servidor.
  - **Full Stack:** Desenvolvedores que trabalham tanto no front-end quanto no back-end, possuindo um conhecimento abrangente de todas as camadas do desenvolvimento web.

### Instalando Todas as Ferramentas
- **Guia para instalação das ferramentas necessárias para começar a programar em HTML e CSS, como editores de código e navegadores:**
  - **Editor de Código:** Escolha um editor de código, como Visual Studio Code, Sublime Text ou Atom, para escrever e editar seu código.
  - **Navegador:** Use um navegador web (Google Chrome, Mozilla Firefox, Safari) para testar e visualizar seu código HTML e CSS.
  - **Terminal (opcional):** Para desenvolvedores avançados, o terminal pode ser útil para executar comandos e gerenciar projetos.

### Seu Primeiro Código HTML
- **Introdução prática à criação de um documento HTML, com explicações passo a passo para escrever seu primeiro código:**

  ```html
  <!DOCTYPE html>
  <html lang="pt-BR">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Meu Primeiro Site</title>
  </head>
  <body>
      <h1>Olá, Mundo!</h1>
      <p>Bem-vindo ao meu primeiro site.</p>
  </body>
  </html>

### Capítulo 6 Aula 4 – A tag `img` em HTML5

- **Descrição:** A tag `<img>` em HTML5 é usada para inserir imagens em uma página web. Ela é um elemento vazio e não possui uma tag de fechamento.
- **Atributos principais:**
  - `src`: Especifica o caminho para o arquivo da imagem.
  - `alt`: Fornece um texto alternativo para descrever a imagem.
  - `width` e `height`: Definem as dimensões da imagem.

**Exemplo:**

``html
<img src="imagem.jpg" alt="Descrição da imagem" width="300" height="200">
### Capítulo 6 Aula 5 – Como mudar o favicon de um site

- **Descrição:** O favicon é o ícone exibido na aba do navegador para uma página web. Para mudar o favicon de um site, você deve adicionar um link para o arquivo de ícone no `<head>` da sua página HTML. O formato mais comum para favicons é `.ico`, mas você também pode usar outros formatos como `.png` ou `.svg`.

- **Atributos principais:**
  - `rel`: Define o tipo de link, geralmente `icon` para favicons.
  - `href`: Especifica o caminho para o arquivo do favicon.
  - `type`: Define o tipo MIME do ícone (opcional, mas recomendado).

**Exemplo:**

```html
<head>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
```
### Capítulo 7 Aula 1 – Hierarquia de Títulos

- **Descrição:** A hierarquia de títulos em HTML organiza o conteúdo da página em seções e subseções. Os títulos são definidos com as tags `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, e `<h6>`, onde `<h1>` é o título principal e `<h6>` é o título menos importante. Usar uma hierarquia adequada melhora a acessibilidade e a estrutura do documento.

- **Regras principais:**
  - **`<h1>`**: Título principal da página. Deve ser único por página.
  - **`<h2>`**: Títulos de seções dentro do `<h1>`.
  - **`<h3>`** a **`<h6>`**: Subdividem ainda mais as seções conforme necessário.

**Exemplo:**

```html
<h1>Título Principal</h1>
<h2>Seção 1</h2>
<h3>Subseção 1.1</h3>
<h4>Subseção 1.1.1</h4>
<h2>Seção 2</h2>
<h3>Subseção 2.1</h3>
```
### Capítulo 8 Aula 1 – Semântica na HTML5 é Importante

- **Descrição:** A semântica no HTML5 utiliza tags que têm significado específico, ajudando a estruturar o conteúdo de maneira mais clara e acessível. Utilizar as tags semânticas corretas melhora a SEO e a experiência do usuário.

- **Regras principais:**
  - **`<header>`**: Define a área de cabeçalho de um documento ou seção.
  - **`<nav>`**: Define uma seção de navegação com links.
  - **`<main>`**: Define o conteúdo principal da página.
  - **`<section>`**: Define uma seção genérica no documento.
  - **`<article>`**: Define um conteúdo independente e reutilizável.
  - **`<footer>`**: Define o rodapé do documento ou seção.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Semântica</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Início</a></li>
            <li><a href="#about">Sobre</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Início</h2>
            <p>Conteúdo principal da página.</p>
        </section>
        <section id="about">
            <h2>Sobre</h2>
            <p>Informações sobre o site.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Meu Site</p>
    </footer>
</body>
</html>
```
### Capítulo 8 Aula 2 – Negrito e Itálico do Jeito Certo

- **Descrição:** As tags `<strong>` e `<em>` são recomendadas para aplicar negrito e itálico, respectivamente, pois fornecem significado semântico ao texto, melhorando a acessibilidade e a SEO.

- **Regras principais:**
  - **`<strong>`**: Aplica negrito e indica que o texto é de maior importância.
  - **`<em>`**: Aplica itálico e indica que o texto tem ênfase.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Negrito e Itálico</title>
</head>
<body>
    <p>O texto em <strong>negrito</strong> é importante para enfatizar informações, enquanto o texto em <em>itálico</em> pode ser usado para destacar citações ou palavras estrangeiras.</p>
</body>
</html>
```
### Capítulo 8 Aula 3 – Formatações Adicionais em HTML

- **Descrição:** HTML5 oferece tags adicionais para formatação de texto, como subscript e superscript, que são úteis para representar informações científicas ou matemáticas.

- **Regras principais:**
  - **`<sub>`**: Define texto como subíndice.
  - **`<sup>`**: Define texto como superíndice.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formatações Adicionais</title>
</head>
<body>
    <p>A fórmula da água é H<sub>2</sub>O, onde o <sub>2</sub> indica o número de átomos de hidrogênio.</p>
    <p>A equação para a área de um círculo é A = πr<sup>2</sup>, onde <sup>2</sup> é o expoente.</p>
</body>
</html>
```
### Capítulo 8 Aula 4 – Citações e Códigos

- **Descrição:** Utilizar as tags `<blockquote>` e `<code>` permite representar citações e trechos de código de maneira adequada e semântica, facilitando a leitura e compreensão do conteúdo.

- **Regras principais:**
  - **`<blockquote>`**: Define uma citação longa ou um bloco de citação.
  - **`<code>`**: Define um trecho de código em linha.
  - **`<pre>`**: Mantém o formato do texto como espaços e quebras de linha, ideal para código.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Citações e Códigos</title>
</head>
<body>
    <blockquote>
        <p>"O HTML é a espinha dorsal da web moderna."</p>
        <footer>- Autor Desconhecido</footer>
    </blockquote>
    <pre><code>
function helloWorld() {
    console.log('Olá, mundo!');
}
    </code></pre>
</body>
</html>
```
### Capítulo 9 Aula 1 – Listas OL e UL

- **Descrição:** Em HTML, listas ordenadas (`<ol>`) e listas não ordenadas (`<ul>`) são usadas para organizar itens em uma lista. As listas ordenadas são numeradas automaticamente, enquanto as listas não ordenadas são marcadas com pontos ou outros símbolos.

- **Regras principais:**
  - **`<ol>`**: Define uma lista ordenada. Itens dentro da lista são numerados.
  - **`<ul>`**: Define uma lista não ordenada. Itens dentro da lista são marcados com pontos.
  - **`<li>`**: Define um item de lista, aplicável tanto para listas ordenadas quanto para listas não ordenadas.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas OL e UL</title>
</head>
<body>
    <h2>Lista Ordenada</h2>
    <ol>
        <li>Primeiro item</li>
        <li>Segundo item</li>
        <li>Terceiro item</li>
    </ol>

    <h2>Lista Não Ordenada</h2>
    <ul>
        <li>Item A</li>
        <li>Item B</li>
        <li>Item C</li>
    </ul>
</body>
</html>
```
### Capítulo 9 Aula 2 – Listas Mistas e de Definição

- **Descrição:** Listas mistas combinam diferentes tipos de listas (ordenadas e não ordenadas) para criar uma hierarquia complexa. As listas de definição são usadas para descrever termos e definições.

- **Regras principais:**
  - **`<dl>`**: Define uma lista de definição.
  - **`<dt>`**: Define um termo em uma lista de definição.
  - **`<dd>`**: Define uma descrição ou definição de um termo.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listas Mistas e de Definição</title>
</head>
<body>
    <h2>Lista Mista</h2>
    <ol>
        <li>Categoria 1
            <ul>
                <li>Subcategoria A</li>
                <li>Subcategoria B</li>
            </ul>
        </li>
        <li>Categoria 2
            <ul>
                <li>Subcategoria C</li>
                <li>Subcategoria D</li>
            </ul>
        </li>
    </ol>

    <h2>Lista de Definição</h2>
    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language, a linguagem de marcação para a web.</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets, usado para estilizar a aparência dos documentos HTML.</dd>
    </dl>
</body>
</html>
```
### Capítulo 10 Aula 1 – Links e Âncoras em HTML5

- **Descrição:** Em HTML5, links e âncoras são fundamentais para a navegação entre páginas e dentro de uma mesma página. A tag `<a>` é usada para criar links e pode incluir atributos para definir o destino e o comportamento do link.

- **Regras principais:**
  - **`<a href="URL">`**: Define um link para uma URL especificada. O atributo `href` define o destino do link.
  - **`target="_blank"`**: Abre o link em uma nova aba ou janela.
  - **`name`**: Define uma âncora no documento, usada para criar links para uma posição específica dentro da mesma página.
  - **`id`**: Também pode ser usado para definir uma âncora e referenciar uma posição específica dentro da página.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Links e Âncoras</title>
</head>
<body>
    <h1>Exemplo de Links e Âncoras</h1>

    <p>Visite o <a href="https://www.example.com" target="_blank">Exemplo</a> para mais informações.</p>

    <h2 id="section1">Seção 1</h2>
    <p>Leia mais sobre <a href="#section2">Seção 2</a> abaixo.</p>

    <h2 id="section2">Seção 2</h2>
    <p>Estamos agora na <a href="#section1">Seção 1</a>.</p>
</body>
</html>
```
### Capítulo 10 Aula 2 – Links Internos

- **Descrição:** Links internos são usados para navegar para diferentes seções da mesma página ou para outras páginas dentro do mesmo site. Eles são criados usando a tag `<a>` com um atributo `href` que aponta para um identificador específico ou para um arquivo dentro do mesmo site.

- **Regras principais:**
  - **`href="#id"`**: Define o destino para uma âncora dentro da mesma página. O `id` deve corresponder a um atributo `id` em um elemento no documento.
  - **`href="pagina.html"`**: Define o destino para outra página dentro do mesmo site.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Links Internos</title>
</head>
<body>
    <h1>Links Internos</h1>
    <p><a href="#section1">Ir para Seção 1</a></p>
    <p><a href="#section2">Ir para Seção 2</a></p>

    <h2 id="section1">Seção 1</h2>
    <p>Esta é a Seção 1.</p>

    <h2 id="section2">Seção 2</h2>
    <p>Esta é a Seção 2.</p>
</body>
</html>
```
### Capítulo 10 Aula 2 – Links Internos

- **Descrição:** Links internos são usados para navegar para diferentes seções da mesma página ou para outras páginas dentro do mesmo site. Eles são criados usando a tag `<a>` com um atributo `href` que aponta para um identificador específico ou para um arquivo dentro do mesmo site.

- **Regras principais:**
  - **`href="#id"`**: Define o destino para uma âncora dentro da mesma página. O `id` deve corresponder a um atributo `id` em um elemento no documento.
  - **`href="pagina.html"`**: Define o destino para outra página dentro do mesmo site.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Links Internos</title>
</head>
<body>
    <h1>Links Internos</h1>
    <p><a href="#section1">Ir para Seção 1</a></p>
    <p><a href="#section2">Ir para Seção 2</a></p>

    <h2 id="section1">Seção 1</h2>
    <p>Esta é a Seção 1.</p>

    <h2 id="section2">Seção 2</h2>
    <p>Esta é a Seção 2.</p>
</body>
</html>
