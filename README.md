<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
   <meta http-equiv="X-UA-Compatible" content="ie=edge">
   <meta name="Keywords" content="关键字,关键词">
   <meta name="Description" content="描述和简介">
   <title>Title</title>
   <style type="text/css">
       *{margin:0;padding:0;}
       body,ul,li,ol,dl,dd,p,h1,h2,h3,h4,h5,h6{ margin:0;}
       a{text-decoration:none;color: inherit;}
       img{display: block;border:none;}
       ol,ul{list-style:none;}
       .clearfix:after {content: "";display: block;clear: both;}
       .fl{ float: left;}
       .fr{ float: right;}

       html{
           height: 100%;
           background: -webkit-radial-gradient(center,#ffffff,rgb(252, 252, 252));
       }

       .heart{ position: relative; width: 300px; height: 300px; margin: 200px auto;transform: rotate(45deg);
           animation: move 2s infinite alternate ;}
       .heart div{ position: absolute; width: 200px; height: 200px; background: rgb(239, 151, 217);}
       .heart .middle{ right: 0; bottom: 0; width: 200px; height: 200px;}
       .heart .left{ left: 0; bottom: 0; border-radius: 50%;}
       .heart .right{ top: 0; right: 0;border-radius: 50%;}

       .heart p{ width: 200px; height: 30px; font: bold 25px/30px "";text-align:center; color: #fff;}
       .heart p{ position: absolute; right: 0; bottom: 85px; transform: rotate(-45deg);}
       .heart p{
            color: rgb(231, 216, 216);
        }
       @-webkit-keyframes move{
           10%{ transform: rotate(45deg) scale(1.1); text-shadow: 0 0 5px #fff; }
           20%{ transform: rotate(45deg) scale(1.2); text-shadow: 0 0 5px #fff; }
           30%{ transform: rotate(45deg) scale(1.3); text-shadow: 0 0 5px #fff; }
           40%{ transform: rotate(45deg) scale(1.2); text-shadow: 0 0 5px #fff; }
           50%{ transform: rotate(45deg) scale(1.3); text-shadow: 0 0 5px #fff; }
           60%{ transform: rotate(45deg) scale(1.2); text-shadow: 0 0 5px #fff; }
           70%{ transform: rotate(45deg) scale(1.3); text-shadow: 0 0 5px #fff; }
           80%{ transform: rotate(45deg) scale(1.2); text-shadow: 0 0 10px #fff;}
           90%{ transform: rotate(45deg) scale(1.1); text-shadow: 0 0 5px #fff; }
       }
 </style>
</head>
<body>
   <div class="heart">
       <div class="left"></div>
       <div class="middle"></div>
       <div class="right"></div>
       <p>椰椰宝</p>
   </div>
</body>
</html>
