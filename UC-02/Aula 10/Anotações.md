# Atributos Globais
Os atributos globais são aqueles que podem ser adicionados em qualquer elemento HTML. Um exemplo claro disso é a tag "style", mas não tem somente ela, temos também:
- id: Essa tag "id" serve para atribuir um nome para alguma tag. onde você pode puxar esse nome para um arquivo CSS, aplicando os estilo definido para esse nome, antes de colocar o nome d id se coloca um "#".
EX:
"<p id="greeting">Hello, world!</p>
<style>
      #greeting {
        font-size: 24px;
        color: blue;
      }
</style>"

- class: Quase a mesma coisa do arquivo "id", a unica mudança é que em vez de um "#" antes do nome definido, se coloca um ".".
EX:
"<p id="greeting">Hello, world!</p>
<style>
      .greeting {
        font-size: 24px;
        color: blue;
      }
</style>"

- title: Essa tag "title" é adicionada dentro de outra tag, para quando passar o mouse por cima, aparecer um texto.
EX:
"<button type="button" title="Click me for more information">
    Learn More</button>"

- accesskey: Essa tag pode definir um atralho no teclado para ativar um elemento.
EX:
"<button accesskey="s">Salvar</button>"

- dir: Define como o texto será visto.
EX:
"<p dir="ltr">Texto em português.</p>
<p dir="rtl">النص باللغة العربية.</p>"

- translate: Define se o objeto no site será traduzido automaticamente ou não.
EX:
"<p translate="no">OpenAI é o nome da empresa.</p>"

- onclick: Ao clicar no botão executa código JavaScript.
EX:
"<button onclick="alert('Você clicou!')">Clique aqui</button>"

# Atributos de Evento
Os atributos de evento são usados para definir o que vai acontecer com a interação do usuario, como cliques de mouse ou entradas do teclado, como:
- onclick: Executa um script em JavaScript quando o elemento definido é clicado.
EX:
"<button onclick="alert('Você clicou!')">Clique aqui</button>"

- onmouseover: Executa um código em JavaScript quando o cursor do mouse passa por cima do elemento.
EX:
"<p onmouseover="alert('Mouse passou aqui!')">Passe o mouse aqui</p>"

- onmouseout: Executa um script quando o mouse sai de cima do elemento
EX:
"<p onmouseout="alert('Saiu do elemento!')">Passe o mouse aqui e depois tire</p>"

- onkeydown: faz um ação definida quando uma tecla do teclado é pressionada.
EX:
"<input type="text" onkeydown="alert('Tecla pressionada!')">"

- onkeyup: Executa um codigo quando o usuari salta uma tecla do teclado.
EX:
"<input type="text" onkeyup="console.log('Tecla solta!')">"
corrija os erros de portugues e deixe mais bem explicado