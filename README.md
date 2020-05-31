<!DOCTYPE html>
<html lang="en">
<head>
    <style type="text/css">
   .header{
    position: relative;
    height: 100px;
    width: 1200px;
    line-height: 100px;
    margin: 0 auto;
  }
    p{
      display: inline;
      font-size: 18px;
      color:#050505;
      border-bottom: rgba(0,164,255,1);
  }

  .logo{
    font-weight: bolder;
    font-size: 40px;
    color: #00A4FF;
    margin: 0px;
    float: left;
  }
  .nav{
    float: left;
    margin-top: 0px;
  }
  .nav li{
    float: left;
    list-style-type: none;
    text-align: center;
    font-size: 18px;
    width:80px;
    height: 80px;
    margin-left: 20px;
  }
  .nav li:hover{
     border-bottom: 2px solid rgba(0,164,255,1);
  }
  .a1{
    position: absolute;
    top: 0 1cvxetrpx;
    right: 0px;
    font-size:14px;

  }
  .form{ 
    position:absolute;
    font-size: 14px;
    margin-top: 22px;
    width:420px;
    right: 100px;
  }
  .search{
    float: left;
    width:361px;
    height:40px;
    margin-bottom: 0px; 
    border: 1px solid rgba(0,164,255,1);
  }
  .sumbit{
    width:50px;
    height:45px;
    border:none; 
    background:rgba(0,164,255,1)
     url(./fa-search.png) no-repeat center center;
    float:left;
  }
   .banner{
    background: url(./banner2.png) no-repeat center;
    height: 420px;
    margin: 0 auto;
   }
  .classes{
    background: url(./classbackground.png) no-repeat ;
    width:1200px;
    margin: 0 auto;
    position: relative;
    left: 5%
  }
  .project{
    font-size:14px;
    font-family:Microsoft YaHei;
    font-weight:400;
    color:white;
    line-height:53px; 
    list-style-type:none; 
  }
  .project:hover{
    color: #00A4FF
  }
  span{
    position: absolute;
    left: 14%;
  }
  .middle{
    position: relative;
    padding-top: 10px;
    width:1200px;
    height:60px;
    background:rgba(255,255,255,1);
    box-shadow:0px 2px 3px 0px rgba(118,118,118,0.2);
    margin: 0 auto;
  }
  .middle ul{
    position: absolute;
    margin-left:0px;
    padding-left: 0px;
  }
  .middle li{
    list-style-type:none;
    float: left;
    width:130px;
    height: 30px; 
    font-size:16px;
    font-family:Microsoft YaHei;
    text-align: center;
    font-weight:bold;
    border-right:1px solid rgba(191,191,191,1);
  }
 .middle p{
  padding-right: 50px;
  font-size:16px;
  font-family:Microsoft YaHei;
  float: right;
  font-weight:bold;
 }
 .blue{
  color: #00A4FF;
 }
 .middle2{
  height: 600px;
  padding-top: 20px;
  width: 1250px;
  margin: 0 auto
 }
 .middle2 .title{
  font-size:20px;
  font-family:Microsoft YaHei;
  font-weight:400;
  color:rgba(73,73,73,1);
 }
 .middle2 li{
  position: relative;
  width: 233px;
  height: 270px;
  padding-right: 5px;
  float:left;
  list-style-type:none; 
   box-shadow:0px 2px 5px 0px rgba(118,118,118,0.5);
 }
 .introduce{
  position: absolute;
  top: 180px;
  left: 25px;
  margin: 0 auto;
  width:185px;
  height:34px;
  font-size:14px;
  font-family:Microsoft YaHei;
  font-weight:400;
  color:rgba(5,5,5,1);
  line-height:20px;

 }
 .middle2 .zzy{
  margin-top: 70px;
  margin-left:25px;
  font-size: 12px;
  width:228px;
  height:20px;
 }
 .middle2 font{
  color: #FF7C2D
 }
 .bottom li{
  padding-top: 15px;
 }

 .zzy{
  font-size:20px;
  height: 20px;
  font-family:Microsoft YaHei;
  font-weight:400;
  color:rgba(72,72,72,1);
 }
  .web{
    height: 360px;
  width: 1250px;
  margin: 0 auto;
  padding-top: 20px;
 }
  .zzy2{  
    float: left;
    display: inline-block;
    color:rgba(72,72,72,1);
    font-size: 20px;
  }
  .choose{
    top: 0;
    padding-top: 20px;
    padding-left: 250px;
    margin: 0 auto;
  }
  .choose li{
    float: left;
    padding-top: 20px;
    list-style-type: none;
    width:100px;
    margin: 0 auto;
  }
  .all {
    float:right;
    font-size: 12px;
    color:rgba(165,165,165,1);
  }
  .p1{
    float: left;
  }
  .web .zzy3{
  position: relative;
  width: 233px;
  height: 270px;
  padding-right: 5px;
  float:left;
  list-style-type:none; 
   box-shadow:0px 2px 5px 0px rgba(118,118,118,0.5);
 }
 .web font{
  color: #FF7C2D
 }
 .zzy4{
  font-size: 12px;
  padding-top: 70px;
  padding-left: 25px;
 }
.middle3{
  height: 380px;
  width:1250px;
  padding-top: 20px;
  margin: 0 auto;
}
.middle3 .p5{
  float: left;
  font-size:20px;
  color:rgba(72,72,72,1);
}
.middle3 ul{
  float: left;

}
.middle3 li{
  float:left;
  list-style-type: none;
  position:relative;
}
.p6{
  position: relative;
}
.p7{
  position: absolute;
   width: 236px;
   height: 100px;
   line-height:20px;
   background-color: black;
   opacity: 0.5;
   bottom:0px;
   color:white;
   font-size: 12px;
}
 .white{
  width:1917px;
  height:417px;
  background:rgba(255,255,255,1);
 }
.box1{
  width: 1200px;
  margin:0 auto;
  padding-top: 120px;
}
.box2{
  float: left;
}
.box2 li{
  list-style-type: none;
  padding-top:25px;
  background-color: #FFFFFF;
}
.box3{
  font-size:36px;
  color: #00A3FF;
}
.box4{
  font-size: 12px;
  color:#656565;
}
.box5{
  border-color: #00A3FF;
  color:  #00A3FF;
  font-size: 16px;
  margin: 28px;
}
.box6{
  float: left;
  padding-top: 20px;
    padding-left: 270px;
    font-size:12px;
    color: black;
    list-style-type: none;
    line-height:21px;
}
.box7{
  float: left;
  padding-top: 20px;
    padding-left: 140px;
    font-size:12px;
    color: black;
    list-style-type: none;
    line-height:21px;
}
.box8{
    padding-top: 20px;
    float: right;
    font-size:12px;
    color: black;
    list-style-type: none;
    line-height:21px;
}
.big{
  font-size:16px;
  color:rgba(51,51,51,1);
  padding-bottom: 5px;
}

  </style>  
  <meta charset="UTF-8">
  <title>Doument</title>
</head>
<body>
    <div class="header clear">
     <p class="logo">学梨在线</p>
     <ul class="nav clear">
      <li>首页</</li>
      <li>课程</li>
      <li>课程规划</li>     
     </ul>
     <form class="form">
        <input type="text" placeholder="输入关键词" class="search"/>
        <input type="button" class="sumbit" src="./fa-search.png">
        </form>
        <div class="a1">个人中心</div>
   </div>
   <div class="banner">
     <ul class="classes">
      <li class="project">前端开发<span>></span></li>
      <li class="project">后端开发<span>></span></li>
      <li class="project">移动开发<span>></span></li>
      <li class="project">人工智能<span>></span></li>
      <li class="project">商业预测<span>></span></li>
      <li class="project">云计算<span>></span></li>
      <li class="project">UI设计<span>></span></li>
      <li class="project">产品><span>></span></li>      
     </ul>
   </div>
   <div class="middle">
   <ul>
    <li class="blue">精品推荐</li>
    <li>JQuer</li>
    <li>Spark</li>
    <li>ySQL</li>
    <li>JavaWeb</li>
    <li>MSQL</li>
    <li>JavaWeb</li>
    </ul>
    <p class="blue">修改兴趣</p>
   </div>
   <div class="middle2">
    <P class="title">精品推荐</P>
    <ul>
    <li><img src="./p1.png">
    <p class="introduce">Think PHP 5.0 博客系统实战项目演练</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div>
    </li>
    <li><img src="./p2.png">
    <p class="introduce">Android 网络图片加载框架详解</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    <li><img src="./p3.png">
    <p class="introduce">Angular 2 最新框架+主流技术+项目实战</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    <li><img src="./p4.png">
    <p class="introduce">Android Hybrid App开发实战 H5+原生</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    <li><img src="./p4.png">
    <p class="introduce">Android Hybrid App开发实战 H5+原生</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    </ul>
    <ul class="bottom">
    <li><img src="./p1.png">
    <p class="introduce">Think PHP 5.0 博客系统实战项目演练</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div>
    </li>
    <li><img src="./p2.png">
    <p class="introduce">Android 网络图片加载框架详解</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    <li><img src="./p3.png">
    <p class="introduce">Angular 2 最新框架+主流技术+项目实战</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    <li><img src="./p4.png">
    <p class="introduce">Android Hybrid App开发实战 H5+原生</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    <li><img src="./p4.png">
    <p class="introduce">Android Hybrid App开发实战 H5+原生</p>
    <div class="zzy"><font>高级</font> * 1125人在学习</div></li>
    </ul>
   </div>
   <br>
   <div class="web">
     <p class="zzy2">前端开发工程师</p>
      <ul class= "choose">
       <li >热门</li>
       <li >初级</li>
       <li >中级</li>
       <li >高级</li>
      </ul>
      <p class="all">查看全部</p>
      <br>
      <ul class="p1" >
    <li class="zzy3"><img src="./p5.png">
    <p class="introduce">Think PHP 5.0 博客系统实战项目演练</p>
    <div class="zzy4"><font>高级</font> * 1125人在学习</div>
    </li>
    <li class="zzy3"><img src="./p7.png">
    <p class="introduce">Android 网络图片加载框架详解</p>
    <div class="zzy4"><font>高级</font> * 1125人在学习</div></li>
    <li class="zzy3"><img src="./p6.png">
    <p class="introduce">Angular 2 最新框架+主流技术+项目实战</p>
    <div class="zzy4"><font>高级</font> * 1125人在学习</div></li>
    <li class="zzy3"><img src="./p9.png">
    <p class="introduce">Android Hybrid App开发实战 H5+原生</p>
    <div class="zzy4"><font>高级</font> * 1125人在学习</div></li>
    <li class="zzy3"><img src="./p8.png">
    <p class="introduce">Android Hybrid App开发实战 H5+原生</p>
    <div class="zzy4"><font>高级</font> * 1125人在学习</div></li>
    </ul>
   </div>
   <div class="middle3">
   <div class="p5">牛人推荐</div>
   <ul>
   <li><img src="./p10.png"></li>
   <li><img class="p6" src="./pz1.png">
    <div class="p7"> <font>   闻老师   大数据<br>高级互联网软件工程师，曾担任某公司CRM开发团队TL，多年JAVAEE，大数据领域研发…… </font></div>
   </li>
   <li ><img class="p6" src="./pz2.png">
   <div class="p7"> <font>   汪老师   大数据<br>高级软件架构师，多线开发，多年大项目管理经验，对webComponents,Nodejs…… </font></div></li>
   <li><img class="p6" src="./pz3.png">
   <div class="p7"> <font>   江老师    大数据<br>多年软件开发经验喝教学经验，精通html，css,js,aasp,net等编程语言和数据库系统…… </font></div></li>
   </ul>
   </div>

   <div class="box1">
   <ul class="box2" >
    <li class="box3">学历在线</li>
    <li class="box4">致力于普及中国最好的教育，与中国一流大学和机构合作提供在线课程。</li>
    <li class="box5">下载APP</li>
    </ul>
    <ul class="box6">
      <li class="big">关于雪梨网</li>
      <li>关于</li>
      <li>管理团队</li>
      <li>工作机会</li>
      <li>客户服务</li>
      <li>帮助</li>
    </ul>
    <ul class="box7">
      <li class="big">新手指南</li>
      <li>如何注册</li>
      <li>如何选课</li>
      <li>如何拿到毕业证</li>
      <li>学分是什么</li>
      <li>考试未通过怎么办</li>
    </ul>
    <ul class="box8">
     <li class="big">合作伙伴</li>
     <li>合作机构</li>
     <li>合作导师</li>
    </ul>
   </div>

</body>
</html>