<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>animation</title>
<link rel="stylesheet" href="styles.css">
<bgsound src="background.mp3" loop="1" volume="1" balance="0" />
</head>
<body>

<div class="body"></div>


</body>
</html>

<style>
body {
/* задает путь до файла */
background-image: url("gifка.gif");
/* задает стартовое положение изображения на странице */
background-position: center center;
/* определяет размер изображения на странице */
background-size: cover;
/* свойство устанавливает, будет ли повторяться изображение и каким образом */
background-repeat: no-repeat;
/* свойство определяет, будет ли фоновое изображение прокручиваться вместе с остальной частью страницы или будет фиксированным */
background-attachment: fixed;

/* возможна также и короткая запись данных свойств */
/* background: url("gifка.gif") center center no-repeat fixed; */
/* background-size: cover; */
}
</style>
