# Imagem

A tag usada para colocar uma imagem é a tag "<img>". A tag "<img>" não possui tag de fechamento.

# Maneiras de se usar uma imagem
Tem duas maneiras:
- Caminho relativo: ele é um caminho que começa no diretorio do arquivo HTML.
- Caminho absoluto: Adicionanado uma url de um site.

Algumas imagens possuem direitos autorais, ent para isso, é bom usar o site https://unsplash.com/pt-br

# Atributos da tag "<img>"
- <src> : Essa tag é usada para colocar a imagem que você deseja, usando o metode de url.
EX: 
"src="https://edube.org/uploads/media/default/0001/03/mountain_landscape.jpg""

- <alt> : Essa tag é usada para adicionar uma descrição da imagem colocada para erros de carregamento da imagens e para deficientes visuais.
EX:
"alt="Mountain landscape""

- <width> : Essa tag é usada para definir a largura da imagem. Ela pode ser definida em pixels (ex.: width="340") ou como porcentagem (ex.: width="50%").

- <height> : Essa tag é semelhante a tag "<width>", ela define a altura da imagem. Ela pode ser definida como pixels (ex.: width="340") ou como porcentagem (ex.: width="50%").

# Imagens responsivas

Para criar imagens responsivas em HTML, pode ser usado o "srcset" e "sizes".

- srcset : Pode especificar uma lista de arquivos de imagem com diferentes resoluções, tamanhos e formatos.

- sizes: pode especificar o tamanho do contêiner de imagens no qual a imagem será exibida.
EX:
"<img src=sunflowers.jpg"
     alt="Sunflowers in the sunset"
     srcset="sunflowers-small.jpg 480w, Essas são as imagens que seram  definidas para cada tamanho
             sunflowers-medium.jpg 800w,
             sunflowers-large.jpg 1200w"
     sizes="(max-width: 480px) 95vw,
            (max-width: 800px) 45vw,
            30vw">" Mudando esse ponto, ele pode mudar a porcentagem da imagem na tela, e de acordo com isso, ele pega umas das imagens definidas mais proxima a esse tamanho

# Outros atributos
Todos esses atributos podem ser usados dentro desse codigo acima

- border: adicionar essa tag, terá uma borda em volta de toda a imagem. Esse numero é para definir a grossura da borda.
EX:
"<img src="example.jpg" alt="Example image" border="2">"

- hspace e vspace: O "hspace" serve para criar espaçamentos na horizontal e o "vspace" um espaçamento na vertical.
EX:
"<img src="example.jpg" alt="Example image" hspace="10" vspace="10">"

- align: Permite alinhar um imagem em relação ao conteudo ao redor, usando valores ,como, left, right e center.
Ex:
"<img src="example.jpg" alt="Example image" align="left">"
