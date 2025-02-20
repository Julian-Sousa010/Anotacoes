# CAPITULO 19 - Imagens De Fundo

## 1. Adicionando Imagens em um Fundo:

- `background-image: url("valor");`

## 2. Quando a imagem e menor do que o background ela e repetida ate preencher o espaco do background do conteiner:


```
background-repeat: no-repeat;

background-repeat: repeat;

background-repeat: repeat-y;

background-repeat: repeat-x;
```

<img src="PREENCHIMENTO DO BACKGROUND.png">

## 3. Posição De Inicio das Repetições:

- `background-position: valor;`

Padrão: `left top;`

<img src="REFERENCIA DE INICIO DE REPETIÇÃO.png">

 ## 4. Tamanho Da Imagem De Fundo:

- `background-size: valor;`

 -  `auto `{Padrao}: A imagem sera aplicada no Fundo no seu tamanho Original.
 -  `[lenght]px` ou `[lenght]% `: Redimensiona a Largura da Imagem e adapta a Altura automaticamente, Largura e Altura podem ser inseridos manualmente tanto px ou porcentagem.
 - `cover`: Define o tamanho da imagem para que ela seja sempre exibida na tela, sem nenhum corte.
 - `contain`: Redimensiona a imagem para que ela cubra o contêiner, mesmo que para isso ocorram alguns eventuais cortes.

 <img src="VALORES BACKGROUND-SIZE.png">

## 5. Comportamento Imagens De Fundo:

- `background-attachment: valor;`

`scroll` (Padrão): A imagen de fundo vai rolar com o conteudo.
`fixed`: A imagen de fundo vai ficar fixa enquanto o conteudo e rolado.

## 6. ShortHand Background:

``` 
background-color: blue;

background-image: url(caminho da imagem);

background-position: center center;

background-repeat: no-repeat;

background-attachment: fixed;
```

Exemplo:

- `background: green url(image.png) left top no-repeat scroll;`

## 7. Centralização Vertical em Conteineres:

```
position: absolute;

left: 50%;

top: 50%;

transform: translate(-50%, -50%);
```
