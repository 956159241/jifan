<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;走进吉梵&nbsp;>&nbsp;核心部门</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">核心部门</h1>
                <h2 class="ui header">CORE DEPARTMENT</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>吉梵金融下设吉梵资产与吉梵金服两大平台，注册资本为1亿元。以帮助客户财富增长为宗旨，以期运用各种金融工具为客户管理财富，帮助企业借力资本市场，搭建金融市场的商务合作桥梁，致力于开创一个新型的现代化金融服务机构。</p>
              </div>
            </div>
            <img src="/static/img/Team-img.png">
            <div class="Tri-1"></div>
          </div>
        </div>
        <!--注资集团背景-->
        <div class="ui grid jf-background">
          <div class="sixteen wide column">
            <br/><br/><br/><br/><br/>
            <h1>更新中……</h1>
            <!--以下注释块是内容排版保留待添加内容-->
            <!--&lt;!&ndash;吉梵金服&ndash;&gt;-->
            <!--<div class="jf-background-container">-->
              <!--<div class="header">-->
                <!--<h1 class="ui header h1">投资发展部</h1>-->
                <!--<h3 class="ui header h4">INVESTMENT AND DEVELOPMENT DEPARTMENT</h3>-->
                <!--<hr/>-->
              <!--</div>-->
              <!--<img src="/static/img/JF-Team-img-1.png">-->
              <!--<div class="ui segment section">-->
                <!--<p>吉梵资产投资发展部主要从事以新三板为主的股权投资业务，涵盖定向增发、市值规划、并购重组及相关投资业务。以股权投资为主要投资方式，立足新三板市场7000多家企业；以新模式、新视角挖掘优质项目，树立风险管理理念，打造股权投资新蓝海。</p>-->
              <!--</div>-->
            <!--</div>-->
            <!--<div class="line">-->
              <!--<div class="line-location-Tri"></div>-->
            <!--</div>-->
            <!--&lt;!&ndash;吉梵理念&ndash;&gt;-->
            <!--<div class="jf-idea-container">-->
              <!--<div class="header">-->
                <!--<h1 class="ui header h1">机构发展中心</h1>-->
                <!--<h3 class="ui header h4">INSTITUTIONAL DEVELOPMENT CENTER</h3>-->
                <!--<hr/>-->
              <!--</div>-->
              <!--<img src="/static/img/JF-Team-img-2.png">-->
              <!--<div class="ui segment section">-->
                <!--<p>机构发展中心负责运营、管理吉梵金融信息服务有限公司以及外地分支机构。现主要项目有组织并承办财经沙龙、金融培训及企业项目路演活动；线上线下同时搭建金融圈内人群相互交流学习与商务洽谈合作平台；在线输出财经直播、研究资讯、品牌推广等服务。</p>-->
              <!--</div>-->
            <!--</div>-->
            <!--<div class="line"></div>-->
            <!--&lt;!&ndash;财富管理中心&ndash;&gt;-->
            <!--<div class="jf-background-container">-->
              <!--<div class="header">-->
                <!--<h1 class="ui header h1">财富管理中心</h1>-->
                <!--<h3 class="ui header h4">WEALTH MANAGEMENT CENTER</h3>-->
                <!--<hr/>-->
              <!--</div>-->
              <!--<img src="/static/img/JF-Team-img-3.png">-->
              <!--<div class="ui segment section">-->
                <!--<p>作为金融产品设计及筛选专家，和客户建立长期的财富管理服务关系，利用全面的金融产品和专业技能，多维度的资产配置，帮助客户合理地获取、保护、管理和运用其金融资源，在适度的风险范围内获得财富的增长、达到其个性化的财富管理目标以至人生目标，获得财务自由的持续服务。成为全方位的财富管理专业服务机构及高净值客户家族财富管理解决方案的提供者。</p>-->
              <!--</div>-->
            <!--</div>-->




          </div>
        </div>

      </div>
    </div>
  </div>
</template>
<script>
  let $ = require('jquery')
  //  let Slider = require('slider')
  export default{
    replace: false,
    ready: function () {
    },
    jquery: function () {
      $('.ui.dropdown')
        .dropdown()
    },
    data () {
      return {
      }
    }
  }
</script>
<style scoped>
  .ui.container{width: 1380px;}
  .two.wide.column{margin: 0px;padding:0px;}
  .twelve.wide.column.main-content{width: 1380px!important;overflow: hidden;padding-left: 0px;text-align: center;padding-right:0px;background-color: rgb(245,245,245);
    padding-top:0px;margin-top: 14px;}
  /*top位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:30px;line-height:30px;vertical-align:middle;padding-left:120px;}
  .location-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(230,230,230);position:absolute;right: 160px;top:30px;z-index:1;}
  /*进入吉梵*/
  .ui.grid.into-jf{padding:0px;text-align:right;height:530px;margin-bottom: 0px;margin-top: 0px;}
  .ui.grid.into-jf>div{background-image: url("../../static/img/home-background-img-1.png");padding-top: 0px;padding-right:0px;}
  .into-jf-container{background-color: rgb(245,245,245);height:380px;width:921px;float: right;text-align: center;padding-top:58px;padding-right:160px;padding-left:100px;}
  .into-jf-container>.header{text-align: right;}
  .into-jf-container>.header>h1,.into-jf-container>.header>h2{margin:0px!important;padding:3px!important;}
  .into-jf-container>.header>h1{font-size: 30px;color:#323232;}
  .into-jf-container>.header>h2{font-size: 18px;color:#323232;}
  .into-jf-container>.header>hr{float: right;width:30px;border: 2px solid #d10a1b;}
  .into-jf-container>.ui.segment.section{text-align: left;margin-top: 60px;border:0px;box-shadow:0px 0px 0px transparent;color: #646464;font-size: 14px;background-color: rgb(245,245,245);}
  .into-jf-container>.ui.segment.section>p{line-height: 20px;}
  .into-jf>div>img{margin-top: 66px;margin-right: -30px;}
  .Tri-1{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(229,27,48);position:absolute;left: 140px;bottom:75px;z-index:1; }
  /*吉梵金服*/
  .ui.grid.jf-background{z-index:999;padding:0px 100px;margin-top: -108px;text-align: left;}
  .ui.grid.jf-background>.sixteen.wide.column{text-align: center!important;}
  .jf-background-container{background-color: rgb(255,255,255);height:340px;padding-top:20px;}
  /*.jf-background-container{background-color: rgb(255,255,255);height:340px;}*/
  .jf-background-container>.header{text-align: left;}
  .jf-background-container>.header>.ui.header.h1{float:left;padding-right:10px;margin-left: 20px;}
  .jf-background-container>.header>.ui.header.h4{}
  .jf-background-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  .jf-background-container>img{float: left;padding-right:20px;padding-top: 30px;}
  .jf-background-container>.ui.segment.section{background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 50px;}
  .jf-background-container>.ui.segment.section>p{line-height: 30px;padding-right: 20px;}
  /*行间距加小三角*/
  .line{width:100%;background-color:rgb(245,245,245);height:35px;}
  .line>.location-Tri{float:right;width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(245,245,245);position:relative;right: 100px;z-index:1;}
  /*吉梵理念*/
  .jf-idea-container{background-color: rgb(230,230,230);margin-top: 0px;padding-top: 40px;height:510px;}
  .jf-idea-container>.header{text-align:right;}
  .jf-idea-container>.header>.ui.header.h1{float:right;padding-right:10px;}
  .jf-idea-container>.header>.ui.header.h4{margin-top: 0px;}
  .jf-idea-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: right;margin-top: -10px;}
  .jf-idea-container>img{float: right;padding-right:20px;padding-top: 30px;}
  .jf-idea-container>.ui.segment.section{width:600px;margin-top: 40px;padding-left: 155px;background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 50px;}
  .jf-idea-container>.ui.segment.section>p{line-height: 30px;}
  /*吉梵合作伙伴*/
  .jf-partner-container{}
  .jf-partner-container>.header{text-align: left;}
  .jf-partner-container>.header>.ui.header.h1{float:left;padding-right:10px;}
  .jf-partner-container>.header>.ui.header.h4{}
  .jf-partner-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  .partner-pic{margin-top:100px;}
  /*7.26调整*/
  /*最上方标题部分与文字*/
  .into-jf-container>.ui.segment.section{text-align: left;margin-top: 60px;border:0px;box-shadow:0px 0px 0px transparent;color: #646464;font-size: 14px;background-color: rgb(245,245,245);
    padding-right: 0px;padding-bottom: 0px;text-align: justify;}
  .into-jf-container>.ui.segment.section>p{line-height: 30px!important;text-align: justify;}
  /*第一排标题与文章内容*/
  .jf-background-container>.header>.ui.header.h1{float:left;padding-right:10px;margin-left: 20px;font-size: 24px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-background-container>.header>.ui.header.h4{font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-background-container>.ui.segment.section{text-align: justify;}
  .jf-background-container>.ui.segment.section>p{line-height: 30px;color: #646464;text-align: justify;}
  /*第二行标题与内容*/
  .jf-idea-container>.header>.ui.header.h1{float:right;padding-right:20px;padding-left: 10px;font-size: 24px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.header>.ui.header.h4{margin-top: 0px;font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.ui.segment.section>p{line-height: 30px;color:#646464;text-align: justify;}
  /*位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:40px;line-height:40px;vertical-align:middle;padding-left:120px;}
  .ui.container>.twelve.wide.column.main-content{margin-top: 0px;}
  .location-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(230,230,230);position:relative;left: 1005px;top:0px;z-index:1;}
  .line>.line-location-Tri{float:right;width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(245,245,245);position:relative;right: 100px;z-index:1;top:33px;}






  @media screen and (max-width:1275px ){
    .into-jf>div>img{display: none;}
  }
</style>
