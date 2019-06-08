<html lang="zh">
<head>
  <title>Trditional Resume</title>
  <meta charset="UTF-8">
  <link type="text/css" rel="StyleSheet" href="css/reset.css"/>
  <link type="text/css" rel="StyleSheet" href="css/main.css"/>
  <style type="text/css">
    body{
      background-image:url(images/bg.png);
    }
    .item-title{
      width:100px;
      padding:4px;
      line-height: 1.8;
    }
    .item-content{
      padding:4px;
      line-height: 1.8;
    }
    li{
      padding:7px 0px;
    }
    li::before{
      content:url(./images/icons/yes.png);
      padding-right:6px;
      vertical-align: middle;
    }
    .item-wrap{
      display:-moz-box;
      display:-webkit-box;
      display:box;
      padding:6px 0px;
      border-bottom:solid 1px #aaa;
      margin-bottom:6px;
      width: 100%;
    }
    .item-box-left{
      width: 100px;
    }
    .item-box-right{
       width: 700px;
    }
    .item-title-hl{
      font-size:18px;
      padding:4px;
      background-color: #ddd;
      border-bottom:solid 2px #ccc;
    }
    .project-title{
      font-size:18px;
      line-height: 1.8;
      padding:4px;
    }
    .project-sub-title{
      padding:4px;
      line-height: 1.8;
      width:70px;
    }
    #goTop{
      position:fixed;
      right:100px;
      bottom:100px;
      background-image:url(images/icons/top.png);
      width:32px;
      height:32px;
      -webkit-box-reflect: below 0px -webkit-gradient(linear, center top, center bottom, from(transparent),color-stop(0.2, transparent), to(white));
      opacity: 0.5;
    }
    .reflect{
      background-image:url(images/icons/top.png);
      width:32px;
      height:32px;
      -webkit-transform: scaleY(-1);
      -moz-transform: scaleY(-1);
      -ms-transform: scaleY(-1);
      transform: scaleY(-1);
      filter:alpha(opacity='80');
      opacity: 0.8;
    }
    .shadow{
      position: relative;
      top:-32px;
      left:0px;
      height:32px;
      width:32px;
      background-image: -moz-linear-gradient(center bottom, rgb(227,227,227) 30%, rgba(255,255,255,0) 100%);
      background-image: -webkit-gradient(linear, center bottom, center top, color-stop(0.3, rgb(227,227,227)), color-stop(0.7, rgba(255,255,255,0)));
      filter: progid:DXImageTransform.Microsoft.Gradient(gradientType=0,startColor=#e8e8e8, EndColorStr=#ffffff);
    }
  </style>
  <script type="text/javascript" src="js/jquery.js"></script>
</head>
<body style="margin:0px auto;width:800px;">
  <header>
    <section style="padding:6px 0px;">
      <hr/>
    </section>
  </header>
  <article style="padding:10px 0px;">
    <section>
      <table style="width:100%">
        <tr>
          <td class="item-title">称呼：</td>
          <td class="item-content">陈先生</td>
          <td class="item-title">求职意向：</td>
          <td class="item-content">python工程师</td>
        </tr>
        <tr>
          <td class="item-title">电话号码：</td>
          <td class="item-content">15030627756</td>
          <td class="item-title">邮箱：</td>
          <td class="item-content">
            <a title="给我发邮件" href="mailto:byron_sun@outlook.com">15030627756@163.com</a>
          </td>
        </tr>
        <tr>
          <td class="item-title">性别：</td>
          <td class="item-content">男</td>
          <td class="item-title">出生日期：</td>
          <td class="item-content">1997.06</td>
        </tr>
        <tr>
          <td class="item-title">博客:</td>
          <td class="item-content" colspan="3">
            <a title="看看我的博客" href="https://me.csdn.net/ssssdbucdbod" target="_blank">https://me.csdn.net/ssssdbucdbod/</a>
          </td>
        </tr>
      </table>
    </section>
    <section style="margin:4px 0px; height:2px; background-color:#888;"></section>
    <section class="item-wrap">
      <section class="item-box-left">
        <span class="item-title-hl">专业技能</span>
      </section>
      <section class="item-box-right">
        <ul>
          <li>精通python语言</li>
          <li>掌握基础Java基础面向对象编程语言，有良好的编码习惯</li>
          <li>对python爬虫熟练掌握</li>
          <li>在机器学习理论熟练掌握</li>
        </ul>
      </section>
    </section>
    <!--<section class="item-wrap">-->
      <!--<section class="item-box-left">-->
        <!--<span class="item-title-hl">教育经历</span>-->
      <!--</section>-->
      <!--<section class="item-box-right" style="margin-bottom:10px;">-->
        <!--<table>-->
          <!--<tr>-->
            <!--<td style="width:150px;">2007.09~2011.06</td>-->
            <!--<td style="width:250px;">**工业大学(211)</td>-->
            <!--<td>软件工程</td>-->
          <!--</tr>-->
        <!--</table>-->
      <!--</section>-->
    <!--</section>-->
    <!--<section class="item-wrap">-->
      <!--<section class="item-box-left">-->
        <!--<span class="item-title-hl">工作经历</span>-->
      <!--</section>-->
      <!--<section class="item-box-right">-->
        <!--<table>-->
          <!--<tr>-->
            <!--<td style="padding:8px 0px; width:150px;">2011.05~今</td>-->
            <!--<td style="padding:8px 0px; width:250px;">北京****科技有限公司</td>-->
            <!--<td>Software Engineer</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td>2010.07~2011.05</td>-->
            <!--<td>天津**软件有限公司</td>-->
            <!--<td>开发实习生</td>-->
          <!--</tr>-->
        <!--</table>-->
      <!--</section>-->
    <!--</section>-->
    <section class="item-wrap">
      <section class="item-box-left">
        <span class="item-title-hl">项目经验</span>
      </section>
      <section class="item-box-right">
        <section>
           <table style="margin-bottom:10px; border-bottom:dashed 1px #ccc;">
          <tr>
            <td colspan="2" class="project-title">2018.5 ~ 2018.6</td>
          </tr>
          <tr>
            <td class="project-sub-title" valign="top">项目描述:</td>
            <td class="item-content">百度旅游、大众点评、驴妈妈、猫途鹰、携程的评论爬虫。</td>
          </tr>
          <tr>
            <td class="project-sub-title" valign="top">使用技术:</td>
            <td class="item-content">python、BeautifulSoup、xpath、正则、代理池、模拟浏览器</td>
          </tr>
          <tr>
            <td class="project-sub-title" valign="top">项目代码:</td>
            <td class="item-content">
              https://github.com/MaxwellJack/pinglun_spyder
            </td>
          </tr>
        </table>
        <table style="margin-bottom:10px; border-bottom:dashed 1px #ccc;">
          <tr>
            <td colspan="2" class="project-title">2019.04 ~ 2019.05</td>
          </tr>
          <tr>
            <td class="project-sub-title" valign="top">项目描述:</td>
            <td class="item-content">
              使用HOG和PCA方法在不同的数据集上进行对比实验，使用BP网络、支持向量机和集成学习的方法对HOG和PCA处理过的数据集进行分类，对比实验结果。
            </td>
          </tr>
          <tr>
            <td class="project-sub-title" valign="top">使用技术:</td>
            <td class="item-content">python</td>
          </tr>
          <tr>
            <td class="project-sub-title" valign="top">项目代码:</td>
            <td class="item-content">
            https://github.com/MaxwellJack/graduation-project-
            </td>
          </tr>
        </table>
        <!--<table style="margin-bottom:10px; border-bottom:dashed 1px #ccc;">-->
          <!--<tr>-->
            <!--<td colspan="2" class="project-title">2012.12 ~ 今 SchoolStream My Desktop、Login Page</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目描述:</td>-->
            <!--<td class="item-content">-->
              <!--My Desktop和Login Page是SchoolStream产品首页及各个应用入口，通过响应式的展现方式方便用户理解与使用。-->
            <!--</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">使用技术:</td>-->
            <!--<td class="item-content">JavaScript、CSS、Ajax、jQuery、ASP.NET、Web Service</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目收获:</td>-->
            <!--<td class="item-content">-->
              <!--通过对首页HTML结构的重新调整及UI的重新设计，使产品首页在易用性得到极大提高，对JavaScript和CSS代码重写，提高的程序运行效率及浏览器兼容性。对JavaScript最佳实践及面向对象可复用设计有了深入了解，熟悉了CSS定位及布局知识，熟练使用jQuery，对浏览器兼容性问题有了深刻认识。-->
            <!--</td>-->
          <!--</tr>-->
        <!--</table>-->
        <!--<table style="margin-bottom:10px; border-bottom:dashed 1px #ccc;">-->
          <!--<tr>-->
            <!--<td colspan="2" class="project-title">2012.09 ~ 今 Common Web Control</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目描述:</td>-->
            <!--<td class="item-content">SchoolStream产品中通用Web控件开发，包括Dialog、Tree、Tab、List View、Single Button，页面可以直接调用组件进行常见功能开发。</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">使用技术:</td>-->
            <!--<td class="item-content">ASP.NET、WebControl、JavaScript、CSS、设计模式</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目收获:</td>-->
            <!--<td class="item-content">-->
              <!--通过对现有自定义控件修改及开发新控件，对软件设计兼容性、拓展性有了深刻认识，理解、熟练使用策略模式、工厂模式、观察者模式、单例模式熟悉JavaScript面向对象开发及CSS定位布局，强化了浏览器兼容性意识。-->
            <!--</td>-->
          <!--</tr>-->
        <!--</table>-->
        <!--<table style="margin-bottom:10px; border-bottom:dashed 1px #ccc;">-->
          <!--<tr>-->
            <!--<td colspan="2" class="project-title">2012.05 ~ 2012.09 Authority System Upgrade</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目描述:</td>-->
            <!--<td class="item-content">通过对现有用户表及权限控制表拆分、重组，引入安全组及object role等概念，使权限系统支持多种账户类型存储与处理。</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">使用技术:</td>-->
            <!--<td class="item-content">ASP.NET、SQLServer、MVP架构、Unity IoC、观察者、策略、工厂模式</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目收获:</td>-->
            <!--<td class="item-content">-->
              <!--了解基于SQL Server的数据库设计基本知识，设计符合3NF的数据库结构，通过正确使用索引提高搜索效率，熟练应用OOP中的开放封闭原则、单一职责原则、里氏代换原则及设计模式进行程序设计，了解基于Unity的IoC及MVP模式。-->
            <!--</td>-->
          <!--</tr>-->
        <!--</table>-->
        <!--<table style="margin-bottom:10px;">-->
          <!--<tr>-->
            <!--<td colspan="2" class="project-title">2011.07 ~ 2012.05 Teacher Web Page</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目描述:</td>-->
            <!--<td class="item-content">一个与SIS集成的教师个人站点，为教师、学生、家长对学生在校学习及评价提供统一平台。</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">使用技术:</td>-->
            <!--<td class="item-content">JavaScript、CSS、Ajax、jQuery、ASP.NET、Web Service</td>-->
          <!--</tr>-->
          <!--<tr>-->
            <!--<td class="project-sub-title" valign="top">项目收获:</td>-->
            <!--<td class="item-content">-->
              <!--通过了解、挖掘用户需求、设计系统、实现系统的流程，培养了做产品的责任心及需求获取、分析能力，程序设计能力。在开发过程中了解HTTP协议，熟悉HTML、CSS、JavaScript及web service、Ajax、jQuery，熟练使用Visual Studio 进行基于ASP.NET的Web Application开发。-->
            <!--</td>-->
          <!--</tr>-->
        <!--</table>-->
        </section>
      </section>
    </section>
    <section class="item-wrap">
      <section class="item-box-left">
        <span class="item-title-hl">自我评价</span>
      </section>
      <section class="item-box-right" style="margin-bottom:10px;">
        <ul>
          <li>性格乐观开朗，感染力强，能够带动团队氛围</li>
          <li>对技术感兴趣，广泛关注行业知识、动向，喜欢钻研技术原理</li>
          <li>表达能力强，热衷于技术分享</li>
        </ul>
      </section>
    </section>
     <section class="item-wrap" style="border:0;">
      <section class="item-box-left">
        <span class="item-title-hl">兴趣爱好</span>
      </section>
      <section class="item-box-right">
        看历史相关书籍、写技术博客，分享知识、羽毛球
      </section>
    </section>
    <aside id="wrap" style="position:fixed; bottom:100px; right:100px;display:none; opacity:0.5;">
      <section style="background-image:url(images/icons/top.png); width:32px;height:32px;"></section>
      <section class="reflect"></section>
      <section class="shadow"></section>
    </aside>
  </article>

  <script type="text/javascript">
    $(function(){
      $('#wrap').on('click', function(event) {
        var obj=document.body.scrollTop>0? document.body:document.documentElement;
        $(obj).animate({"scrollTop":0}, 1000);
        $(this).animate({"opacity":0.5}, 1000);
      }).on('mouseover', function(event) {
        $(this).css('opacity',1);
      }).on('mouseout',function(event) {
        $(this).css('opacity',0.5);
      });
    });
    $(document).scroll(function(event) {
      var goTop=$('#wrap');
      var scrollTop=document.body.scrollTop || document.documentElement.scrollTop || 0;
      if(scrollTop>0){
        if(goTop.css('display')=='none'){
          $('#wrap').fadeIn(500);
        }
      }else{
        if(goTop.css('display')!='none'){
          $('#wrap').fadeOut(500);
        }
      }
    });
  </script>
</body>
</html>

