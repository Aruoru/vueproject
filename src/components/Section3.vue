<template>
     <section class="section3">
                <div class="section3_main_title"><h1>НАШИ</h1><h1>ТАРИФЫ</h1></div>
                <div class="section3_conditions">
                    <div class="section3_content">
                        <h2 class="section3_title">АНТИВИРУСНЫЙ ОНЛАЙН</h2>
                        <hr class="section3_line" />
                        <p class="section3_description">Возможность бесплатно провести 
                            небольшую встречу с коллегами/
                            партнерами удаленно, оценить
                            возможность платформы</p>
                            <div class="section3_description2">
                                <p>До 20 слушателей</p>
                                <p>Продолжительность - от 1 до 8 часов</p>
                                <p>Не более 2-х переводчиков</p>
                            </div>
                                <p class="section3_about_price">Стоимость создания
                                    конференции</p>
                                    <div class="section3_price"><p>0</p>руб</div>

                    </div>

                    <div class="section3_content">
                        <h2 class="section3_title">БАЗОВЫЙ ОНЛАЙН</h2>
                        <hr class="section3_line" />
                        <p class="section3_description">Покрывает базовые потребности –
                            идеально для вебинаров, прямых
                            трансляций, встреч с клиентами до 30
                            человек</p>
                            <div class="section3_description2">
                                <p>До 30 слушателей</p>
                                <p>Продолжительность - от 1 до 8 часов</p>
                                <p>Не более 2-х переводчиков</p>
                            </div>
                                <p class="section3_about_price">Стоимость создания
                                    конференции</p>
                                    <div class="section3_price">от<p>5 000</p>руб</div>

                    </div>

                    <div class="section3_content">
                        <h2 class="section3_title">БИЗНЕС</h2>
                        <hr class="section3_line" />
                        <p class="section3_description">Участие в мероприятиях большого
                            количества специалистов, сложные
                            переговоры с партнерами из разных стран
                            на протяжении нескольких часов</p>
                            <div class="section3_description2">
                                <p>До 100 слушателей</p>
                                <p>Продолжительность - от 1 до 8 часов</p>
                                <p>Не более 6 пар переводчиков</p>
                            </div>
                                <p class="section3_about_price">Стоимость создания
                                    конференции</p>
                                    <div class="section3_price">от<p>9 000</p>руб</div>

                    </div>

                    <div class="section3_content">
                        <h2 class="section3_title">EVENT</h2>
                        <hr class="section3_line" />
                        <p class="section3_description">Мероприятия event-агентств с четким
                            регламентом, массовые мероприятия 
                            и масштабные конференции на полный
                            рабочий день</p>
                            <div class="section3_description2">
                                <p>До 300 слушателей</p>
                                <p>Продолжительность - от 1 до 8 часов</p>
                                <p>Не более 7 пар переводчиков</p>
                            </div>
                                <p class="section3_about_price">Стоимость создания
                                    конференции</p>
                                    <div class="section3_price">от<p>20 000</p>руб</div>

                    </div>

                    <div class="section3_content">
                        <h2 class="section3_title">ИНДИВИДУАЛЬНЫЙ</h2>
                        <hr class="section3_line" />
                        <p class="section3_description">Если ваша задача не подходит под
                            имеющиеся тарифы, мы предложим
                            уникальный сценарий для вашего
                            мероприятия</p>
                            <div class="section3_description2">
                                <p>Количество участников,
                                    продолжительность не ограничены</p>
                            </div>
                                <p class="section3_about_price">Стоимость создания
                                    конференции</p>
                                    <div class="section3_price"><h3>По запросу</h3></div>
                    </div>
                </div>  
                    <div class="section3_download">Скачать полную версию тарифов</div>
            </section>
</template>

<script>
export default {};
</script>

<style>
.section3 {
    margin-top: 32px;
   display: flex;
   flex-direction: column;
   align-items: center;
}
.section3_main_title {
    display: flex;
    justify-content: center;
    gap: 12px;
}
.section3_main_title :first-child {
color: #8A8A8A;
text-align: center;
font-family: proxima;
font-size: 30px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 33.6px */
}
.section3_main_title :last-child {
    color: #3585F5;
font-family: proxima;
font-size: 30px;
font-style: normal;
font-weight: 800;
line-height: 112%;

}
.section3_conditions {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    align-items: center;
    margin-top: 40px;
    justify-content: center;
}
.section3_content {
    width: 360px;
    height: 432px;
    background: #3585F5;
    text-align: center;
    color: #FFF;
    padding: 36px 20px;

}
.section3_title {
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 22.4px */
}
.section3_line {
    margin: 14px 20px;
}
.section3_download {
    margin-top: 30px;
    align-items: center;
}
.section3_description {
 color: #FFF;
text-align: center;
font-family: proxima;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 17.92px */
}
.section3_description2 {
    padding-top: 32px;
}
.section3_description2 p {
color: #FFF;
text-align: center;
font-family: proxima;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 17.92px */

}
.section3_about_price {
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 20px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 22.4px */
padding-top: 36px;
}
.section3_price {
    display: flex;
    align-items: baseline;
    gap: 8px;
    justify-content: center;
    padding-top: 16px;
color: #FFF;
text-align: right;
font-family:  proxima;
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 20.16px */
}
.section3_price p {
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 46px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 51.52px */

}
.section3_price h3 {
color: #FFF;
text-align: center;
font-family: proxima;
font-size: 30px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 33.6px */
margin-top: 36px;
}
.section3_download {
    margin-top: 30px;
    margin-bottom: 60px;
    color: #4579B2;
    font-family: proxima;
font-size: 14px;
font-weight: 400;
line-height: 16px;
}

.section3_download:hover{
    color: #b2a545;
    
}

</style>