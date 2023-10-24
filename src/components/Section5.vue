<template>
      <section class="section5">
                    <div class="section5_content">
                        <img src="@/assets/section5.svg" alt="section5_background" class="section5_cover" />
                        <div class="section5_container">
                            <h1 class="section5_title">Работаем на мероприятиях любого размера</h1>
                            <div class="section5_text">
                                <ul class="section5_list">
                                    <li>Конференция</li>
                                    <li>Форум</li>
                                    <li>Саммит</li>
                                </ul>
                                <ul class="section5_list">
                                    <li>Встреча делегации</li>
                                    <li>Собрание акционеров</li>
                                    <li>Заседание</li>
                                </ul>
                                <ul class="section5_list">
                                    <li>Семинар</li>
                                    <li>Митап</li>
                                    <li>Вебинар</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </section>
                <section class="section5_second_part">
                    <div class="section5_box">
                        <img src="@/assets/section5_1_img.png" alt="section5_1_img" class="section5_image"/>
                        <!-- <div class="section5_hover">
                        <h4 class="section5_image_title">Вебинар</h4>
                        <p class="section5_image_text">Расширяем вашу глобальную аудиторию за счет перевода на любые языки мира</p>
                        </div> -->
                    </div>
                    <div class="section5_box">
                            <img src="@/assets/section5_2_img.png" alt="section5_2_img" class="section5_image"/>
                            <!-- <div class="section5_hover">
                                <h4 class="section5_image_title">Выступление со сцены</h4>
                            <p class="section5_image_text">Обеспечиваем синхронный перевод аудио- и видеотрансляции вашей презентации</p>
                            </div> -->
                            </div>
                            <div class="section5_box">
                                <img src="@/assets/section5_3_img.png" alt="section5_3_img" class="section5_image"/>
                                <!-- <div class="section5_hover">
                                <h4 class="section5_image_title">Подиумная дискуссия</h4>
                                <p class="section5_image_text">Поддерживаем синхронный перевод выступления нескольких участников и вопросы слушателей с разных языков</p>
                                </div> -->
                                </div>
                                <div class="section5_box">
                                    <img src="@/assets/section5_4_img.png" alt="section5_4_img" class="section5_image"/>
                                    <!-- <div class="section5_hover">
                                        <h4 class="section5_image_title">Телеконференция</h4>
                                    <p class="section5_image_text">Все участники получают синхронный перевод вне зависимости от используемого программного обеспечения для связи</p>
                                    </div> -->
                                    </div>
                    </section>
</template>

<script>
export default {};
</script>

<style>
.section5 {
    display: flex;
    flex-direction: column;
    margin-top: 54px;
    width: 100%;

}
.section5_cover {
    position: absolute;
}
.section5_container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

}
.section5_title {
position: relative;
color: #FFF;
font-family: proxima;
font-size: 42px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 47.04px */
margin-top: 192px;
}
.section5_text {
    position: relative;
    display: flex;
    gap: 148px;
    margin-top: 28px;
    line-height: 8px;
    
}
.section5_list li {
    color: #FFF;
    font-family: proxima;
    font-size: 22px;
    font-style: normal;
    font-weight: 400;
    line-height: 112%; /* 24.64px */
gap: 8px
}
.section5_second_part {
    width: 100%;
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
    left: 0;
}
.section5_box {
align-items: center;
}
.section5_image {
   /* position: absolute; */
   display: block;
   z-index: 1;
   opacity: 1;
   width: 360px;
height: 277px;



}
/* .section5_hover {
 opacity: 0;
 z-index: 0;
  position:relative; */
  /* transform:translate(-50%, 0);
  transition: 0.5s;*/
  /* width:100%; */
  /*font-size:22px; */
  /* background-color:rgba(0, 0, 0, 0.5); */
  /* border-top:5px solid green; */
  /* color:#fff;
}
.section5_hover:hover {
    opacity:2;
    z-index: 5; */
    /* } */


/* .section5_image_title {
    /* position: relative; */
    /* z-index: 0;
    position:relative;
    background-color:rgba(0, 0, 0, 0.5);
    color: #FFF;
text-align: center;
font-size: 24px;
font-family: proxima;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 26.88px */
/* margin-top: 40px;
align-items: center; */ 
/* 
} */ 
/* .section5_image_text {
    margin-top: 30px;
    /* position: relative; */
    /* width: 308px;
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 20.16px */
/* } */ 

</style>