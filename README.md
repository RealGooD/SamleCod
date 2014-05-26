<!DOCTYPE html>
<html>
<head>
    <title>Здоровый образ жизни</title>
    <meta charset="utf=8">
    <style type="text/css">

    body {
    background: url("../images/bgGrl.jpg") #EAEAEA no-repeat center top fixed; /* Альтернатива всем Бэкграундам */
    margin: 0; /* Отступ внутри */
    padding: 0; /* Отступ вне */

}

a {
    color: #333; /* Цвет ссылок */
}

#page_align {
    font-family: Arial, Calibri, Tahoma;
    font-size: 14px;
    color: #333;
    width: 990px;
    height: 520px;
    background: rgba(255,255,255,0.4); /* Прозрачность */
    margin: 50px auto;
    border-radius: 5px; /* Закругленный контент */
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px; /* Для отображения в Mozila */
    box-shadow: 0px 2px 5px rgba(0,0,0,0.3); /* Тень */
}

#header {
    width: 990px;
    height: 35px;
    background: #cdeb8e;
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2NkZWI4ZSIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiNhNWM5NTYiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
    background: -moz-linear-gradient(top,  #cdeb8e 0%, #a5c956 100%);
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#cdeb8e), color-stop(100%,#a5c956));
    background: -webkit-linear-gradient(top,  #cdeb8e 0%,#a5c956 100%);
    background: -o-linear-gradient(top,  #cdeb8e 0%,#a5c956 100%);
    background: -ms-linear-gradient(top,  #cdeb8e 0%,#a5c956 100%);
    background: linear-gradient(to bottom,  #cdeb8e 0%,#a5c956 100%);
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#cdeb8e', endColorstr='#a5c956',GradientType=0 );
    border-top-left-radius: 5px;
    -webkit-border-top-left-radius: 5px;
    border-bottom: 1px solid #6DBA4C;
    overflow: hidden;
}

#header ul {
    list-style: none; /* Убирает точки */
    float: left;
    margin: 0;
    padding: 0;
}

#header ul li {
    float: left;
}

#header ul li a{
    text-decoration: none; /* Убрать подчеркивание */
    padding: 0px 10px;
    line-height: 35px; /* Ширина между пунктами */
    height: 35px;
    display: block; /* Ссылка на все пространство */
}

#header ul li a:hover { /* Все изменения при наведение на ссылку */
    background: rgba(0,0,0,0.1);
    color: #FFF;
    text-shadow: 1px 1px 0px #60BA4C;
}

#img h1 {
    margin: 0px;
    padding: 0px;
    font-size: 20px; /* Размер шрифта */
    margin-left: 310px;
    border-bottom: none /* Подчеркивание снизу текста */
    margin-right: 10px;
    margin-bottom: 5px;
    padding-bottom: 3px; /* Отступ от текста к подчеркивающей линии */
}

#img p {
    margin-left: 310px;
    margin-right: 10px;
}

#img {
    margin-left: 10px;
    margin-top: 10px;
    position: relative;
}

#img span {
    position: absolute;
    bottom: 2px;
    background: rgba(0,0,0,0.5);
    color: #FFF;
    width: 300px;
    line-height: 30px;
    padding-left: 5px;
}

.img {
    border-radius: 5px;
    box-shadow: 0px 1px 3px rgba(0,0,0,0,2);
    float: left; /* Обтекаемость элемента */
    overflow: hidden;
}
.clr { /* Убирает background основного контента, при удалении высоты */
    clear: both;
}
input[name="name"] {  /*поле формы*/
    margin-left: 10px;
    height: 30px;
    width: 300px;
    border-radius: 3px;
    border: solid 1px #666;
    box-shadow: none;
    transition: all 0.2s ease-in-out;
    -webkit-transition: all 0.2s ease-in-out;
}
input[name="name"]:focus { /*поле формы*/
    outline: none;
    box-shadow: 0px 0px 9px blue; /*фокус Hrome*/
}
h2 {
    font-style: italic;
    font-style: oblique;

}
.text {
    margin-left: 285px;
}
h2 {
    margin-left: 312px;
}
footer {
    background: #cdeb8e;
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2NkZWI4ZSIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiNhNWM5NTYiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
    background: -moz-linear-gradient(top,  #cdeb8e 0%, #a5c956 100%);
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#cdeb8e), color-stop(100%,#a5c956));
    background: -webkit-linear-gradient(top,  #cdeb8e 0%,#a5c956 100%);
    background: -o-linear-gradient(top,  #cdeb8e 0%,#a5c956 100%);
    background: -ms-linear-gradient(top,  #cdeb8e 0%,#a5c956 100%);
    background: linear-gradient(to bottom,  #cdeb8e 0%,#a5c956 100%);
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#cdeb8e', endColorstr='#a5c956',GradientType=0 );
    text-align: center;
}

    </style>
    </head>
<body>
    <div id="page_align">
        <div id="header">
            <ul>
                <li><a href="regPit.html">Здоровое питание</a></li>
                <li><a href="fizAkt.html">Физическая активность</a></li>
                <li><a href="ciklTrenVes.html">Циклическая тренировка весом</a></li>
                <li><a href="komplYpr.html">Комплекс упражнений за 7 минут</a></li>
            </ul>
        </div>
        <div id="img">
            <a href="http://tti.sfedu.ru/" target="_blank"><img src="images/YFY.JPG" class="img"></a>
            <h1>Здоровый образ жизни</h1>
                <p>Здоровый образ жизни (ЗОЖ) - это образ жизни, основан­ный на принципах нравственности, рационально
                    организованный, активный, трудовой, закаливающий и, в то же время, защищаю­щий от неблагоприятных
                    воздействий окружающей среды, позво­ляющий до глубокой старости сохранять нравственное, психиче­ское
                    и физическое здоровье.
                    Здоровый образ жизни отражает  направлен на укрепление адаптивных возможностей организма,
                    полноценную самореализацию своих сущностных сил, дарований и способностей в общекультурном и
                    профессиональном развитии, жизнедеятельности в целом. Он создает для личности такую социокультурную
                    микросреду, в условиях которой возникают реальные предпосылки для высокой творческой самоотдачи,
                    работоспособности, трудовой и общественной активности, психологического комфорта, наиболее полно
                    раскрывается психофизиологический потенциал личности, актуализируется процесс ее
                    самосовершенствования.
                    На страницах этого сайта мы затронем такие аспекты здорового образа жизни как:</p>
                    <ul class="text">
                        <li><a href="regPit.html">здоровое питание;</a></li>
                        <li><a href="fizAkt.html">Физическая активность.</a></li>
                    </ul>
                    <h2>Дополнительные материалы по теме</h2>

                    <p><a href="http://www.takzdorovo.ru">1. Премия рунета 2010, лучший интернет-проект о здоровье и отдыхе</a></p>
                    <p><a href="http://www.zdorovajaplaneta.ru/zdorovyj-obraz-zhizni-zozh/">2. Международное общественное движение "Здоровая планета"</a></p>
                    <p><a href="http://ru.wikipedia.org/wiki/Здоровый_образ_жизни">3. ЗОЖ (википедия)</a></p>
            <footer>
                Таганрог, 2014. Наполнение: асс. кафедры <a href="http://eim.sfedu.ru/">ЭиМ</a> Береснев М.А., дизайн: Волков Михаил (d900w@mail.ru)
            </footer>
        </div>
    </div>

    <div class="clr"></div>

</body>
</html>
