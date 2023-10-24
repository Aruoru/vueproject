<template>
    <section class="section9">
        <h1 class="section9_title"> С нами работают</h1>
        <ul class="section9_text">
            <li class="section9_des">Компании </li>
            <li class="section9_des">VC фонды </li>
            <li class="section9_des">Конференц-залы </li>
            <li class="section9_des"> Гостиницы</li>
            <li class="section9_des"> Новости и СМИ</li>
            <li class="section9_des"> Технопарки</li>
            <li class="section9_des"> Развлечения и отдых</li>
        </ul>
        <img src="@/assets/section9.png" alt="img"  class="section9_img">
        <div class="button9">
        <button class="section9_more">ПОПРОБОВАТЬ БЕСПЛАТНО</button>
        <button class="section9_order">ЗАКАЗАТЬ ПЕРЕВОД</button>
    </div>
        
    </section>
</template>

<style>
.section9_title{
    margin-top: 400px;
    font-family: proxima;
font-size: 42px;
font-weight: 800;
line-height: 47px;
color: #3585F5;
text-align: center;
margin-bottom: 22px;
}

.section9{
    display: flex;
    flex-direction: column;
}

.section9_text{
  text-align: center;
  word-spacing: 15px;

}

.section9_des{
    font-family: proxima;
font-size: 16px;
font-weight: 400;
line-height: 18px;
letter-spacing: 0em;
color: black;
display: inline;
list-style: circle;


}

.button9{
    display: flex;
    flex-direction: row;
    justify-content: center;
    margin-top: 50px;
}

.section9_more{
    background-color: #3585F5;
border-radius: 20px;
border-color: none;
padding: 16px 7px 16px 7px;
font-family: proxima;
font-size: 14px;
font-weight: 700;
line-height: 16px;
text-align: center;
color: white;
}

.section9_more:hover{
    color:#3585F5;
    background-color: white;
}


.section9_order{
background-color: white;
border-radius: 20px;
border-color: #3585F5;
border-style: solid;
padding: 16px 35px 16px 35px;
font-family: proxima;
font-size: 14px;
font-weight: 700;
line-height: 16px;
text-align: center;
color: #3585F5;
margin-left: 26px;


}

.section9_order:hover{
    background-color: #3585F5;
    color: white;
}

.section9_img{
max-width: 1145.76px;
align-items: center;
justify-content: center;
margin-left: 148px;
margin-right: 146px;
}
</style>