# RESTIC36_Desafios
## **Desafio Relâmpago 2 de HTML e CSS**

## Descrição

Temos um segundo código HTML e CSS com alguns erros que precisam ser corrigidos. O objetivo é encontrar e corrigir os 7 erros presentes no código.

## Objetivo

O objetivo deste desafio é aprimorar suas habilidades de identificação e correção de erros em código HTML e CSS. Aprender a detectar e corrigir esses erros é essencial para o desenvolvimento de páginas web funcionais e esteticamente agradáveis. Ao participar deste desafio, você vai:

- Melhorar suas habilidades de revisão de código.
- Desenvolver um olhar crítico para identificar erros comuns.
- Praticar a correção de problemas que afetam a renderização e a usabilidade das páginas web.

## Codigo
~~~html
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <style>
     body {
         font-famly: Arial, sans-serif;
         margin: 0;
         padding: 0;
     }

     #main-header {
         backgroud-color: #f4f4f4;
         padding: 20px;
         text-align: center;
     }

     .flex-container {
         display: flex;
         flex-direction: row;
         justify-content: space-around;
     }

     .flex-item {
         background-color: #e4e4e4;
         padding: 15px;
         margn: 5px;
     }

     .grid-container {
         display: grid;
         grid-template-colums: 1fr 1fr;
         gap: 20px;
     }

     .grid-item {
         background-color: #ccc;
         padding: 20px;
     }

     fotter {
         background-color: #f4f4f4;
         text-align: center;
         padding: 10px;
     }

     h1 {
         color: #333;
     }

     p {
         margin: 0;
     }
 </style>
</head>
<body>
 <header id="main-header">
     <h1>Galeria de Fotos</h1>
 </header>
 <main class="flex-container">
     <section class="flex-item">
         <h2>Imagens em Flexbox</h2>
         <img src="image1.jpg" alt="Imagem 1" />
         <img src="image2.jpg" alt="Imagem 2" />
         <img src="image3.jpg" alt="Imagem 3" />
     </section>
     <section class="grid-container">
         <div class="grid-item">
             <img src="image4.jpg" alt="Imagem 4">
             <p>Descrição da Imagem 4</p>
         </div>
         <div class="grid-item">
             <img src="image5.jpg" alt="Imagem 5">
             <p>Descrição da Imagem 5</p>
         </dv>
         <div class="grid-item">
             <img src="image6.jpg" alt="Imagem 6">
             <p>Descrição da Imagem 6</p>
         </div>
         <div class="grid-item">
             <img src="image7.jpg" alt="Imagem 7">
             <p>Descrição da Imagem 7</p>
         </div>
 </main>
     </section>
 <fotter>
     <p>(c) 2024 Galeria de Fotos</p>
 </fotter>
</body>
</html>
~~~

## Resposta

ERROS:

- Linha 8 - `font-famly: Arial, sans-serif;` - erro de digitação (`font-famly`)
- Linha 14 - `backgroud-color: #f4f4f4;` - erro de digitação (`backgroud-color`)
- Linha 28 - `margn: 5px;` - erro de digitação (`margn`)
- Linha 33 - `grid-template-colums: 1fr 1fr;` - erro de digitação (`grid-template-colums`)
- Linha 42 - `fotter {` - chama a tag escrita errada na linha 87
- Linha 76 - `</dv>` - tag incorreta (deve ser `</div>`)
- Linha 86 - `</section>` - tag escrita após o `</main>`
- Linha 87 - `<fotter>` - erro de digitação (`fotter`)




