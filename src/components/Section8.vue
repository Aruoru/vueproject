<template>
    <section class="section8">
                    <img src="@/assets/section8_cover.svg" alt="section8_background" class="section8_cover" />
                    <div class="section8_container">
                        <div class="section8_content">
                            <img src="@/assets/micro.png" alt="microphone" class="section8_img"/>
                            <h3 class="section8_title">Простота использования</h3>
                            <p class="section8_description">Избавьтесь от дорогого оборудования и километров проводов</p>
                        </div>
                        <div class="section8_content">
                            <img src="@/assets/map.png" alt="map" class="section8_img"/>
                            <h3 class="section8_title">Мобильность и экономия</h3>
                            <p class="section8_description">Организация перевода в любом месте и помещении. Сам переводчик тоже может работать удаленно</p>
                        </div>
                        <div class="section8_content">
                            <img src="@/assets/talk.png" alt="talk" class="section8_img"/>
                            <h3 class="section8_title">Мультиязычные мероприятия</h3>
                            <p class="section8_description">Одновременная работа нескольких переводчиков. Слушатели выбирают свой язык перевода</p>
                        </div>
                        <div class="section8_content">
                            <img src="@/assets/apple_adr.png" alt="apple_android" class="section8_img"/>
                            <h3 class="section8_title">Устройство слушателя</h3>
                            <p class="section8_description">Слушатели получают перевод на смартфон или планшет с нашим мобильным приложением</p>
                        </div>
                        <div class="section8_content">
                            <img src="@/assets/computer.png" alt="computer" class="section8_img"/>
                            <h3 class="section8_title">Устройство докладчика</h3>
                            <p class="section8_description">Поддерживаются любые портативные и десктопные устройства</p>
                        </div>
                        <div class="section8_content">
                            <img src="@/assets/wifi.png" alt="wi-fi" class="section8_img"/>
                            <h3 class="section8_title">Подключение к интернету</h3>
                            <p class="section8_description">Рекомендуемая скорость канала от 5 Мбит/с</p>
                        </div>
                    </div>
                </section>
</template>


<style>
.section8_cover {
    position: absolute;
    margin-top: 144px;
}
.section8_container {
    position: relative;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding-top: 260px;
    /* align-items: center; */
}
.section8_content {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 18px;
    padding: 35px 50px;
}
.section8_content h3 {
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 24px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 26.88px */
margin-top: 20px;
}

.section8_content p {
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 17.92px */
width: 280px;
}
</style>