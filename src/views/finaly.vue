<template>
     <div class="loginPage">
        <div class="form">
          <h2>تحميل متطلبات الحصول على تقرير الرصانه </h2>
          <div class="contener">
          <form @submit.prevent="login">
    <div class="form-group text-right">
        <label for="exampleInputEmail1">الاعتمادية</label>
        <input
          type="text"
          class="form-control"
          id="UserName"
          aria-describedby="emailHelp"
          v-model="text"
          placeholder="Your answer"
          required
        />
      </div>
      <div class="form-group text-right">
        <label for="exampleInputEmail1">ملاحضات اللجنة</label>
        <br>

      <textarea  required></textarea>
      </div>
      <div class="form-group text-right">
        <label for="exampleInputEmail1">اعضاء اللجنة</label>
        <br>
        <div class="rr">
        <input
          type="text"
          id="UserName"
          aria-describedby="emailHelp"
          v-model="text"
          placeholder="الاسم الاول"
          required
        />
        <input
          type="text"
          id="UserName"
          aria-describedby="emailHelp"
         
          v-model="text"
          placeholder="الاسم الثاني"
          required
        />
        <input
          type="text"
          id="UserName"
          aria-describedby="emailHelp"
          v-model="text"
          placeholder="الاسم الثالث"
          required
        />
    </div>
      </div>
<button
type="submit"
class="btn btn-success btn-block p-3"
>تحميل</button>
<br> 
</form>
</div>
</div>
<div class="lotte">
 
  <lottie-player src="https://assets9.lottiefiles.com/packages/lf20_IrrfGz.json"  background="transparent"  speed="1"  style="width: 600px; height: 500px;"  loop  autoplay></lottie-player>
</div>
<br>
</div>
</template>
<style scoped>
*{
    margin: 0;
    padding: 0;
}


.loginPage {
    display: flex;
    direction: rtl;
    justify-content: space-around;
    margin: 10px;
    min-height: 700px;
  }
  label {
    font-size: 18px;
}
  .loginPage .form {
    width:50%;
    height: 300px;
    padding: 20px;
  }
  .loginPage .form .contener{
      width: 400px;
  }
  .loginPage .form h2 {
      width: 90%;
    text-align: center;
    padding: 15px;
    border-bottom: 1px solid rgba(2, 2, 2, .8);
  }
  .loginPage .form .btn {
    margin: 51px 85px 91px 0;
    outline: none;
    transition: all  .8s ease-in-out;
    font-size: 20px;
    width: 250px;
    border-radius: 30px;
    border: 1px solid #fff;
  }
  .loginPage .form .btn:hover{
    transition: all .4s ease-in-out;
    border: 1px solid #000;
  }
  .loginPage .form .btn a {
    color: #fff;
    outline: none;
    text-decoration: none;
    transition: all  .8s ease-in-out;
}
.form-group {
    margin: 54px 0px -24px 0;
}
.form-control {
    transition: all .5s ease-in-out;
    width: 85%;}
    textarea
{
    width: 80%;
    height: 100px;
    margin: 0 0 0 0;
}
input {
    transition: all .5s ease-in-out;
    width: 130px;
    padding: 4px 21px 4px 0;
}
input:hover {
    transform: scale(1.1,1.1);
}
.loginPage .lotte {
    margin-top:100px;
  width: 50%;
  padding: 15px;
  position: relative;
}
.loginPage .lotte img {
    position: fixed;
    margin: 35px -682px 0 0;
    width: 50%;
}
</style>