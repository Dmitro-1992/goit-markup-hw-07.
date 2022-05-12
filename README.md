<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Студия </title>   
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700&display=swap"
    rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css">

 <link rel="stylesheet" href="./css/styles.css">
</head> 
<body> 
   
   <!--Шапка страницы-->
   
    <header class="page-header">
        <div class="container nav-flex">
  <nav class="header-nav"> 
        <a href="./index.html" class="logo">
        <span class="part-logo">Web</span>Studio</a>
      <ul class="site-nav">
          <li class="list"><a href="./index.html" class="link current">Студия</a></li>    
          <li class="list"><a href="./portfolio.html" class="link">Портфолио</a></li>
          <li class="list"><a href="compendium.html" class="link">Контакты </a></li>
      </ul>
    </nav>
        <ul class="text">
            <li class="list"><a class="link" href="malito:info@devstudio.com">
                <svg class="header-icon">
                    <use href="./images/sprite.svg#icon-envelope" width="15" height="16px"></use>
                </svg>
                info@devstudio.com
             </a>
            </li>
            <li class="list"><a class="link" href="tel+380961111111">
                <svg class="header-icon">
                    <use href="./images/sprite.svg#icon-smartphone" width="15px" height="16px"></use>
                </svg>
                +38 096 111 11 11
            </a>
        </li>
        </ul>
    
    </div>
 </header> 
<main> 
            <!--Герой-->

    <section class="hero works">
        <div class="container">
        <h1 class="hero-title">Эффективные решения для вашего бизнеса</h1>
         <button class="button" type="button" data-modal-open>Заказать услугу</button>
    </div>

    </section>
    <!--Задача организации-->
    <section class="section-benefits">
        <!-- <h2 class="">Преимущество</h2> -->
        <div class="container">
        <ul class="list-body">
            <li class="aside">
                <div class="pictures-icon">
                <svg class="animatiol-icon">
                <use href="./images/sprite.svg#icon-antena" width="70"  height="70"></use>
                </svg> 
                </div>  
                <h3>Внимание к деталям</h3>
                <p>Идейные соображения, а также начало повседневной работы по формированию позиции.</p>
            </li>
            <li class="aside">
                <div class="pictures-icon">
                    <svg class="animatiol-icon">
                        <use href="./images/sprite.svg#icon-chasy" width="70" height="70"></use>
                    </svg>
                </div>
                <h3>Пунктуальность</h3>
                <p>Задача организации, в особенности же рамки и место обучения кадров влечет за собой.</p>
            </li>
            <li class="aside">
                <div class="pictures-icon">
                    <svg class="animatiol-icon">
                        <use href="./images/sprite.svg#icon-noutbuk" width="70" height="70"></use>
                    </svg>
                </div>
                <h3>Планирование</h3>
                <p>Равным образом консультация с широким активом в значительной степени обуславливает.</p>
            </li>
            <li class="aside">
                <div class="pictures-icon">
                    <svg class="animatiol-icon">
                        <use href="./images/sprite.svg#icon-astronaut" width="70" height="70"></use>
                    </svg>
                </div>
                <h3>Современные технологии</h3>
                <p>Значимость этих проблем настолько очевидна, что реализация плановых заданий.</p>
               
            </li>
        </ul>
        </div>
    </section>
    <!--Чем мы занимаемся-->
    <section class="section-text">
        <div class="container">
        <h2 class="section-title">Чем мы занимаемся</h2>
        <ul class="list-content">
            
          <li class="item">
            <!-- <div class="dex-content"> -->
              <img src="./images/photo.jpg" width="370" height="294" alt=Програмирование >
            <!-- <div class="desktop-application"> -->
               <p class="dext-text">Десктопные приложения</p>
            <!-- </div> -->
            <!-- </div> -->
            </li>
           <li class="item">
            <!-- <div class="dex-content"> -->
             <img src="./images/photo1.jpg" width="370" height="294" alt=Оформление>
            <!-- <div class="desktop-application"> -->
                <p class="dext-text">Мобильные приложения</p>
            <!-- </div>
            </div> -->
           </li>
           <li class="item">
            <!-- <div class="dex-content"> -->
            <img src="./images/photo2).jpg" width="370" height="294" alt=Установка>
            <!-- <div class="desktop-application"> -->
                <p class="dext-text">Дизайнерские решения</p>
            <!-- </div>
            </div> -->
           </li> 
        </ul>
        </div>
    </section>
    <!--Наша команда-->
    <section class="section-list">
     <div class="container">
        <h2 class="section-title" >Наша команда</h2>
        <ul class="list-section">
    <li class="list-aside">
        <img src="./images/img3.jpg" width="270" height="260" alt="Игорь Демьяненко" />
         <div class="thumb">
        <h3  class="list-title">Игорь Демьяненко</h3>
        <p>Product Designer</p>
        <ul class="ourteam-text">
        <li class="ourteam-list">
          <a class="ourteam-link" href="">
           <svg class="ourteam-icon">
          <use href="./images/sprite.svg#icon-instagram1" width="20px" height="20px"></use>
         </svg>
         </a>
        </li>
        <li class="ourteam-list">
         <a class="ourteam-link" href="">
        <svg class="ourteam-icon">
            <use href="./images/sprite.svg#icon-tviter2" width="20px" height="20px"></use>
          </svg>
            </a>
            </li>
            <li class="ourteam-list">
          <a class="ourteam-link" href="">
            <svg class="ourteam-icon">
             <use href="./images/sprite.svg#icon-facebook3" width="20px" height="20px"></use>
            </svg>
             </a>
            </li>
            <li class="ourteam-list">
             <a class="ourteam-link" href="">
             <svg class="ourteam-icon">
             <use href="./images/sprite.svg#icon-linkedin4" width="20px" height="20px"></use>
            </svg>
            </a>
            </li>
        </ul>
         </div>  
    </li>
    <li class="list-aside">
        <img src="./images/img4.jpg" width="270" height="260" alt="Ольга Репина"/>
        <div class="thumb">
        <h3 class="list-title">Ольга Репина</h3>
         <p>Frontend Developer</p>
        <ul class="ourteam-text">
        <li class="ourteam-list">
         <a class="ourteam-link" href="">
        <svg class="ourteam-icon">
        <use href="./images/sprite.svg#icon-instagram1" width="20px" height="20px"></use>
        </svg>
        </a>
        </li>
        <li class="ourteam-list">
        <a class="ourteam-link" href="">
        <svg class="ourteam-icon">
        <use href="./images/sprite.svg#icon-tviter2" width="20px" height="20px"></use>
         </svg>
            </a>
        </li>
        <li class="ourteam-list">
        <a class="ourteam-link" href="">
         <svg class="ourteam-icon">
        <use href="./images/sprite.svg#icon-facebook3" width="20px" height="20px"></use>
         </svg>
        </a>
        </li>
        <li class="ourteam-list">
        <a class="ourteam-link" href="">
         <svg class="ourteam-icon">
         <use href="./images/sprite.svg#icon-linkedin4" width="20px" height="20px"></use>
         </svg>
        </a>
        </li>
        </ul>
        </div>
    </li>
     <li class="list-aside">
         <img src="./images/img5.jpg" width="270" height="260" alt="Николай Тарасов"/> 
        <div class="thumb">
        <h3 class="list-title">Николай Тарасов</h3>
         <p>Marketing</p>
        <ul class="ourteam-text">
        <li class="ourteam-list">
         <a class="ourteam-link" href="">
         <svg class="ourteam-icon">
             <use href="./images/sprite.svg#icon-instagram1" width="20px" height="20px"></use>
        </svg>
            </a>
         </li>
         <li class="ourteam-list">
          <a class="ourteam-link" href="">
         <svg class="ourteam-icon">
        <use href="./images/sprite.svg#icon-tviter2" width="20px" height="20px"></use>
        </svg>
         </a>
         </li>
        <li class="ourteam-list">
        <a class="ourteam-link" href="">
         <svg class="ourteam-icon">
         <use href="./images/sprite.svg#icon-facebook3" width="20px" height="20px"></use>
         </svg>
         </a>
      </li>
      <li class="ourteam-list">
        <a class="ourteam-link" href="">
         <svg class="ourteam-icon">
        <use href="./images/sprite.svg#icon-linkedin4" width="20px" height="20px"></use>
         </svg>
        </a>
       </li>
     </ul>
          </div>
    </li>
    <li class="list-aside">
        <img src="./images/img6.jpg" width="270" height="260" alt="Михаил Ермаков"/>
    <div class="thumb">
    <h3 class="list-title">Михаил Ермаков</h3>
     <p>UI Designer</p>
     <ul class="ourteam-text">
     <li class="ourteam-list">
        <a class="ourteam-link" href="">
        <svg class="ourteam-icon">
    <use href="./images/sprite.svg#icon-instagram1" width="20px" height="20px"></use>
     </svg>
     </a>
    </li>
     <li class="ourteam-list">
    <a class="ourteam-link" href="">
    <svg class="ourteam-icon">
    <use href="./images/sprite.svg#icon-tviter2" width="20px" height="20px"></use>
    </svg>
    </a>
     </li>
     <li class="ourteam-list">
     <a class="ourteam-link" href="">
     <svg class="ourteam-icon">
     <use href="./images/sprite.svg#icon-facebook3" width="20px" height="20px"></use>
      </svg>
     </a>
      </li>
      <li class="ourteam-list">
     <a class="ourteam-link" href="">
      <svg class="ourteam-icon">
    <use href="./images/sprite.svg#icon-linkedin4" width="20px" height="20px"></use>
    </svg>
     </a>
    </li>
    </ul>
     </div>
    </li> 
    </ul>  
  </div>
    </section>
    <section class="clients">
    <div class="container">
        <h2 class="clients-constant">Постоянные клиенты</h2>
         <ul class="clients-text list">
            <li class="clients-list">
             <a class="clients-link" href="">
            <svg class="logo-icon">
            <use href="./images/sprite.svg#icon-yaco1" width="106" height="60"></use>
            </svg>
            </a>
             </li>
            <li class="clients-list">
            <a class="clients-link" href="">
             <svg class="logo-icon">
            <use href="./images/sprite.svg#icon-naglinehere2" width="106" height="60"></use>
           </svg>
             </a>
            </li>
            <li class="clients-list">
            <a class="clients-link" href="">
            <svg class="logo-icon">
            <use href="./images/sprite.svg#icon-company3" width="106" height="60"></use>
            </svg>
            </a>
            </li>
            <li class="clients-list">
            <a class="clients-link" href="">
            <svg class="logo-icon">
            <use href="./images/sprite.svg#icon-fosterpeters4" width="106" height="60"></use>
            </svg>
            </a>
            </li>
            <li class="clients-list">
             <a class="clients-link" href="">
            <svg class="logo-icon">
             <use href="./images/sprite.svg#icon-brand5" width="106" height="60"></use>
            </svg>
            </a>
            </li>
            <li class="clients-list">
             <a class="clients-link" href="">
            <svg class="logo-icon">
            <use href="./images/sprite.svg#icon-tagline6" width="106" height="60"></use>
            </svg>
            </a>
            </li>
         </ul>
        </div>
    </section>
   <!--Подвал-->
    <footer class="section-footer">
    <div class="container">
        <div class="footer-link">
        <a href="./index.html" class="logo-logo">
    <span class="part part-logo">Web</span>Studio</a>
      <address class="active works">
        <!-- <a href="./index.html" class="logo">
        <span class="part part-logo">Web</span>Studio</a> -->
    <ul class="address">
     <li>  Киев, пр-т Леси Украинки, 26</li>
     </ul>
    <ul class="text-meta">
     <li><a class="link" href="malito:info@devstudio.com">info@devstudio.com</a></li>
    <li><a class="link" href="tel+380961111111">+38 096 111 11 11</a></li>
   </ul>
    </address>
</div>
    <div class="footer-contacts">
    <p class="join-footer">присоединяйтесь</p>
    <ul class="footer-text">
    <li class="footer-list">
    <a class="contacts" href="">
    <svg class="footer-icon">
        <use href="./images/sprite.svg#icon-instagram1" width="20px" height="20px"></use>
    </svg>
    </a>
  </li>
<li class="footer-list">
 <a class="contacts" href="">
  <svg class="footer-icon">
  <use href="./images/sprite.svg#icon-tviter2" width="20px" height="20px"></use>
 </svg>
 </a>
</li>
<li class="footer-list">
 <a class="contacts" href="">
<svg class="footer-icon">
<use href="./images/sprite.svg#icon-facebook3" width="20px" height="20px"></use>
</svg>
</a>
</li>
<li class="footer-list">
 <a class="contacts" href="">
 <svg class="footer-icon">
 <use href="./images/sprite.svg#icon-linkedin4" width="20px" height="20px"></use>
</svg>
 </a>
</li>
    </ul>
</div>
<div class="footer-mailing">
    <p class="title-mailing">Подпишитесь на рассылку</p>
    <form class="mailing-form">
    <label class="mailing-leibel" for="contact-email"></label>
    <input class="mailing-input" id="contact-email" placeholder="E-mail" type="email">
    <button class="button-mailing" type="button">Отправить</button> 
    </form>
</div>
</div>
    </footer>
   </main>
   <div class="hero-backdrop is-hidden" data-modal>
    <div class="hero-modal">
    <button type="button" class="close-button" data-modal-close>
    <svg class="modal-icon">
        <use href="./images/sprite.svg#icon-close-black11"></use>
   </svg>
</button>

 <form class="form" action="#" autocomplete="off" novalidate>
      <h2 class="form-title">Оставьте свои данные, мы вам перезвоним</h2>
     <div class="form-class list-top">
     <label class="form-label" for="name" > Имя</label>
     <input class="form-input current" id="name" type="text">
    <svg class="form-icon" >
    <use href="./images/sprite.svg#icon-person-black-18dp-1-1" width="12px" height="12px"></use>
    </svg>
</div>
<div class="form-class">
    <label class="form-label" for="contact-tel">Телефон</label>
    <input class="form-input" id="contact-tel" type="tel">
    <svg class="form-icon">
        <use href="./images/sprite.svg#icon-phone-black-18dp-1-1" width="13px" height="13px"></use>
    </svg>
</div>
<div class="form-class">
    <label class="form-label" for="contact-email">Почта</label>
    <input class="form-input" id="contact-email" type="email">
    <svg class="form-icon">
        <use href="./images/sprite.svg#icon-email-black-18dp-1-1" width="15px" height="12px"></use>
    </svg>
</div>
<div class="form-class">
 <label class="comment-label" for="comment">Комментарий</label>
<textarea class="form-input comment" name="comment" id="comment" placeholder="Введите текст"></textarea>
</div>
<div class="class-checkbox">
<label class="form-checkbox" for="form-checkbox">
<input class="input-checkbox" id="form-checkbox" type="checkbox">
<span class="checkbox-icon"></span>
Соглашаюсь с рассылкой и принимаю <a class="form-link" href=""> Условия договора</a>

</label>
</div>
<button class="button-modal" type="button">Отправить</button>
</form>
    </div>
   </div>
   <script src="./js/modal.js"></script>
  </body>
 </html>




/* цвет фона вторичный 
#FFFFFF      #E5E5E5;     #F5F4FA*/
/* цвет основного текста #FFFFFF; */
/* текст h2 #212121;*/
/* футер адрес #FFFFFF */
/* контакт rgba(255, 255, 255, 0.6) */
/*вторичный текст #757575;*/
/*сексыя наша команджа #757575 */
/* акцент#2196F3; */

:root {
   --primary-text-color: #212121;
   --title-text-paragraph: #757575;
   --accent-color: #2196F3;
   --primary-bg-color:#E5E5E5;
   --logo-nav-color:#000000;
   --logo-footer-color:#FFFFFF;
   --address-footer-color:#F5F4FA;
   --h1-color:#2F303A;
   --cube-color:cubic-bezier(0.4, 0, 0.2, 1);
   --form-input-color:rgba(33, 33, 33, 0.2);
}

html {
  box-sizing: border-box;
}
  *, *::before, *::after{
    box-sizing: border-box;  
  }
body {
  margin: 0;
  padding: 0;
  background-color: var(--logo-footer-color);
  color: var(--primary-text-color);

  font-family: Roboto, sans-serif;
  letter-spacing: 0.02em;
  font-size: 14;
}
.container {
  /* align-items: center;
  display: flex; */
  margin-left: auto;
  margin-right: auto;
  width: 1200px;
  /* outline: 2px solid red; */
  padding-left: 15px;
  padding-right: 15px;

} 
 


.site-nav{
display: flex;  
margin-left: 93px;
}
.header-nav{
  align-items: center;
  display: flex;
}
.text  .list{
  margin-left: auto;
}
.nav-flex {
  align-items: center;
  display: flex;
}

 

 .container {
  margin-left: auto;
  margin-right: auto;
  width: 1200px;
  padding-right: 15px;
  padding-left: 15px;
  /* display: block;
  max-width: 100%;
  height: auto; */

   /* outline: 2px solid red;  */
} 
.page-header{
/* border: 1px solid #ECECEC; */
background-color: var(--logo-footer-color);
border-bottom:1px solid #ECECEC;
}
h1, h2, h3, p{
  margin: 0;
  padding: 0;
}
.header-icon{
  width: 15px;
  height: 16px;
  margin-right: 10px;
}

 .section .no-podding {
  padding-top: 0;
  padding-bottom: 0;
 
} 
.ourteam-icon{
  margin: 12px 0 0 12px;
  text-align: center;
  justify-content: center;
  
}

.section-benefits{
  padding-top: 94px;
  /* padding-bottom: 94px; */
}


  /* padding-top: 94; *
/* .section {
margin-bottom: 0;
margin-top: 0%;
}  */

  /* logo */

 .logo{

  color: var(--logo-nav-color);
  font-family: Raleway, sans-serif;

  font-weight: 700;
  font-size: 26px;
  line-height: 1.19;
  font-size: normal;
  text-decoration: none;
  font-style: normal;
 }

.part-logo {
  color: var(--accent-color);
}
/* логин в футаре */
.logo-logo{
  margin-bottom: 20px;
  display: block;
  color: var(--logo-footer-color);
  font-family: Raleway, sans-serif;

  font-size: 26px;
  line-height:1.19;
  font-size: normal;
  text-decoration: none;
  padding: 0;


  }
  /* футер адрес */
 .activ{
   font-style: normal;

 }
  .address{
   margin-bottom: 9px;
   color: var(--address-footer-color);
   font-family: Roboto,normal;
  font-size: 14px;
  line-height: 1.71;
   }
   .address>li:hove,  
   .address>li:focus {
    color: #2196F3;
   }

  .address{
   flex-direction: column;
   font-style: normal;
  } 
  .address>li:not(:last-child){
   display: block;
  }

  .section-footer {
    padding-top: 60px;
    padding-bottom: 60px;
    background-color: #2F303A;
  }
  .section-footer .container{
    display: flex;
    align-items: baseline;
  }
  .join-footer{
    font-weight: 700;
    font-size: 14px;
    line-height: 1.14;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    margin-bottom: 20px;
    
    color: var(--logo-footer-color);
  }

  /* фоотер гд текст */
  .text-meta .link {
    color: rgba(255, 255, 255, 0.6);
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 1.71;
    text-decoration: none;
  }
  
  .text-meta .link:hover, 
  .text-meta .link:focus {
    color: #2196F3;

  }
  .text-meta>li:not(:last-child) {
   display: block;
   margin-bottom: 9px;
  }
  .footer-text{
  display: flex;
  justify-content: space-between;
  } 
  .footer-list{
  width: 44px;
  height: 44px;
 } 

.contacts{
  width: 44px;
  height: 44px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.1);
  display: block;
  transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1)
}
.contacts:hover,
.contacts:focus{
  background-color: var(--accent-color);
}
  
  .footer-icon {
    width: 20px;
    height: 20px;
    margin: 12px 0 0 12px; 
    fill: var(--logo-footer-color);
  }
  /* .footer-icon:hover,
  .footer-icon:focus{
    fill: #2196F3;
  } */

  .footer-contacts{
  margin-left: 70px;
  width: 206px;
  }
  /* Подпишитесь на рассылку в шапке */

  .footer-mailing{
    margin-left: auto;
  }
   .title-mailing {
    font-weight: 700;
    font-size: 14px;
    line-height: 1.14;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    margin-bottom: 20px;
    color: var(--logo-footer-color);
  } 
  .mailing-leibel{
    font-weight: 400;
    font-size: 16px;
    line-height: 1.25;
    display: flex;
    align-items: center;
    letter-spacing: 0.03em;
    color:rgba(255, 255, 255, 0.6);
    }

.mailing-input{
  margin: 0;
  width: 358px;
  padding: 15px 16px;
  outline: none;
  border-radius: 4px;
  border: 1px solid rgba(255, 255, 255, 0.3);
  background: var(--h1-color);
  color: var(--accent-color);
}

.mailing-input::placeholder{
  color: rgba(255, 255, 255, 0.6);
}

   .button-mailing {
   display:inline-flex;
    align-items: center;
    justify-content: center;
    /* text-align: center; */
    margin: 0 ;
    border-radius: 4px;
   width: 200px;
    padding:0;
    margin-left: 12px;
    height: 50px;
    color: var(--address-footer-color);
    box-shadow: 0px 4px 4px rgb(0 0 0 / 15%);
    background-color: var(--accent-color);
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 1.87;
    letter-spacing: 0.06em;
    border: none; 

}
.button-mailing::after{
  content: "";
  margin-left: 10px;
  width: 24px;
  height: 24px;
  background-image: url(../images/icon\ \ telegram.svg);
}

  /* h2наша команда в ul */

.list-section { 

  margin: 0;
  padding: 0;
  list-style: none;
}



/* задачя организации */
.list-body{
  /* padding-top: 94px; */
  display: flex;
  
  
}
.list-body .aside+ .aside{
  margin-left: 30px;
}
.list-body .aside{  
  width: 270px;
}
/* .aside::before{
  display:inline-block;
  content: "";
  width: 270px;
  height: 120px;
  border-radius: 4px;
   background-color: #F5F4FA;
} */
 


/* .site-nav .list{
 background-color: tomato;
} */


.site-nav {
  display: flex;
  margin-left: 93px;
}

.header-nav {
  align-items: center;
  display: flex;
}

.text .list {
  margin-left: auto;
}

.nav-flex {
  align-items: center;
  display: flex;
}

.site-nav  .link.current::after {
  position: absolute;
  content: "";
  display: block;
  height: 4px;
  border-radius: 2px;
  width: 100%;
  left: 0;
  bottom: 0;
  background-color: var(--accent-color);

}

.site-nav .list+ .list{
  margin-left: 50px;
}

.site-nav .link{
position: relative;

  padding-top: 32px;
  padding-bottom: 32px;

  color: var(--primary-text-color);
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  text-decoration: none;
  transition-duration:color 250ms cubic-bezier(0.4, 0, 0.2, 1);


   
}
.site-nav .link.current {
  color: var(--accent-color);
}
/* сайт nav */

.site-nav .link:hover,
.site-nav .link:focus {
    color: var(--accent-color);
 } 


 /* ul contact  header*/
 .text .link{

  align-items: center;
  display: inline-flex;
  color:var(--title-text-paragraph);
  padding-top: 32px;
  padding-bottom: 32px;
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14px;
  letter-spacing: 0.02em;
  text-decoration: none;
   }
 .text .header-icon:hover,
 .text .header-icon:focus,
 .text .link:hover, 
 .text .link:focus{
   color: var(--accent-color);
   fill: var(--accent-color);
 }
  .header-icon{
  fill: currentColor;
  }

  .text{
    display: flex;
    margin-left: auto;
   
 }
 .text .list + .list{
   margin-left: 50px;
 }
 
 /* .-paragraph);
 } */
 /* .text .header-icon:hover,
 .text .header-icon:focus{
   fill: var(--accent-color);
 }
 .text .header-icon:current{
   fill: var(--accent-color);
 }  */

 /* ul для портфолио */

 /* задача организации */
.list-body p {
  margin-top: 0;
  margin-bottom: 0;
  color: var(--title-text-paragraph);

   font-weight: 400;
    font-size: 14px;
    line-height: 1.7; 
    }
.list-body h3 {
  margin-top: 0;
  margin-bottom: 10px;
  color: var(--primary-text-color);
  font-weight: 700;
  font-size: 14px;
  line-height: 1.14;
  text-transform: uppercase;
}

/* h3 наша команда */
.list-aside .list-title {
  margin-top: 0;
  text-align: center;
  color: var(--primary-text-color);
  margin-bottom: 0;
  /* margin-bottom: 0px; */
  font-weight: 500;
  font-size: 16px;
  line-height: 1.2;
}
 img {
  display: block;
  max-width: 100%;
  height: auto;
  margin-top: o;
  margin-bottom: o;

}

.list-section p { 
  text-align: center;
  margin-top: 10px;
  margin-bottom: 0;
   color: var(--title-text-paragraph);
   /* margin-top: 10px; */
   font-size: 16px;
   line-height: 1.19;
  }
  .thumb {
   padding: 30px 32px; 
   }
  
.list-aside{
  background: var(--logo-footer-color);
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12),
  0px 1px 1px rgba(0, 0, 0, 0.14),
  0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 0px 0px 4px 4px;
}
.section-list {
  background-color:#F5F4FA;
}
.section-text{
  padding-top: 94px;
  padding-bottom: 94px;
}
.section-list{
  padding-bottom: 94px;
  padding-top: 94px;
}

  /* чем мы занимаемся  */
.list-content {
display: flex;
text-align: center;

}
.list-content .item+ .item{
  margin-left: 30px;
}
.list-section{
  display: flex;
  /* padding-bottom: 94px; */
}
.list-section {
justify-content: space-between;
}
.list-content .item{
  display: block;
  max-width: 100%;
  height: auto;
}
.ourteam-text{
  display: flex;
  justify-content: space-between;
  margin-top: 16px;
  align-items: center;
  
}
.item{
position: relative;
display: inline-block;
}
/* .dex-content{


}
.desktop-application{
  
} */
.dext-text{
color: var(--logo-footer-color);

font-size: 14px;
line-height: 1.14;
display: flex;
height: 70px;
justify-content: center;
align-items: center;
letter-spacing: 0.03em;
text-transform: uppercase;
/* padding: 27px 82px; */
position: absolute;
width: 100%;

background: rgba(47, 48, 58, 0.8);
top: 76%;
}

.ourteam-list{
width: 44px;
height: 44px;
}
.ourteam-icon{
  width: 20px;
  height: 20px;
  /* background-color: tomato; */
}
.ourteam-link {
  width: 44px;
  height: 44px;
  border-radius: 50%;
  fill: #AFB1B8;
  display: block;
 transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.ourteam-link:hover,
.ourteam-link:focus {
  background-color: #2196F3;
  fill: var(--logo-footer-color);


}


/* hero */

.hero-title {
  max-width: 1600px;
   text-transform: uppercase; 
   margin-top: 0; 
  margin: 0 auto;
  margin-bottom: 30px;
  color: var(--address-footer-color);
   width: 696px;
  font-weight: 900;
    font-size: 44px;
    line-height: 1.36;
    text-transform: uppercase;
    text-align: center;
    letter-spacing: 0.06em;
}

.hero{
  text-align: center;
  background-color: var(--h1-color);
  padding-top: 200px;
  padding-bottom: 200px;
  background-image:linear-gradient(to left,rgba(47, 48, 58, 0.4),rgba(47, 48, 58, 0.4)),
  url(../images/Img\ hero.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  }
   /* другой пример */
  .hero-backdrop {
    position: fixed;
    /* display: flex;
    align-items: center;
    justify-content: center; */
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-color: rgba(0, 0, 0, 0.2);
    top: 0;
    transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1), visibility 250ms cubic-bezier(0.4, 0, 0.2, 1);
  }  
   /* .hero-backdrop {
    position: fixed;
   display: flex;
   align-items: center;
   justify-content: center;
    top: 0;
    left: 0;
    width: 0;
    height: 0;
    background-color: rgba(0,0,0,0.2);
    opacity: 1;
    transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1), visibility 250ms cubic-bezier(0.4, 0, 0.2, 1);

  }  */
  /* модальное окнол */
  .hero-backdrop.is-hidden{
    opacity: 0;
    pointer-events: none;
    
  }
  
  /* .hero-modal {
    position: relative;
    width: 528px;
    height: 581px;
    transform: scale(1);
    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
    border-radius: 4px;
    background: var(--logo-footer-color); */
    /* top: 50%;
        left: 50%;
        transform: translate(-50%, -50%) scale(1); */
  
  /* .hero-modal{
    width: 528px;
    min-height: 581px;
    background-color: #ffffff;
    
    position: relative;
    transform: scale(1);
    transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
 }  */
  .hero-modal{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  height: 581px;
  width: 528px;
  background: #FFFFFF;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12),
  0px 1px 1px rgba(0, 0, 0, 0.14),
  0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 4px;
  /* padding: 15px; */
  transition: transform 250ms var(--cube-color);
  }  
  /* .close-button{
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    top: 8px;
    right: 8px;
    width: 30px;
    height: 30px;
    border: 1px solid var(--logo-nav-color);
    box-sizing: border-box;
  } */
  .close-button {
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
  
    right: 8px;
    top: 8px;
    background-color: transparent;
    border-radius: 50%;
    width: 30px;
    height: 30px;
  border: 1px solid rgba(0, 0, 0, 0.1);
  }
  /* .close-button{
  right: 8px;
  top: 8px;
  background: #FFFFFF;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 50%;
  width: 30px;
  height: 30px;
  cursor: pointer;
  } */
 /* .works{
   background-color: var(--logo-nav-color);
 } */


.modal-icon:hover,
.modal-icon:focus{
fill: var(--accent-color);
border-color: var(--accent-color);
border: none;
}
/* офомления модал окна  */
.form{
  width: 528px;
padding: 40px;
margin-left: auto;
margin-left: auto;
}
.form-class{
position: relative;
display: flex;
flex-direction: column;
margin-bottom: 10px;
}

.list-top{
  margin-top: 12px;
}
.form-label, .comment-label {
font-weight: 400;
font-size: 12px;
line-height: 14px;
margin-bottom: 4px;
color: var(--title-text-paragraph);
}
.form-input{
margin: 0;
width: 100%;
padding: 10px 35px;
background: var(--logo-footer-color);
border-radius: 4px;
border: 1px solid var(--form-input-color);
transition: border-color 250ms var(--cube-color);
}
.form-icon{
  position: absolute;
  width: 15px;
  height: 15px;
  top: 55%;
  left: 15px;
  transition: fill 250ms var(--cube-color);
}
.form-input:hover,
.form-input:focus{
border-color: var(--accent-color);
 outline: none; 
}
.form-input:hover ~ .form-icon,
.form-input:focus ~ .form-icon{
  fill: var(--accent-color);
}

.form-title {
  font-weight: 700;
  font-size: 20px;
  line-height: 1.15;
  text-align: center;
  letter-spacing: 0.03em;

}
.comment{ 
  height: 120px;
  padding: 12px 16px;
  resize: none;
  font-size: 12px;
  line-height: 14px;
  letter-spacing: 0.01em;
  
  color: rgba(117, 117, 117, 0.5);
}
.form-checkbox{
  display: flex;
  align-items: center;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.03em;
  color: var(--title-text-paragraph);
}
 /* .coment-label{
  font-weight: 400;
  font-size: 12px;
  line-height: 14px;
  margin-top: 0;
  margin-bottom: 4px;
color: var(--title-text-paragraph);
} */
 .form-link{
   color: var(--accent-color);
   margin-left: 3px;
 }
 .button-modal{
      display:flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      margin: 0 auto;
      border-radius: 4px;
      width: 200px;
      height: 50px;
      color: var(--address-footer-color);
      background-color: var(--accent-color);
      font-weight: 700;
      font-size: 16px;
      line-height: 30px;
      letter-spacing: 0.06em;
      border: none;
 }
 .class-checkbox{
   margin-top: 25px;
   margin-bottom: 25px;
   padding-left: 14px;
 }
  .input-checkbox{
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    border: 0;
    clip: rect(0 0 0 0);
    }
.input-checkbox:checked +.checkbox-icon{
  background-image: url(../images/like-icon.svg);
  background-color: var(--accent-color);
  background-position: center;
  border-color: var(--accent-color);
}
.checkbox-icon{
  display: inline-block;
  width: 16px;
  height: 15px;
  border-radius: 2px;
  border: solid #212121;
  background-color: var(--logo-footer-color);
  margin-right: 8px;
}
/* .form-label, .comment-label{
  font-weight: 400;
  font-size: 12px;
  line-height: 14px;
  margin-bottom: 4px;
  color: var(--title-text-paragraph);
} */
/* заголовки h2 */
.section-title{

  margin-top: 0;
  margin-bottom: 50px;
  /* padding-top: 94px; */
  color: var(--primary-text-color);
  font-weight: 700;
  font-size: 36px;
  line-height: 1.6;
  text-align: center;
}
.section-title{
  padding: 0;
}
/* приймучество */
.pictures-icon {
  display: flex;
  background-color: #F5F4FA;
  width: 270px;
  height: 120px;
  align-items: center;
  justify-content: center;
  margin-bottom: 30px;
  padding: 0;
  
}
.animatiol-icon{
position: absolute;
width: 70px;
height: 70px;
color: #212121;
}
 .nimatiol-icon:hover,
.animatiol-icon:focus{
  fill:var(--logo-nav-color);
}
/* постоянные клиенты */
.clients{
  background-color: var(--logo-footer-color);
  /* width: 1600px;
  height: 708px; */
  padding-top: 94px;
  padding-bottom: 94px;
}
.clients-text{
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0;
  margin: 0;
  text-decoration: none;
  list-style: none;
}


  .clients-link {
  width: 170px;
  height: 90px;
  /* padding: 16px 32px;
   */
  display: flex;

  justify-content: center;
   align-items: center;
  color: #afb1b8;
  border-radius: 4px;
  border: 1px solid #afb1b8;
  transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1),
  color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.clients-link:hover,
.clients-link:focus {
  color: var(--accent-color);
  border-color: var(--accent-color);
} 
.clients-constant{
  margin-top: 0;
  padding: 0;
  justify-content: center;
  margin-bottom: 50px;
  font-weight: 700;
  font-size: 36px;
  line-height: 42px;
  text-align: center;

}
.logo-icon{
  position: absolute;
  width: 106px;
  height: 60px;
  fill: currentColor;
  transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1),
  color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.logo-icon:hover,
.logo-icon:focus{
  fill: #2196F3;
  fill: currentColor;
      
}





.clients-text .clients-list+ .clients-list{
margin-left: 30px;
}

   /* button */
  .button {
    display: inline-block;  

    border-radius: 4px;
    padding: 10px 32px;
    min-width: 200px;
    color: var(--address-footer-color);
    background-color:var(--accent-color);
    font-weight: 700;
    font-size: 16px;
    line-height: 30px;
    letter-spacing: 0.06em;
    border: none;
    } 
  .button:hover,
  .button:focus {
  background-color: #188CE8;
  }
  

/* ПОРТФОЛИО */


/* кнопки ul */
.portfolio-title {
  display: none;

}
/* сброс для всех порт,веб */
ul {
  list-style: none;
  text-decoration: none;
  padding: 0;
  margin: 0;
} 
.title-text{
  background-color: var(--logo-footer-color);
  padding-bottom: 94px;
  padding-top: 94px;
  display: block;
   max-width: 100%;
  height: auto;

}
.filter-text {
  margin-bottom: 50px;
  justify-content: center;
  display: flex;
}

.filter-text .item:not(:last-child) {
  margin-right: 8px;
}




/* button */
.filter-text.btn-main .blockquote-button{
color:var(--primary-text-color);
background-color: var(--address-footer-color);

font-weight: 500;
font-size: 16px;
line-height: 26px;
letter-spacing: 0.03em;

}
.filter-text .btn-main .blockquote-button:hover,
.filter-text.btn-main .blockquote-button:focus{
  color:var(--logo-footer-color);
  background-color: var(--accent-color);
}


/* h2 */
.headline{
  margin-top: 0;
  margin-bottom: 4px;
  color:var(--primary-text-color);

  font-weight: 700;
  font-size: 18px;
  line-height: 2;
  letter-spacing: 0.06em;
  list-style: none;
}
/* p */
 .projects-title{
  color: var(--title-text-paragraph);
  margin-bottom:0;
  margin-top: 0;
  font-size: 16px;
  line-height: 1.87;
  
}
  /* фон на картках в профиле */
.backdrop{
      position: relative;
      overflow: hidden;


  /* position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: ; */

 }

 /* .modal{
  position: absolute;
  top: 50%;
  left: 50%;
 transform: translate(-50%, -50%);
 width: 370px;
 height: 294px;
 padding: 15px;
 background: rgba(33, 150, 243, 0.9);
 }  */
 /* пример другого макета */
 .modal{
  position:absolute;
  display:inline-block;
  width: 100%;
  height: 100%;
  top:0 ;
  left:0 ;
  /* opacity: 1px; */
  transform: translateY(101%);
  transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
  background-color:rgba(33, 150, 243, 0.9);
}  



 .modal-text{
position: absolute;
padding: 63px 24px;
font-size: 18px;
line-height: 1.56;
color: var(--logo-footer-color);
 }
.projects-list-text:hover .modal,
.projects-list-text:focus .modal {
  transform: translateY(0);
  }
.link-backdrop{
display: block;
list-style: none;
text-decoration: none;
}
.projects-list .link-title {
text-decoration: none;
list-style: none;
}
/* .projects-list{
list-style: none;
opacity: 1px;  */


.link-title{
  display: block;

}


 .container {
  width: 1200px;
  padding-left: 15px;
  padding-right: 15px;
  margin-left: auto;
  margin-right: auto;
  /* display: block;
  max-width: 100%;
  height: auto; */
}  
 /* .test-container{
 display: flex;
flex-wrap: wrap;
} */

  /* background-color: teal; */
  
  .projects-list{
  display: flex;
  flex-wrap: wrap; 
  margin: -15px;
  /* background-color: tomato; */
} 
.projects-list-text {
  margin: 15px;
/* width: calc((100% - 60px) / 3);
margin-right: 30px;
 margin-bottom: 30px; */
/* width: 370px; */
} 
/* .projects-list-text:nth-child(3n) {
  margin-right: 0;
} 
 .projects-list-item:nth-last-child(-n + 3) {
  margin-bottom: 0;
} */
.projects-list-text .main{
  padding: 20px 24px;
  border-bottom: 1px solid #eeeeee;
  border-left: 1px solid  #eeeeee;
  border-right: 1px solid #eeeeee;
}  
.link-title img {
  display: block;
  max-width: 100%;
  height: auto;
}
 .blockquote-button{
  min-width: 73px;
  padding: 6px 22px;
  border: none;
  border-radius: 4px;
  font-family: inherit;
  font-weight: 500;
  font-size: 16px;
  line-height: 1.62;
  text-align: center;
  letter-spacing: 0.03em;
 }
 .filter-text .btn-main:not(:last-child){
     margin-right: 8px;
   }

/* animation header */
    /* @keyframes translatecall {
   0% {
    transform: translateY(0);
    }
   50% {
    transform: translateY(20px);
   }
   100% {
    transform: translateY(0);
   }
  }  
  .header-icon{
    animation-name: translatecall;
    animation-duration: 5s;
  animation-iteration-count: infinite;
  animation-delay: 4px;
  } */
   /* короткий запис
  animation: 5s infinite; */










