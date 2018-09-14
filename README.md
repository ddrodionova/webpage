# webpage
# webpage
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Личная страница Родионовы Дарьи</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
  body {
      font: 20px Montserrat, sans-serif;
      line-height: 1.8;
      color: #f5f6f7;
  }
  p {font-size: 16px;}
  .margin {margin-bottom: 45px;}
  .bg-1 {
      background-color: #001a43; /* Dark Blue */
      color: #ffffff;
  }
  .bg-2 {
      background-color: #000000; /* Black */
      color: #ffffff;
  }
  .bg-3 {
      background-color: #ffffff; /* White */
      color: #555555;
  }
  .bg-4 {
      background-color: #2f2f2f; /* Black Gray */
      color: #fff;
  }
  .container-fluid {
      padding-top: 70px;
      padding-bottom: 70px;
  }
  .navbar {
      padding-top: 15px;
      padding-bottom: 15px;
      border: 0;
      border-radius: 0;
      margin-bottom: 0;
      font-size: 12px;
      letter-spacing: 5px;
  }
  .navbar-nav  li a:hover {
      color: #1abc9c !important;
  }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-default">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">Me</a>
  </div>
</nav>

<!-- Первый раздел -->
<div class="container-fluid bg-1 text-center">
  <h3 class="margin">Кто я?</h3>
  <img src="https://github.com/ddrodionova/webpage/blob/gh-pages/FullSizeRender-14-09-18-10-21.jpg.jpg" class="img-responsive img-circle margin" style="display:inline" width="350" height="350">
  <h3>Я - Родионова Дарья r</h3>
</div>

<!-- Второй раздел -->
<div class="container-fluid bg-2 text-center">
  <h3 class="margin">Обо мне</h3>
  <p>Студентка Школы Лингвистики. Люблю искусство во всех его проявлениях, могу рассказать о любой архитектурной эпохе. Читаю на трёх языках, также в моём арсенале иметются 397, если быть точной, просмотренных фильма, и ещё примерно тысяча, о которых могу притвориться, будто смотрела. Знакома почти с каждым жанром музыки и могу предложить интересные книжечки. </p>
  <a href="#" class="btn btn-default btn-lg">
    <span class="glyphicon glyphicon-search"></span> Search
  </a>
</div>

<!-- Третий раздел -->
<div class="container-fluid bg-3 text-center">    
  <h3 class="margin">Мои контакты</h3><br>
  <div class="row">
    <div class="col-sm-4">
      <a href="https://vk.com/id322256847">
      Вконтакте </a>
    </div>
  </div>
</div>


</body>
</html>
