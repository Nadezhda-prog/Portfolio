# Portfolio
<html>
<head>
 <title>Заголовок сайта</title>
 <style>
  .container {
   width: 100%;
   max-width: 1024px;
   padding: 15px;
   margin: 0 auto;
  }
  .logo {
   float: left;
   padding: 0 25px;
  }
  nav {
   float: right;
  }
  nav a {
   text-decoration:none;
   line-height: 30px
  }
  nav ul {
   margin:0;
   padding:0;
   list-style:none;
  }
  nav li {
   display: inline-block;
   padding: 0 10px;
  }
  .container div {
   float: left;
   margin-bottom: 15px;
   <!--height: 100px;--!>
  }
  .col-1-2 {
   width: 50%; 
   background-color: #FFff00;
  }
  .col-1-3 {
   width: 33.3333333333%;
   background-color: #FFA500;
  }
  .col-1-4 {
   width: 25%;
   background-color: #FFA5ff;
  }
  .col-1-6 {
   width: 16.666666667%;
   background-color: #FFA5ff;
  }
  .col-2-3 {
   width: 66.6666666667%;
   background-color: #00FF00;
  }
  .container:after {
   content: "";
   display: table;
   clear: both;
  }
  .carousel {
   position: relative;
   width: 100%;
   overflow: hidden;
  }
  .carousel-inner {
   display: flex;
   width: 300%;
   transition: transform 0.5s;
  }
  .carousel-item {
   flex: 1;
   text-align: center;
  }
  .carousel-item img {
   width: 100%;
   max-height: 400px;
   object-fit: cover;
  }
 </style>
</head>
<body>
 <header>
  <div class='container'>
   <div class="col-1-6"><img src='https://www.pngplay.com/wp-content/uploads/12/Internet-Explorer-Transparent-File.png' alt='LOGO' align='middle'/ width=100%></div>
   <div class="col-1-2"><h1 align='center'>Пример сайта</h1></div>
   <div class="col-1-3">
    Надежда Самойлова <br>
    <a href='mailto:nadezhda.v.samoylova@gmail.com'>nadezhda.v.samoylova@gmail.com</a><br>
    <a href='tel:+7(905)2708717'>+7(905)2708717</a>
   </div>
   <nav>
    <ul>
     <li><a href=''>1 пункт меню</a></li>
     <li><a href=''>2 пункт меню</a></li>
     <li><a href=''>3 пункт меню</a></li>
    </ul>
    <nav>
  </div>
 </header>
 <div class=main>
  <div class='container'>
   <br><br>
   <div class="col-1-2">
    <div class="carousel">
     <div class="carousel-inner">
      <div class="carousel-item">
       <img src='https://sun9-28.userapi.com/impg/B9dLEmJbXlXveT3uw4SqIyT7_JOURO9-PvL9EA/rIWXIaaooqY.jpg?size=1379x980&quality=96&sign=b6b6dd398139fbadd99a9dd635f66949&c_uniq_tag=qQfJJRiXWnXo1dBuXtmP2WAoFB5RnWNEJ1mj6A3VXxE&type=album' alt='Адаптивный дизайн'>
      </div>
      <div class="carousel-item">
       <img src="https://hozyindachi.ru/wp-content/uploads/2022/09/glavnaya-stranica-sajta-foto.jpg" alt="Современный сайт">
      </div>
      <div class="carousel-item">
       <img src="https://avatars.mds.yandex.net/i?id=00109fd94b53c12d0d56aac61c821339_l-10703717-images-thumbs&n=13" alt="Менеджеры общаются с клиентами">
      </div>
     </div>
    </div>
   </div>
   <div class="col-1-2">
    Я готова сделать для вас сайт, который:
    <ul>
     <li>показывает все лучшие качества вашего продукта</li>
     <li>одинаково хорошо выглядит и на компьютере, и на смартфоне</li>
     <li>собирает заявки от потенциальных клиентов и отправляет их в вашу CRM</li>
   </div>
   <div class="col-1-2">половина</div>
   <div class="col-1-2">половина</div>
   <div class="col-1-4">четверть</div>
   <div class="col-1-4">четверть</div>
   <div class="col-1-2">половина</div>
  </div>
 </div>
 <footer>
  <div class='container'>
    <div class="col-1-3">треть</div>
    <div class="col-1-3">треть</div>
    <div class="col-1-3">треть</div>
  </div>
 </footer>
</body>
</html>
