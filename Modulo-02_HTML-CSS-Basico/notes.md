
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


# **Background**

background ou background-color - Muda a cor de fundo do elemento.

**hexadecimal**

A cor é representada através de um código de 6 caracteres que vão de 0 até F.

#84e = #8844ee


**rgba**

rgba(0, 0, 0, 1);

O rgba é uma função que recebe os valores de r (red), g (green), b (blue) e a (alpha). O rgb vai de 0 até 255 e o alpha vai de 0 até 1.

Existe tbm a rgb, que tira a parte de opacidade do a (alpha). 


# **Box Model**

Content (conteúdo) - Define a largura inicial da caixa (salvo elementos de bloco).

Padding (preenchimento) - Separa o conteúdo das bordas da caixa. É a margem interna.

Border (borda) - Define bordas para a caixa.

Margin (margem) - Define a distância entre uma caixa e outra.

Width (largura) - A largura total da caixa, por padrão é o somatório do conteúdo + padding (left/right) + border (left/right).

Height (altura)- A altura total da caixa, por padrão é o somatório do conteúdo + padding (top/bottom) + border (top/bottom).

Pixel - É a unidade de referência da Web, pois as telas são desenvolvidas em pixels.

- Um monitor de: 3840 (largura em px) x 2160 (altura em px) = 8.294.400.
- No CSS o pixel (px) é uma unidade de referência e não representa 1 pixel exato do seu dispositivo (é adaptável em relação à densidade da tela).

A <div> é um elemento de bloco block genérico que serve para auxiliar no posicionamento dos elementos/conteúdo na tela.

Existem também elementos semânticos como main, section, nav e outros que veremos em outras aulas.

# **Documentação**

- Existem centenas de tags e propriedades, é quase impossível você gravar todas elas. Por isso consultamos uma documentação.

- Mozilla
https://developer.mozilla.org/en-US/docs/Web/HTML/Element
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

- W3C
https://www.w3.org/TR/



