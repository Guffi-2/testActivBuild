<template>
    <header>
    <img src="./On.png" class="logo vue" alt="Vue logo" />
    <h2>Актив школы 211</h2>
    <menu>
      <h4 id="news">Новоcти</h4>
      <h4 id="about">О нас</h4>
      <h4 id="soc-seti">Соц-сети</h4>
    </menu>
  </header>
  <mobileMenu>
      <h4 id="news_m"><a href="#news_p">Новоcти</a></h4>
      <h4 id="about_m"><a href="#about_p_o_nas">О нас</a></h4>
      <h4 id="soc-seti_m">Соц-сети</h4>
  </mobileMenu>
  <main>
  <div class="news_title">
    <h2 id="news_p">Новости</h2>
  </div>
  <news>
  <news_p>
    <div class="post_1">
        <h4>🎤Приглашаем всех желающих на новый концерт Оркестра!🎤</h4>
        <img src="./ljdsfh.jpeg"/>
        <h5>Оркестр 211<br>
            🌟27.10.2023🌟<br>
            🎬11:40<br>
            🎤Актовый зал<br>
            🎬Вход для всех желающих с 11:30<br>
            🎬Завтра<br>
            🎸Приходите на наш новый концерт!🎸<br>
            <u>Приглашаются все желающие!</u><br> </h5>
            <a href="https://vk.com/wall-213311039_82">VK пост</a>
    </div>
    <div class="post_2">
        <h4>🎤Приглашаем всех желающих на новый концерт Оркестра!🎤</h4>
        <img src="./ljdsfh.jpeg"/>
        <h5>Оркестр 211<br>
            🌟27.10.2023🌟<br>
            🎬11:40<br>
            🎤Актовый зал<br>
            🎬Вход для всех желающих с 11:30<br>
            🎬Завтра<br>
            🎸Приходите на наш новый концерт!🎸<br>
            <u>Приглашаются все желающие!</u><br> </h5>
            <a href="https://vk.com/wall-213311039_82">VK пост</a>
    </div>
  </news_p>
</news>

<div class="about_title">
      <h2 id="about_p_o_nas">О нас</h2>
</div>
  <about>
    <div class="about_p">
      <h3 id="about_text">Актив - это большая и дружная семья, члены которой создают школьные традиции и уклад. Благодаря разделению нашего актива по видам деятельности и интересам, каждый может найти занятие по душе и проявить себя.</h3>
    </div>
  </about>
</main>
<footer>
  <h2>buil version 0.0.2</h2>
</footer>
</template>

<style>
#about_p_o_nas{
  font-size: 1.6rem;
}
#about_text{
  padding-top: 30px;
  padding-left: 50px;
  padding-right: 50px;
}
.about_title{
  padding-top: 312px;
  padding-left: 40px;
  font-size: 1.6rem; 
}
mobileMenu a{
  text-decoration: none;
}

.news_title{
  width: 100%;
  height: 10px;
}

.post_2{
  width: 400px;
  height: 535px;
  background-color: rgb(243, 243, 243);
  border-radius: 30px;
  margin-right: 30px;
}
.post_2 h4{
  padding: 15px;
}
.post_2 h5{
  padding-top: 0px;
  padding-left: 15px;
  font-size: 15px;
}
.post_2 h3{
  padding-top: 0px;
  padding-left: 0px;
}
.post_2 a{
  padding-top: 0px;
  padding-left: 15px;
  text-decoration: none;
  font-weight: bolder;
  color: #4f75d6;
}
.post_2 img{
  width: 400px;
}

.post_1{
  width: 400px;
  height: 535px;
  border-radius: 30px;
  margin-right: 50px;
}
.post_1 h4{
  padding: 15px;
}
.post_1 h5{
  padding-top: 0px;
  padding-left: 15px;
  font-size: 15px;
}
.post_1 h3{
  padding-top: 0px;
  padding-left: 0px;
}
.post_1 a{
  padding-top: 0px;
  padding-left: 15px;
  text-decoration: none;
  font-weight: bolder;
  color: #4f75d6;
}
.post_1 img{
  width: 400px;
}
#news_p{
  padding-top: 20px;
  padding-left: 40px;
  font-size: 1.6rem; 
}
news_p{
  width: 100%;
  height: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 333px;
}
#news{
  padding-right: 20px;
}
#about{
  padding-right: 20px;
}
.logo {
  height: 5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo.vue {
  /* */
  margin: none;
}
menu{
  width: 55%;
  height: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.logo.vue:hover {
  filter: drop-shadow(0 0 0.4em #b90000); /* #a5a5a5*/
}
mobileMenu{
  width: 100%;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: none;
  padding: none;
  background-color: #2e2e2e;
  display: none;
}
header{
  width: 100%;
  height: 85px;
  display: flex;
  justify-content: left;
  align-items: center;
  margin: none;
  padding: none;
}

@media (min-width: 640px) {
  body{
    display: none;
  }
  h2 { 
    font-size: 1.5vw;
  }
  h4{
    font-size: 1.3vw;
  }
  .logo {
  height: 5em;
  will-change: filter;
  transition: filter 300ms;
  }
  #about_m{
    visibility: hidden;
  }
  #news_m{
    visibility: hidden;
  }
  #soc-seti_m{
    visibility: hidden;
  }
  mobileMenu{
    visibility: hidden;
    display: none;
  }
}

@media (min-width: 1200px) {
  body{
    display: none;
  }
  h2 { 
    font-size: 1.5vw;
  }
  h4{
    font-size: 1.3vw;
  }
  .logo {
  height: 5em;
  will-change: filter;
  transition: filter 300ms;
  }
  #about_m{
    visibility: hidden;
  }
  #news_m{
    visibility: hidden;
  }
  #soc-seti_m{
    visibility: hidden;
  }
  mobileMenu{
    visibility: hidden;
    display: none;
  }
}
@media (max-width: 1199px) and (min-width: 900px) {
  h2 { 
    font-size: 1rem; 
  }
  #about_m{
    visibility: hidden;
  }
  #news_m{
    visibility: hidden;
  }
  #soc-seti_m{
    visibility: hidden;
  }
  mobileMenu{
    visibility: hidden;
    display: none;
  }
}

@media (min-width: 320px) and (max-width: 899px) {
  footer{
    margin-top: 1283px;
    background-color: #373737;
    width: 90%;
    height: 100px;
    padding: 10px;
  }
  mobileMenu{
    display: flex;
  }
  .logo {
  height: 4em;
  will-change: filter;
  transition: filter 300ms;
  }
  header h2{
    width: 55%;
    height: 85px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #about{
    visibility: hidden;
  }
  #news{
    visibility: hidden;
  }
  #soc-seti{
    visibility: hidden;
    
  }

  #about_m{
    padding-right: 20px;
  }
  #news_m{
    padding-right: 20px;
  }
  menu{
    display: none;
  }
  news{
    padding-top: 20px;
    width: 100%;
    height: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #news_p{
  padding-top: 0px;
  padding-left: 0px;
  font-size: 1.6rem; 
}
#about_p_o_nas{
  padding-top: 2090px;
  padding-left: 0px;
  font-size: 1.6rem; 
}
.about_title {
  padding-top: 40px;
  padding-left: 0px;
    width: 100%;
    height: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.post_1{
  width: 95%;
  height: 520px;
  background-color: #373737;
  border-radius: 30px;
  margin-right: 0px;
}
.post_1 h4{
  padding: 15px;
}
.post_1 h5{
  padding-top: 0px;
  padding-left: 15px;
  font-size: 16px;
}
.post_1 h3{
  padding-top: 0px;
  padding-left: 0px;
}
.post_1 a{
  padding-top: 0px;
  padding-left: 15px;
  text-decoration: none;
  font-weight: bolder;
  color: #4f75d6;
}
.post_1 img{
  width: 100%;
}
.post_2{
  width: 95%;
  height: 520px;
  background-color: #373737;
  border-radius: 30px;
  margin-right: 0px;
  margin-top: 15px;
}
.post_2 h4{
  padding: 15px;
}
.post_2 h5{
  padding-top: 0px;
  padding-left: 15px;
  font-size: 16px;
}
.post_2 h3{
  padding-top: 0px;
  padding-left: 0px;
}
.post_2 a{
  padding-top: 0px;
  padding-left: 15px;
  text-decoration: none;
  font-weight: bolder;
  color: #4f75d6;
}
.post_2 img{
  width: 100%;
}
news_p{
  width: 100%;
  height: 10px;
  display: flex;
  /* align-items: center; */

  
  padding-top: 12px;
  flex-wrap: wrap;
  
  
  /* justify-content: center;*/
}
.about_p{
  width: 100%;
  height: 10px;
  display: flex;
  /* align-items: center; */


  
  padding-top: 12px;
  flex-wrap: wrap;
  


  /* justify-content: center;*/
}
.news_title{
  padding-top: 25px;
  width: 100%;
  height: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.mobile_pons{
  display: grid;
  justify-content: center;
  align-items: center;
}
#about_text{
  width: 95%;
  margin-top: 1039px;
  padding-left: 20px;
  padding-right: 20px;
}
}
@media (min-width: 414px) {
.post_1{
  width: 95%;
    height: 530px;
    background-color: #373737;
    border-radius: 30px;
    margin-right: 0px;
}
.post_2{
  width: 95%;
    height: 530px;
    background-color: #373737;
    border-radius: 30px;
    margin-right: 0px;
}
}

@media (min-width: 375) {
.post_1{
  width: 95%;
    height: 500px;
    background-color: #373737;
    border-radius: 30px;
    margin-right: 0px;
}
.post_2{
  width: 95%;
    height: 530px;
    background-color: #373737;
    border-radius: 30px;
    margin-right: 0px;
}
}

@media (min-width: 430px) {
  body{
    display: none;
  }
  mobileMenu{
    display: flex;
  }
  .logo {
  height: 4em;
  will-change: filter;
  transition: filter 300ms;
  }
  header h2{
    width: 55%;
    height: 85px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #about{
    visibility: hidden;
  }
  #news{
    visibility: hidden;
  }
  #soc-seti{
    visibility: hidden;
    
  }

  #about_m{
    padding-right: 20px;
  }
  #news_m{
    padding-right: 20px;
  }
  menu{
    display: none;
  }
  news{
    padding-top: 20px;
    width: 100%;
    height: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #news_p{
  padding-top: 0px;
  padding-left: 0px;
  font-size: 1.6rem; 
}
#about_p_o_nas{
  padding-top: 2090px;
  padding-left: 0px;
  font-size: 1.6rem; 
}
.about_title {
  padding-top: 40px;
  padding-left: 0px;
    width: 100%;
    height: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.post_1{
  width: 95%;
  height: 530px;
  background-color: #373737;
  border-radius: 30px;
  margin-right: 0px;
}
}
/* 


ОСНОВНАЯ ЧАСТЬ СТИЛЕЙ САЙТА


*/
:root {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;

  color-scheme: light dark;
  color: rgba(255, 255, 255, 0.87);
  background-color: #242424;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
  margin: none;
  padding: none;
}
header{
  background-color: rgb(241, 241, 241);
}
* {
  margin: 0;
  padding: 0;
 }
 html, body{
  background-color: #242424;
  color: #ebebeb;
  max-width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
}
a{
  color: #ebebeb;
}
header{
  background-color: #292929;
  width: 100%;
  height: 85px;
  display: flex;
  justify-content: left;
  align-items: center;
  margin: none;
  padding: none;
}
#app {
  margin: none;
}
@media (prefers-color-scheme: light) {
  :root {
    color: #213547;
    background-color: #ffffff;
  }
  mobileMenu a{
  text-decoration: none;
  color: #213547;
}
footer{
    background-color: #f3f3f3;
}
  html, body {
  background: #ffffff;
  color: #213547;
}
  header{
    background-color: rgb(241, 241, 241);
  }
  mobileMenu{
  background-color: #eeeeee;
  color: #213547;

}
.post_2{
  background-color: rgb(243, 243, 243);
}
.post_1{
  background-color: #f3f3f3;
}
}
</style>
