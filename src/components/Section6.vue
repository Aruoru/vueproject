<template>
    <section class="section6">
                    <div class="section6_container">
                        <h1 class="section6_title">Мы помогаем всем участникам event-рынка</h1>
                        <div class="section6_content">
                            <div class="section6_box">
                                <img src="@/assets/director.png" class="section6_box_img"/>
                                <div class="section6_box_title">Владелец 
                                    <br>ивент-площадки</div>
                                <div class="section6_box_description">"Проводим больше разных мероприятий и экономим на оборудовании"</div>
                            </div>
                            <div class="section6_box">
                                <img src="@/assets/ivent.png" class="section6_box_img" />
                                <div class="section6_box_title">Инвест агентство</div>
                                <div class="section6_box_description">"Можем заказать перевод мероприятия в самые сжатые сроки"</div>
                            </div>
                            <div class="section6_box">
                                <img src="@/assets/meneger.png" class="section6_box_img" />
                                <div class="section6_box_title">Менеджер ивент-площадки</div>
                                <div class="section6_box_description">"Нам важен подбор качественных переводчиков и хороший звук"</div>
                            </div>
                            <div class="section6_box">
                                <img src="@/assets/producer.png" class="section6_box_img" />
                                <div class="section6_box_title">Продюсер мероприятий</div>
                                <div class="section6_box_description">"Можем предложить синхронный перевод даже в небольшом коворкинге"</div>
                            </div>
                            <div class="section6_box">
                                <img src="@/assets/buro.png" class="section6_box_last_img" />
                                <div class="section6_box_last_title">Бюро 
                                    <br>перевода</div>
                                <div class="section6_box_description">"Наши переводчики могут работать удаленно, поддерживая здоровый баланс между работой и личной жизнью"</div>
                            </div>
                        </div>
                       
                    </div>
                </section>
</template>

<script>
export default {};
</script>

<style>
.section {
    width: 100%;
}
.section6_title {
color: #3585F5;
font-family: proxima;
font-size: 30px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 33.6px */
text-align: center;
margin-top: 94px;
}
.section6_content {
    margin-top: 94px;
    display: flex;
    justify-content: space-around;
}

.section6_box {
    width: 145px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.section6_box :last-child {
    width: 180px;
}
.section6_box_title {
    width: 140px;
    margin-top: 30px;
    color: #3585F5;
text-align: center;
font-size: 18px;
font-family: proxima;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 20.16px */
}

.section6_box_last_title{
    width: 140px;
    margin-top: 30px;
    color: #3585F5;
text-align: center;
font-size: 18px;
font-family: proxima;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 20.16px */

}
.section6_box_description {
    width: 160px;
    margin-top: 12px;
    color: #8A8A8A;
text-align: center;
font-family: proxima;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 15.68px */
align-items: center;
}
.section6_box_title :last-child {
    margin-top: 40px;
    
}
.section6_box_last_img {
    padding-left: 50px;
}



</style>