# Lista de Exercícios – HTML

## 1. O que é HTML?

HTML (_HyperText Markup Language_) é a linguagem de marcação usada para estruturar páginas da web. Ele organiza o conteúdo usando elementos e tags, sendo essencial para a construção de sites.

## 2. Estrutura do HTML

A estrutura básica de um documento HTML é:

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <title>Minha Página</title>
  </head>
  <body>
    <h1>Bem-vindo ao meu site</h1>
    <p>Este é um exemplo básico de HTML.</p>
  </body>
</html>
```

## 3. Diferença entre HTML e HTML5

1. HTML5 introduziu tags semânticas como `<article>`, `<section>` e `<header>`.
2. Suporte nativo para áudio e vídeo com `<audio>` e `<video>`.
3. Melhor compatibilidade com dispositivos móveis e APIs como Geolocalização e Canvas.

## 4. Elementos e Atributos

Os elementos HTML são componentes de uma página web, e os atributos fornecem informações adicionais. Exemplo:

```html
<img src="imagem.jpg" alt="Descrição da imagem" />
```

Aqui, `src` é um atributo que define a fonte da imagem, e `alt` fornece um texto alternativo.

## 5. Listas em HTML

- `<ul>` (lista não ordenada) → Usada para itens sem hierarquia.
- `<ol>` (lista ordenada) → Itens numerados ou ordenados.
- `<dl>` (lista de definição) → Usada para termos e descrições.

Exemplo:

```html
<ul>
  <li>Maçã</li>
  <li>Banana</li>
</ul>
```

## 6. Tags Semânticas

São tags que atribuem significado ao conteúdo:

- `<article>` → Representa um artigo independente.
- `<section>` → Define uma seção genérica do documento.
- `<header>` → Cabeçalho de uma página ou seção.

## 7. Formulários HTML

Principais elementos:

- `<input type="text">` → Entrada de texto.
- `<input type="email">` → Campo de email.
- `<input type="password">` → Campo de senha.
- `<textarea>` → Caixa de texto multilinhas.
- `<button>` → Botão interativo.

## 8. Links e Âncoras

- **Link absoluto**: Redireciona para um site externo.

```html
<a href="https://www.google.com">Google</a>
```

- **Link relativo**: Direciona para uma página interna.

```html
<a href="sobre.html">Sobre nós</a>
```

## 9. Meta Tags

São usadas no `<head>` para metadados. Exemplos:

```html
<meta charset="UTF-8" />
<meta name="description" content="Página sobre tecnologia" />
```

## 10. Áudio e Vídeo

Para incorporar multimídia:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg" />
</audio>

<video controls>
  <source src="video.mp4" type="video/mp4" />
</video>
```

Compatibilidade pode ser garantida adicionando múltiplos formatos de arquivos.

## 11. Criando um Documento HTML

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <title>Minha Primeira Página</title>
  </head>
  <body>
    <h1>Bem-vindo ao meu site</h1>
    <p>Este é um exemplo básico de HTML.</p>
  </body>
</html>
```

## 12. Trabalhando com Imagens

```html
<img src="foto.jpg" alt="Foto de uma paisagem" />
```

O atributo `alt` melhora a acessibilidade e SEO.

## 13. Criando Listas

```html
<ol>
  <li>São Paulo</li>
  <li>Rio de Janeiro</li>
  <li>Belo Horizonte</li>
</ol>

<ul>
  <li>Pizza</li>
  <li>Hambúrguer</li>
  <li>Sorvete</li>
</ul>
```

## 14. Criando Tabelas

```html
<table border="1">
  <tr>
    <th>Produto</th>
    <th>Preço</th>
    <th>Estoque</th>
  </tr>
  <tr>
    <td>Celular</td>
    <td>R$ 2.500</td>
    <td>10</td>
  </tr>
</table>
```

## 15. Criando Links Internos e Externos

```html
<a href="https://www.google.com">Google</a>
<a href="#sobre">Ir para a seção Sobre</a>
<h2 id="sobre">Sobre</h2>
```

## 16. Criando um Formulário

```html
<form>
  <label>Nome: <input type="text" name="nome" /></label>
  <label>Email: <input type="email" name="email" /></label>
  <label>Senha: <input type="password" name="senha" /></label>
  <button type="submit">Enviar</button>
</form>
```

## 17. Incorporando um Vídeo

```html
<video controls>
  <source src="video.mp4" type="video/mp4" />
</video>
```

## 18. Criando um Layout Simples

```html
<header>
  <h1>Meu Site</h1>
</header>
<nav>
  <a href="#">Home</a>
  <a href="#">Contato</a>
</nav>
<main>
  <p>Conteúdo principal</p>
</main>
<footer>
  <p>Rodapé</p>
</footer>
```

## 19. Formulário com Caixa de Seleção e Radio Button

```html
<form>
  <label
    >Escolha uma cor:
    <select>
      <option>Vermelho</option>
      <option>Azul</option>
      <option>Verde</option>
    </select>
  </label>

  <label><input type="radio" name="opcao" value="sim" /> Sim</label>
  <label><input type="radio" name="opcao" value="não" /> Não</label>

  <button type="submit">Enviar</button>
</form>
```

## 20. Criando uma Página Completa

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <title>Meu Site Completo</title>
  </head>
  <body>
    <header>
      <h1>Meu Site</h1>
    </header>

    <img src="imagem.jpg" alt="Imagem principal" />

    <p>
      Bem-vindo ao meu site! Aqui você encontra diversos conteúdos
      interessantes.
    </p>

    <ul>
      <li>Notícias</li>
      <li>Artigos</li>
      <li>Tutoriais</li>
    </ul>

    <form>
      <label>Nome: <input type="text" /></label>
      <label>Email: <input type="email" /></label>
      <button type="submit">Enviar</button>
    </form>

    <footer>
      <p>&copy; 2025 Meu Site</p>
    </footer>
  </body>
</html>
```
