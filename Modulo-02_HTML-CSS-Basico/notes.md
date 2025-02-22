
### Anatomia Tag

# **Tag**

- As tag's (etiquetas) servem para marcarmos o conteúdo no HTML. Geralmente abrimos <a> e fechamos </a> após o conteúdo.
- Case insensitive, mas é boa prática escrever com minúsculas <html>.

**Semântica**

- Dar sentido ao conteúdo, a escrita de um documento semântico beneficia principalmente leitores de tela (acessibilidade) e leitores de códigos (robôs como o do Google).

- Interação com CSS e JavaScript

- Através das marcações das tags que conseguimos selecionar elementos para mudarmos o seu estilo ou comportamento.


# **Tags Iniciais**

<p> - Marca um parágrafo.

<h1>, <h2>, <h3>, <h4>, <h5>, <h6> - Marcam diferentes níveis de títulos.

<a> - Marca um link.

Podemos usar uma tag dentro da outra:
<p>Entre no meu site: <a href="https://www.origamid.com">origamid.com</a></p>

# **Estrutura HTML** 

<!DOCTYPE html> - Indica o tipo de documento (html, xhtml e outros)

<html> -Representa a raiz do documento, é a tag que envolve todo o documento.

<head> - Informações gerais para o browser. Título, descrição e outras.

<title> - Título do documento.

<meta> - Dados extras sobre o documento.

<body> - Conteúdo do site, aqui escrevemos toda a estrutura do documento.

Exemplo da estrutura completa: 

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Título da Página</title>
  </head>
  <body>
    <h1>Curso de HTML</h1>
  </body>
</html>

# **Caminho (path)** 

**Absoluto**

<a href="https://www.origamid.com/cursos/">Origamid Cursos</a> - Usado para arquivos externos ao nosso site.

**Relativo**

<a href="/produtos/bicicletas.html">Bicicletas</a> - Usado para arquivos internos do site.

# **Seletores**

- Exemplo p/ css estilizar os elemtos html

h1, p{

}

- A vírgula permite selecionarmos múltiplos elementos para a aplicação de um mesmo estilo.

p a{

}

- Seleciona o a que tiver um p como elemento pai (não precisa ser filho direto).

Atributo HTML que adiciona um identificador único na tag. Esse identificar pode ser utilizado no CSS para selecionarmos o elemento: #nomeid

**class**

Atributo HTML que adiciona um identificador reutilizável na tag. Esse identificar pode ser utilizado no CSS para selecionarmos o(s) elemento(s): .classe

<h1 class="logo">oi</h1>

//No CSS

.logo{

}

**id**
Atributo HTML que adiciona um identificador único na tag. Esse identificar pode ser utilizado no CSS para selecionarmos o elemento: #nomeid

<h1 id="logo">oi</h1>

//No CSS

#logo{
}


