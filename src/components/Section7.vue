<template>
     <section class="section7">
                    <hr class="section7_line" />
                    <h1 class="section8_title">Экономим время и деньги</h1>
                    <div class="section7_container">
                    <div class="section7_content">
                        <img src="@/assets/section7_list_1.svg" alt="list" class="section7_list" />
                        <p>Не арендуйте и не настраивайте дорогостоящее оборудование</p>
                    </div>
                    <div class="section7_content">
                        <img src="@/assets/section7_list_2.svg" alt="list" class="section7_list" />
                        <p>Не переплачивайте за полную дневную стоимость аренды оборудования</p>
                    </div>
                    <div class="section7_content">
                        <img src="@/assets/section7_list_3.svg" alt="list" class="section7_list" />
                        <p>Не платите штрафы за поломку и утерю приемников</p>
                    </div>
                    <div class="section7_content">
                        <img src="@/assets/section7_list_4.svg" alt="list" class="section7_list" />
                        <p>Не платите за трансфер и проживание ваших переводчиков</p>
                    </div>
                    <div class="section7_content">
                        <img src="@/assets/section7_list_5.svg" alt="list" class="section7_list" />
                        <p>Не тратьте дни и недели в поисках людей и техники</p>
                    </div>
                </div>
                </section>
</template>

<script>
export default {};
</script>

<style>
.section7 {
    width: 100%;
    color: #3585F5;
font-family: proxima;
font-size: 22px;
font-style: normal;
font-weight: 400;
line-height: 112%; /* 24.64px */

}
.section7_line {
    margin: 88px 150px 116px;
    background: #3585F5;
    border: solid #3585F5;
}
.section8_title {
    color: #3584F4;
text-align: center;
font-family: proxima;
font-size: 30px;
font-style: normal;
font-weight: 800;
line-height: 112%; /* 33.6px */
}
.section7_container {
    display: flex;
    flex-direction: column;
    margin-left: 30%;
    /* align-items: center; */
}
.section7_content {
    display: flex;
    align-items: center;
    margin-top: 20px;
    gap: 24px;
  
  
   
}


   
</style>