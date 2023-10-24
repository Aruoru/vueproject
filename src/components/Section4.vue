<template>
     <section class="section4">
                    <div class="section4_background">
                        <img src="@/assets/section4_cover.png" alt="section4" class="section4_cover">
                    </div>
                    <div class="section4_container">
                        <div class="section4_title">Стираем языковые барьеры</div>

                    <div class="section4_description">
                        <div class="section4_description_img">
                            <img src="@/assets/section4_phone.png" alt="phone"/>
                        </div>
                        <div class="section4_description_text">
                        <ol class="section4_list">
                            <li>Установите приложение</li>
                            <li>Отсканируйте код
                                конференции</li>
                                <li>Слушайте на своем языке</li>
                            </ol>
                        </div>
                        </div>
                            <div class="section4_stores">
                                <img src="@/assets/play_market.png" alt="play market" class="section4_playmarket"/>
                                <img src="@/assets/app_store.png" alt="app store" class="section4_appstore" />
                                <img src="@/assets/mobil.png" alt="mobil" class="section4_mobil"/>
                            </div>
                    </div>
                
    </section>
</template>

<script>
export default {};
</script>

<style>

.section4 {
    width: 100%;
    align-items: center;
}
.section4_background {
    position: absolute;
}
.section4_container {
    position: relative;
    display: flex;
    flex-direction: column;
    /* justify-content: center; */
    align-items: baseline;
    left: 50%;
    margin-left: -80px;
}
.section4_title {
    margin-top: 60px;
}
.section4_description{
    display: flex;
    gap: 40px;
    margin-top: 24px;
}
.section4_description_text li {
    color: #FFF;
    font-family: proxima;
font-size: 24px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 26.88px */
margin-top: 36px;

}
.section4_description_text li :nth-child(2) {
    margin-top: 36px;
}
.section4_title {
color: #FFF;
text-align: center;
font-family: proxima;
font-size: 44px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 49.28px */
}
.section4_stores {
margin-top: 46px;
}

.section4_playmarket{
    margin-right: 6px;
}

.section4_appstore{
    margin-right: 6px;

}

.section4_cover{
    width: 100%;
}
</style>