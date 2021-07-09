<template>
<div>
      <h2>تحميل متطلبات الحصول على تقرير الرصانة </h2>
      <div class="form">
   
      <div class="contener">
    <table class="table table-hover">
        <thead>
          <tr>
            <th scope="col">التسلسل</th>
            <th scope="col">اسم الباحث باللغة الانكليزية</th>
            <th scope="col">عنوان البحث باللغة الانكليزية</th>
            <th scope="col">المجلد</th>
            <th scope="col">عنوان المجلة</th>
            <th scope="col">دار النشر</th>
            <th scope="col">رابط البحث في المجلة</th>
            <th scope="col">تاريخ النشر</th>
            <th scope="col">رقم المجلة</th>
            <th scope="col">حالة البحث</th>
            <th scope="col">تصنيف المجلة</th>
            <th scope="col">تحميل البحث او القبول</th>
            <th scope="col">التفاصيل</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Mohanned ali harif</td>
            <td>CPU</td>
            <td>12</td>
            <td>ISSV</td>
            <td>Otto</td>
            <td>@mdo</td>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
            <td>Mark</td>
            <td>Otto</td>
            
            <td>
              <button><a href="finaly.html"> عرض التفاصيل</a></button>
            </td>

          </tr>
          <tr>
            <th scope="row">2</th>
            <td>jasim mohaed</td>
            <td>Thornton</td>
            <td>@fat</td>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
            <td>Mark</td>
            <td>Otto</td>
            <td>
              <button><a href="finaly.html"> عرض التفاصيل</a></button>
            </td>
          </tr>
         
        </tbody>
      </table>
    </div>
</div>
</div>
</template>
<style scoped>
body{
    padding: 0;
    margin: 0;

}
.form{
    width: 0;
    text-align: center;
    margin: 234px 0 25px 0;
    border: 1px solid#000;
    
}
 .form .contener{
    width: 90%;
    text-align: center;
    margin: 0 0 0 79px;
}
h2{
    text-align: center;
    padding: 15px;
    border-bottom: 1px solid rgba(2, 2, 2, .8);
    width: 41%;
    margin: 40px 0 -151px 352px;
}

table{
    position: absolute;
    float: right;
    transform: translate(-3%,-3%);
    border-collapse: collapse;
    border: 1px solid#bdc3c7;
    box-shadow: 2px 2px 12px rgba(0, 0, 0, 90%);
    border: 1px solid rgba(2, 2, 2, .2) -1px -1px 8px rgba(0,0,0,0.2);
  }
  tr{
      transition: all .2s ease-in-out;
  }
  .table > caption + thead > tr:first-child > th, .table > colgroup + thead > tr:first-child > th, .table > thead:first-child > tr:first-child > th, .table > caption + thead > tr:first-child > td, .table > colgroup + thead > tr:first-child > td, .table > thead:first-child > tr:first-child > td {
    background: #009879;
    color: #fff;
    font-size: 15px;
    font-weight: bold;
    padding: 19px 9px;
}
.table {
    width: 100%;
    max-width: 92%;
    height: 40%;
}
.table tbody tr:nth-of-type(even){
    background-color: #f3f3f3;
}
.table tbody tr:last-of-type{
    border-bottom: 2px solid #009879;
}
button{
    font-size: 15px;
    width: 100%;
    height: 100%;
    border-radius: 30px;
    background: #009879;
    color: #fff;
    border: 1px solid #000;
    transition: all .5s ease-in-out;
}
button:hover{
    transform: scale(1.1,1.1);

}
button a{
    color: #fff;
    outline: none;
    text-decoration: none;

}
button a:hover{
    color: #fff;
    outline: none;
    text-decoration: none;

}
</style>