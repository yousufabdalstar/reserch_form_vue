<template>
<div>
    <div class="loginPage">
    <div class="form">
      <h2>تحميل متطلبات الحصول على تقرير الرصانه </h2>
      <div class="contener">
      <form >
        <div class="form-group text-right">
            <label for="exampleInputEmail1"> اسم الباحث باللغة الانكليزية</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">عنوان البحث باللغة الانكليزية</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">المجلد</label>
            <input
              type="number"
              class="form-control"
              id="number"
              aria-describedby="emailHelp"
              v-model="number"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">الاصدار</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">عنوان المجلة</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">دار النشر</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">رابط البحث في المجلة</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
          </div>
          <div class="form-group text-right">
            <label for="exampleInputEmail1">تاريخ النشر</label>
            <input
              type="text"
              class="form-control"
              id="text"
              aria-describedby="emailHelp"
              v-model="text"
              placeholder="Your answer"
              required
            />
        
          </div>
          <div class="form-group text-right">
          <label for="exampleInputEmail1">رقم المجلة</label>
          <select class="form-control form-control-lg" required>
            <option>ISSN</option>
            <option>ISSV</option>  
            </select>
          </div>
          <div class="form-group text-right">
              <div class="aa">
            <label for="exampleInputEmail1">حالة البحث</label>
            <select class="form-control form-control-lg" required>
              <option>مقبول</option>
              <option>منشور</option>  
              </select>
            </div>
            </div>
            <div class="form-group text-right">
                <div class="aa2">
                <label for="exampleInputEmail1">تصنيف المجلة</label>
                <select class="form-control form-control-lg" required>
                  <option>scopus</option>
                  <option>clarivate</option>  
                  <option>مجلة عالمية</option>
                  <option>مجلة محلية</option>  
                  </select>
                </div>
                </div>

                <div id="wrapper">
                  <main id="main">
                      <form action="#">
                         <label class="ff" for="exampleInputEmail1">تحميل البحث او القبول</label>
                         <br />
                          <p><span class="file-input"><input class="file" type="file" name="file" size="40" id="file" /></span></p>
                           <label class="ff" for="exampleInputEmail1">واجهة المجلة</label>
                         <br /><span class="wpcf7-form-control-wrap file-input"><input class="wpcf7-form-control wpcf7-file" type="file" name="file-input" size="40" /></span>
                      </form>
                  </main>
              </div>
               
    <button
    type="submit"
    class="btn btn-success btn-block p-3"
  >رفع</button>
  <br> 
</form>
      </div>
</div>
    <div class="lotte">
     
      <lottie-player src="https://assets6.lottiefiles.com/packages/lf20_LNnKZv.json"  background="transparent"  speed="1"  style="width: 600px; height: 500px;"  loop  autoplay></lottie-player>
    </div>
    <br>
  </div>
  </div>
</template>
<style scoped>
*{
    margin: 0;
    padding: 0;
}
.ff{
  text-align: right;
  padding-bottom: 25px;
}
.form-control {
    display: block;
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555;
    background-color: #fff;
    background-image: none;
    border: 1px solid #ccc;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    -webkit-transition: border-color ease-in-out .15s, -webkit-box-shadow ease-in-out .15s;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.loginPage {
    display: flex;
    direction: rtl;
    justify-content: space-around;
    margin: 10px;
    min-height: 700px;
  }
  
  .loginPage .form {
    width:40%;
    height: 300px;
    padding: 20px;
  }
  .loginPage .form .contener{
      width: 400px;
  }
  .loginPage .form h2 {
    text-align: center;
    padding: 15px;
    border-bottom: 1px solid rgba(2, 2, 2, .8);
  }
  label{font-size: 16px;}
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
  .loginPage .lotte {
      margin-top:100px;
    width: 50%;
    padding: 15px;
    position: relative;
  }
  .loginPage .lotte img {
    position: fixed;
    margin: 35px -719px 0 0;
    width: 59%;
  }
  .loginPage .form-group{
      margin-top: 25px;
  }
  .form-control{
      transition: all  .8s ease-in-out;

  }
  .form-control:hover{
    transition: all .4s ease-in-out;
    border: 1px solid #000;
  }

  .loginPage .form-group .aa{
    margin-top: 45px;
}
.loginPage .form-group .aa2{
    margin: 44px 0 83px 0;
}
.loginPage .form-group .btbt{
    width: 200px;
}
.loginPage .form-group .rr{
    display: inline;
}
input[type="file"] {
    border-radius: 30px;
    margin: 7px 18px 0 0;
    border: 1px solid rgb(63, 6, 6);
    width: 228px;
    height: 43px;
    padding: 7px 47px 0 0;
}
textarea
{
    width: 250px;
    height: 100px;
    margin: 0 0 0 0;
}
input {
    transition: all .5s ease-in-out;
    width: 115px;
    margin-left: 5px;
   
    padding: 4px 21px 4px 0;
}
input:hover{
    transform: scale(1.1,1.1);
}
input[type="file"] {

  border-radius: 30px;
  margin: 7px 18px 0 0;
  border: 1px solid rgb(63, 6, 6);
  width: 228px;
  height: 43px;
  padding: 7px 47px 0 0;
}

input:hover{
transform: scale(1.1,1.1);
}

[type='file'] {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
opacity: 0;
z-index: 10;
cursor: pointer;
}

.file-input {
display: block;
position: relative;
overflow: hidden;
cursor: pointer;
}

.file-input:before {
content: '\00a0';
}

.file-input:after {
content: 'Choose file';
position: absolute;
top: 0;
right: 0;
bottom: 0;
}

.file-input:after {
padding: .75em 1.5em;
appearance: none;
outline: none;
line-height: normal;
border-radius: 0;
border: none;
}

.file-input:after {
font: inherit;
line-height: normal;
cursor: pointer;
text-transform: uppercase;
text-align: center;
letter-spacing: 0.14286em;
border-width: 2px;
border-style: solid;
transition: all 0.3s cubic-bezier(0.5, 0, 0, 1);
}

.file-input:after {
background-color: black;
border-color: black;
color: white;
}

.file-input:hover:after, .file-input:focus:after, .file-input:active:after {
color: black;
background: white;
border-color: black;
text-shadow: none;
}

.file-input, label[for], span.floating-label {
padding: calc(.75em + 2px) 1.25em;
appearance: none;
outline: none;
line-height: normal;
border-radius: 0;
border: none;
}

.file-input {
font: inherit;
line-height: normal;
width: 100%;
box-sizing: border-box;
display: block;
background: rgba(0, 0, 0, 0.05);
outline: none;
border: none;
box-shadow: inset 0 1px 1px 0px rgba(0, 0, 0, 0.1);
transition: all .15s ease;
color: inherit;
margin-top: -34px;
}

.file-input:placeholder {
color: inherit;
}

.error.file-input, .error .file-input {
background-color: #ffe6e6;
}

.form:not(.has-floated-label) .file-input:active, .form:not(.has-floated-label) .file-input:focus {
border-color: transparent transparent black transparent;
}

.file-input:focus {
box-shadow: inset 0 2px 1px 0px rgba(0, 0, 0, 0.2);
background: rgba(0, 0, 0, 0.1);
}

h4{
margin: 0 0 0 222px;
  padding: 4px 0 46px 0;
  font-weight: bold;
}
h3{ margin:0 -68px 0 236px;
font-size: 19px;
font-weight: bold;
}

form {
max-width: 60rem;
margin: 2rem;
}

form > label, form > p {
margin: 1.5em 0;
position: relative;
display: block;
}

form > label br, form > p br {
display: none;
}

p + h3 {
margin-top: 2em;
}

h3 {
margin-bottom: 1.5em;
}

.background-gradient body {
background: linear-gradient(to right bottom, #f3904f, #3b4371);
color: white;
text-shadow: 0 1px 2px rgba(0, 0, 0, 0.5);
}

svg path {
fill: black;
}

</style>