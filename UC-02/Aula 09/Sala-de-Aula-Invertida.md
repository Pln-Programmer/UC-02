# Cores
Em HTML, as cores podem ser aplicadas por meio da propriedade color, e o plano de fundo pode ser alterado utilizando a propriedade background-color. Essas propriedades podem ser inseridas utilizando CSS de diferentes formas:

- Estilo interno: O código CSS é inserido dentro da tag <style>, geralmente localizada no cabeçalho do documento (<head>).

- Estilo embutido: O estilo é aplicado diretamente em elementos HTML, utilizando o atributo style.

- Estilo externo: O CSS é colocado em um arquivo separado com extensão .css, que é então vinculado ao HTML por meio da tag <link>.

As cores podem ser definidas utilizando diferentes métodos:

- Por nome: Basta utilizar o nome da cor.
EX:
body {
    color: aqua;
}
- Por código hexadecimal: Utiliza um código composto por seis dígitos (números e letras).
EX:
body {
    color: #ffffff;
}
- Por RGB: Define a cor com base na combinação de vermelho (Red), verde (Green) e azul (Blue).
EX:
body {
    color: rgb(255, 0, 0);
}

# Fontes
As propriedades de fonte são fundamentais para a aparência visual de uma página web. As principais propriedades relacionadas ao estilo da fonte são:

- font-size: Define o tamanho da fonte. Pode ser especificado com valores fixos (como pixels - px) ou valores relativos (como porcentagem - %).
EX:
body {
    font-size: 10px;
}
- font-family: Especifica a família tipográfica a ser utilizada no texto.
EX:
body {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
- font-weight: Define a espessura da fonte (por exemplo, normal, negrito ou valores numéricos como 400, 500, 700).
EX:
body {
    font-weight: 500;
}
- font-style: Define o estilo da fonte, como itálico, normal ou oblíquo.
EX:
body {
    font-style: italic;
}