# Portfolio
<html>
<head>
 <title>Заголовок сайта</title>
 <style>
   .line {
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
   }
  .container {
   width: 100%;
   max-width: 1024px;
   padding: 15px;
   margin: 0 auto;
   display: -webkit-flex;
   display: -ms-flexbox;
   display: flex;
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
  button {
   display: block; 
   margin: 0 auto;
  }
  .container div {
   float: left;
   margin-bottom: 15px;
  }
  .col-1-2 {
   width: 50%; 
  }
  .col-1-3 {
   width: 33.3333333333%;
  }
  .col-1-4 {
   width: 25%;
  }
  .col-1-6 {
   width: 16.666666667%;
  }
  .col-2-3 {
   width: 66.6666666667%;
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
  <div class='line'>
   <div class='container'>
    <div class="col-1-6"><img src='https://www.pngplay.com/wp-content/uploads/12/Internet-Explorer-Transparent-File.png' alt='LOGO' align='middle'/ width=100%></div>
    <div class="col-1-2"><h1 align='center'>Создание сайтов и лендингов</h1></div>
    <div class="col-1-3">
     Надежда Самойлова <br>
     <a href='mailto:nadezhda.v.samoylova@gmail.com'>nadezhda.v.samoylova@gmail.com</a><br>
     <a href='tel:+7(905)2708717'>+7(905)2708717</a>
    </div>
   </div>
  </div>
  <div class='line'>
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
 <div class='line'>
  <div class='container'>
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
      <li>покажет все лучшие качества вашего продукта</li>
      <li>будет одинаково хорошо выглядеть и на компьютере, и на смартфоне</li>
      <li>будет отправлять в вашу CRM заявки от ваших потенциальных клиентов</li>
     </ul>
     <br><br>
     <button>Заказать предварительный расчет</button>
     <br><br>
    </div>
   </div>
  </div>
  <h2 align='center' width=100%>Почему мне можно доверять</h2>
  <div class='line'>
  <div class='container'>
    <div class="col-1-3">
     <img src='' alt='Программирование'>
     <p>Опыт администрирования сайтов, SEO-оптимизации, настройки рекламы, интеграции с CRM<br><br>Готова помочь решить большой спектр задач бизнеса клиента</p>
    </div>
    <div class="col-1-3">
     <img src='' alt='Образование'>
     <p>Образование в сфере программирования, менеджмента, предпринимательства и финансов<br><br>Профессиональный подход и ответственность</p>
    </div>
    <div class="col-1-3">
     <img src='' alt='Бизнес'>
     <p>15 лет управляю собственным бизнесом, в штате 40+ человек <br><br> Прекрасно понимаю клиентов и помогаю им достигать лучших результатов</p>
    </div>
   </div>
   </div>
  </div>
  <div class='line'>
  <div class='container'>
    <div class="col-1-4">четверть</div>
    <div class="col-1-4">четверть</div>
    <div class="col-1-2">половина</div>
   </div>
  </div>
 </div>
 <footer>
 <div class='line'>
  <div class='container'>
    <div class="col-1-3">треть</div>
    <div class="col-1-3">треть</div>
    <div class="col-1-3">треть</div>
  </div>
 </footer>
</body>
</html>
