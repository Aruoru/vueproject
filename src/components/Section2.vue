<template>
      <div clas="section2_content">
                    <div class="section2_text">
                        <h1>SPEAKUS стирает языковой барьер для гостей ваших мероприятий</h1>
                        <p>Организуем синхронный перевод с помощью ноутбука и интернет канала</p>
                        <p>Передаем аудио и видео высокого качества, ведь ценно каждое слово</p>
                        <p>Слушайте трансляцию на родном языке через смартфон или планшет</p>
                    </div>
                    <div class="section2_imgbox">
                        <p class="section2_just">Так просто!</p>
                    <img src="@/assets/section2.png" alt="image" class="section2_img" />
                    <button class="section2_btn">УЗНАТЬ БОЛЬШЕ</button>
                </div>
                </div>
</template>

<script>
export default {
  name: 'Section2',
};
</script>


<style>
.section2_content {
    background-color: white;
}
.section2_text h1 {
color: #3585F5;
text-align: center;
font-family: proxima;
font-size: 30px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 33.6px */
margin-top: 110px;
}
.section2_text p {
color: #8A8A8A;
text-align: center;
font-family: proxima;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 17.92px */
margin-top: 30px;
}
.section2_img {
 margin-top: 14px;
 border: none;
 
}
.section2_imgbox {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}

 .section2_btn {
    border-radius: 20px;
background: #3585F5;
color: #FFF;
text-align: center;
font-family: proxima;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 17.92px */
padding: 16px 24px;
border-color: none;
 }
 .section2_btn p {
    color: #FFF;
text-align: center;
font-family: proxima;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 112%; /* 17.92px */
 }

 .section2_just{
  color: #3585F5;
  font-family: proxima;
  font-size: 22px;
  font-weight: 800px;
  margin-top: 42px;
 }

 .section2_btn:hover {
    border-radius: 20px;
border: 2px solid #3585F5;
background-color: #FFF;
color: #3585F5;
border-color: none;
 }
</style>