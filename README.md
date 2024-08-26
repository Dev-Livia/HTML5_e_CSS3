
# 1° Módulo do curso de HTML e CSS

O primeiro módulo do curso de **HTML e CSS** do professor **Gustavo Guanabara** aborda os seguintes tópicos:

### 1. Como a Internet Chega na Minha Casa?
- Explicação sobre a infraestrutura da internet e como ela é distribuída até chegar aos lares dos usuários.

### Como a Internet Funciona?
- Descrição do funcionamento da internet, incluindo conceitos de servidores, clientes e protocolos de comunicação.

### O Que é Domínio e Hospedagem?
- Definição de domínio e hospedagem, e como eles são fundamentais para que um site esteja disponível na internet.

### A Diferença Entre HTML, CSS e JavaScript
- Explicação das funções e diferenças entre HTML, CSS e JavaScript, e como essas tecnologias se complementam no desenvolvimento web.

### Front-end, Back-end e Full Stack
- Introdução aos conceitos de front-end, back-end e desenvolvedor full stack, com ênfase nas responsabilidades e tecnologias associadas a cada área.

### Instalando Todas as Ferramentas
- Guia para instalação das ferramentas necessárias para começar a programar em HTML e CSS, como editores de código e navegadores.

### Seu Primeiro Código HTML
- Introdução prática à criação de um documento HTML, com explicações passo a passo para escrever seu primeiro código.

### Parágrafos e Quebras
- Como utilizar as tags de parágrafo (`<p>`) e quebras de linha (`<br>`) no HTML para formatar o texto em uma página web.

### Símbolos e Emojis no Seu Site
- Instruções sobre como inserir símbolos especiais e emojis em uma página HTML, utilizando entidades de caracteres.

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
