# -
باز طراحی صفحه ورود به  کلاس های آنلاین دانشگاه آزاد
<DOCTYPE hrml>
<html lang="fa-IR">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta name="author" content="Mehrshad Moradshan">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
        <title>
            طراحی سایت دانشگاه آزاد برای کلاس های مجازی
        </title>
        <style>
            .wrapper{
                width: 750px;
                height: 1010px;
                border: 1px solid gray; 
                border-radius: 10px;
                direction: rtl;
                margin:0 auto 0;
                box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2);
                background: white;
            }
            .header{
                text-align:center;
                font-family: 'Tahoma', Geneva, Segoe UI , sans-serif;
                margin: 10px auto;
                padding: 0px 25px;
                color: red;
            }
            span{
                font-family: tahoma;
                text-align: center;
                margin: 10px auto;
                padding: 0px 25px;
                color: #000000;
            }
            body{
                margin: 0px;
                direction: rtl;
                background: #f4f4f5 url(../image/bg.png);
            }
            .box{
                width: 617px;
                height: 78px;
                left: 69px;
                top: 119px;
                border-bottom: 1px solid #0F662D;
                border-radius: 5px;
                clear: both;
                padding: 10px 0px;
                margin: 20px 60px;
                direction: rtl;
                background: #99E99C;
            }
            .logo{
                /* لوگو دانشگاه آزاد 1 */

                height: 65px;
                float: right;
                margin: 0px 10px;
            }
            .b1{
                border:none;
                background: #50AECB;
                color:#fff;
                padding: 8px;
                position: absolute;
                width: 283px;
                height: 39px;
                left: 825px;
                top: 210px;
                text-align: center;
                display: inline-block;
                cursor: pointer;
                border-radius:5px;
                }
              .b1:hover{
                    background-color:gray;
                    }
              .b2{
                border:none;
                background: gray;
                color:white;
                padding: 8px;
                position: absolute;
                width: 283px;
                height: 40px;
                left: 490px;
                top: 210px;
                text-align: center;
                display: inline-block;
                cursor: pointer;
                border-radius:5px;
                }
             .b2:hover{
                background-color:#50AECB;
                }
            .bottom1{
                position: absolute;
                width: 283px;
                height: 40px;
                left: 490px;
                top: 210px;
                text-align: center;
                padding: 8px;
                background: #C4C4C4;
                border-radius: 5px;
            }
            .gude{
                font-family: tahoma;
                font-size: 12px;
                position: absolute;
                width: 339px;
                height: 35px;
                left: 770px;
                top: 266px;
                display: flex;
                align-items: flex-end;
                text-align: right;
                color: #000000;
            }
            .map{
                position: absolute;
                width: 560px;
                height: 574.41px;
                left: 518px;
                top: 326px;
                border-radius: 5px;
                box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0.2);
            }
            .line{
                position: absolute;
                width: 622px;
                height: 0px;
                left: 485px;
                top: 930px;
                border: 1px solid rgba(85, 84, 84, 0.48);
            }
            .footer1{
                font-family: tahoma;
                font-size: 12px;
                position: absolute;
                width: 70px;
                height: 24px;
                left: 830px;
                top: 943px;
            }
            .line2{
                position: absolute;
                width: 16px;
                height: 0px;
                left: 800px;
                top: 951px;

                border: 1px solid #000000;
                transform: rotate(90deg);
            }
            .footer2{
                /* اطلاعات تماس واحدها */


                position: absolute;
                width: 89px;
                height: 16px;
                left: 700px;
                top: 943px;
            }
            .footer3{
                position: absolute;
                width: 172px;
                height: 18px;
                left: 700px;
                top: 975px;
            }

        </style>
    </head>
    <body>
    <div class="wrapper">
        <div class="header">
            اساتید و دانشجویان محترم:
       <br>
            
         <span>   با توجه به گسترش استفاده از خدمات مبتنی بر اینترنت و در نتیجه افزایش استفاده از پهنای باند کشور در نقاط
            مختلف و شروع همزمان آموزش مجازی واحد ها،مشکل کندی اینترنت در کشور واختلالاتی بر روی سامانه آموزش
            مجازی وجود دارد.در صورت بروز هر گونه مشکل و اختلالات،از صبر و شکیبایی شما سپاسگزاریم.
        </span>  
     </div>
     <div class="box">
         <image src="لوگو دانشگاه آزاد.png" class="logo">
         درگاه ورود به
         <br>
         سامانه های آموزش مجازی
         <br>
         دانشگاه آزاد اسلامی - واحد الکترونیکی
     </div>
     <div>
            <div>
            <button class="b1">دانشگاه</button>
            </div>
            <div>
           <button class="b2">مدارس</button> 
            </div>
            <div class="gude">
               <p>
                    برای ورود به سامانه آموزشی دانشگاه خود،لطفا استان مورد نظر را انتخاب نمایید:
               </p>
            </div>
    </div>
    <div>
        <image src="5.png" class="map">
    </div>
    <div class="line">
    </div>
    <div class="footer1">
        مرکز دانلود
        <i class="glyphicon glyphicon-download" style="color:#1CD350;"></i>
    </div>
    <div class="line2">
    </div>
    <div class="footer2">
       اطلاعات تماس
       <i class="glyphicon glyphicon-phone" style="color:#26CFDA;"></i>
    </div>
    <div  class="footer3">
      اداره کل توسعه و نرم افزار
      <i class="glyphicon glyphicon-book" style="color:rgb(240, 12, 12);"></i>
    </div>
    </div>



    </body>
</html>
