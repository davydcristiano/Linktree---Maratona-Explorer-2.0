Linktree - Maratona Explorer 2.0
===

Nessa maratona foi desenvolvido um social link como o linktree, totalmente funcional e customizado.

<img src="https://user-images.githubusercontent.com/53920878/177476767-0249d60e-d868-4b53-a71a-ec14a6707a19.png" width="100%" alt="Imagem do Projeto">

## Papar Information
- Title:  `Linktree - Bootstrap 4.0`
- Author:  `Davyd Cristiano`
- Project: `Linktree - Maratona Explorer 2.0 - Rocketseat!`
- Full-Print:
- <img src="https://user-images.githubusercontent.com/53920878/177658870-9fb97e69-3cbb-49ca-94ba-0433ce611ea4.PNG" width="80%" alt="Imagem ilustrativa do Projeto">

## Linguagens
- HTML5 - Hyper Text Marckup Language
- CSS3 - Cascading Style Sheet
- Bootstrap - Frameworking Front-End

## Directory Hierarchy
```
|—— Assets
|    |—— image
|        |—— background01.jpg
|        |—— background02.png
|        |—— BackgroundGradient.gif
|    |—— svg
|        |—— build.svg
|—— css
|    |—— bootstrap-grid.min.css
|    |—— style.css
|—— index.html
|—— js
|    |—— bootstrap.bundle.min.js
|    |—— jquery-3.6.0.min.js
```
## HTML5 Details
```
<!doctype html>
<html lang="pt-br">
  <head>
    <title>Davyd Cristiano Linktree</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="description" content="Davyd Cristiano, Linktree">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="theme-color" content="#ffffff">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap-grid.min.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono&family=Roboto:wght@500;700&display=swap" rel="stylesheet">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/Assets/favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/Assets/favicon/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
    <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
  </head>
  <body>
      <div class="container-fluid">
        <div class="image">
        <img src="https://github.com/davydcristiano.png" class="img-fluid" alt="Responsive image"></div>

        <h1>Davyd Cristiano</h1>
        <p>DESENVOLVEDOR FRONT-END <br> HTML | CSS | JS |</p>
        <br>
        <ul>
            <li><a class="btn" href="https://www.youtube.com/channel/UCDn5q_9DMH2xiu1tSxBLIMA" alt="Botão Youtube" target="_blank"><p>🎬 Youtube</p></a></li>
            
            <li><a class="btn" href="https://www.instagram.com/davyd_cristiano/" alt="Botão Instagram" target="_blank"><p>📷 Instagram</p></a></li>

            <li><a class="btn" href="https://www.linkedin.com/in/davyd-cristiano-b41b5b99/" alt="Botão Linkedin" target="_blank"><p>📘 Linkedin</p></a></li>

            <li><a class="btn" href="https://github.com/davydcristiano" alt="Botão Github" target="_blank"><p>🐱 Github</p></a></li>

        </ul>
        <div id="footer">
        <footer>Desenvolvido por Davyd Cristiano</a></footer></div>
      </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="js/jquery-3.6.0.min.js"></script>
    <script src="js/bootstrap.bundle.min.js"></script>
  </body>
</html>
```

## CSS3 Details
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    overflow-x: hidden;
    font-family: 'Roboto', sans-serif;
    font-family: 'Roboto Mono', monospace;
}

a {
    text-decoration: none;
}

body {
    width: 100%;
    height: 100vh;
    display: flex;
    font-family: 'Roboto', sans-serif;
    background-image: url(/Assets/image/BackgroundGradient.gif);
    background-repeat: no-repeat;
    background-size: cover;

}

.container-fluid {
    width: 500px;
    text-align: center;
    margin: 60px auto;
    background-color: #1212140a;
    box-shadow: 0.5px 0.5px 35px 0.5px #2f2f3084;
    border-radius: 20px;
}

.img-fluid {
    width: 40%;
    padding: 3px;
    border-radius: 50%;
    color: #00000048;
    padding: 5px;
    border: 6px solid;
    margin-top: 16px;
}

h1 {
    color: rgba(0, 0, 0, 0.748);
    font-size: 40px;
    margin-top: 5px;
    line-height: 50px;
    font-family: 'Roboto', sans-serif;
}

p {
    color: #ffffff80;
    margin-top: 10px;
    font-size: 20px;
    font-family: 'Arial', sans-serif;
}

ul li a p {
    color: rgba(255, 255, 255, 0.641);
    display: flex;
    align-items: center;
    justify-content: center;
}

.btn {
    width: 100%;
    color: #00000053;
    background-color: #0000002c;
    padding: 16px 80px;
    margin-top: 12px;
    display: inline-block;
    border-radius: 10px;
    border: 3px solid;
    border-style: 3px #fff;
    box-shadow: inset 0px 0px 0px rgba(60, 0, 255, 0.752);
    transition: ease-out 0.3s;
    outline: none;
}

.btn:hover {
    box-shadow: inset 600px 0 0 0 #4d5cfb;
    background-color: #223094;
    cursor: pointer;
    color:rgb(0, 0, 0);
}

#footer {
    color:#ffffff;
    font-weight: 500;
    font-size: 12px;
    opacity: 0.6;
    text-align: center;
    margin-top: 10px;
    margin-bottom: 5px;
}

#footer:hover {
    color:#000000;
    cursor: pointer;
}
```
## Direitos Reservados
```
Title: Linktree - Bootstrap 4.0
Author: Davyd Cristiano
```


