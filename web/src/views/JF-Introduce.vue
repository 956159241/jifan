<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location" id="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;走进吉梵&nbsp;>&nbsp;吉梵简介</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">吉梵简介</h1>
                <h2 class="ui header">  INTRODUCE OF JIFAN</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>吉梵金融于2014年1月成立于国际金融中心---上海，位于集时代感与历史文化沉淀于一体的上海新天地核心商圈，由资深金融专业背景的管理团队运营，拥有金融业内一流的战略顾问团队，主要开展投资银行，财富管理，金融服务三大领域业务。</p>
              </div>
            </div>
            <img src="/static/img/into-jf-float-img.png">
            <div class="Tri-1"></div>
          </div>
        </div>
        <!--注资集团背景-->
        <div class="ui grid jf-background">
          <div class="sixteen wide column">
            <!--吉梵金服-->
            <div class="jf-background-container">
              <div class="header">
                <!--<h1 class="ui header h1">吉梵金服</h1>-->
                <!--<h4 class="ui header h4">KAT VAN SERVICE</h4>-->
                <h1 class="ui header h1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h1>
                <h4 class="ui header h4">&nbsp;&nbsp;&nbsp;&nbsp;</h4>
                <!--<hr/>-->
              </div>
              <img src="/static/img/JF-introduce-img-1.png">
              <div class="ui segment section">
                <p>在投资银行领域，主要开展投资、并购、财务顾问等业务，帮助企业借力资本市场。<br/>
                  在财富管理领域，涵盖了财务规划、投资组合管理和一系列综合金融资产配置的投资咨询服务，针对财富积累、财富增值、财富保全以及财富传承等方面提出的专业建议，运用各种金融工具为高净值人群、家族及企业提供资产配置规划、法律服务、税收规划、金融资产投资管理、海外资产配置及家族账户委托管理等全方位财富管理服务。</p>
              </div>
            </div>
            <div class="line">
              <div class="line-location-Tri"></div>
            </div>
            <!--吉梵理念-->
            <div class="jf-idea-container">
              <div class="header">
                <!--<h1 class="ui header h1">吉梵理念</h1>-->
                <!--<h4 class="ui header h4">VATICAN PHILOSOPHY KAT</h4>-->
                <h1 class="ui header h1">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h1>
                <h4 class="ui header h4">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h4>
                <!--<hr/>-->
              </div>
              <img src="/static/img/JF-introduce-img-2.png">
              <div class="ui segment section">
                <p>在金融服务领域，投资创建了集办公与金融会所功能为一体的吉梵金融空间作为实体平台，组织并承办财经沙龙、金融培训及项目路演等各类活动，同时链接互联网资源，搭建金融市场的交流学习与商务合作平台，通过线上为机构输出财经直播、研究资讯、品牌推广等服务。<br/>
                  吉梵金融致力于建立一个对社会有积极价值的现代化金融机构，搭建一个能让金融专业人士，投资者，企业家共同成长，共享资源，共赢利益的开放平台。本着公平、开放、自由、共赢的核心价值观，严谨、专业、高效的经营理念及全球化视野来经营公司，为投资者与客户创造价值，为社会进步贡献力量。</p>
              </div>
            </div>
            <div class="line"></div>
            <!--合作伙伴-->
            <div class="jf-partner-container">
              <div class="header">
                <h1 class="ui header h1">合作伙伴</h1>
                <h4 class="ui header h4">COOPERATIVE PARTNER</h4>
                <hr/>
              </div>
              <!--图片展示-->
              <div class="partner-pic">
                <div class="ui grid row-1">
                  <div class="three wide column"><img src="/static/img/partner-1.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-2.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-3.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-4.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-5.png"></div>
                </div>
                <div class="ui grid row-2">
                  <div class="three wide column"><img src="/static/img/partner-6.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-7.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-8.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-9.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-10.png"></div>
                </div>
                <div class="ui grid row-3">
                  <div class="three wide column"><img src="/static/img/partner-11.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-15.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-17.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-14.png"></div>
                  <div class="three wide column"><img src="/static/img/partner-12.png"></div>
                </div>
                <br/><br/><br/><br/>
              </div>


            </div>



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
  .home-message{margin-bottom: 0px!important;padding-bottom:0px!important;}
  /*.home-message>.ui.grid{margin-bottom: 0px!important;padding-bottom:0px!important;}*/
  .twelve.wide.column.main-content{width: 1380px!important;overflow: hidden;padding-left: 0px;text-align: center;padding-right:0px;background-color: rgb(245,245,245);
    padding-top:0px;margin-top: 14px;margin-bottom: 0px;}
  /*top位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:40px;line-height:40px;vertical-align:middle;padding-left:120px;}
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
  .into-jf-container>.ui.segment.section{text-align: left;margin-top: 60px;border:0px;box-shadow:0px 0px 0px transparent;color: #646464;font-size: 14px;background-color: rgb(245,245,245);
  padding-right: 0px;}
  .into-jf-container>.ui.segment.section>p{line-height: 30px!important;text-align: justify;}
  .into-jf>div>img{margin-top: 66px;margin-right: -30px;}
  .Tri-1{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(229,27,48);position:absolute;left: 140px;bottom:75px;z-index:1; }
  /*吉梵金服*/
  .ui.grid.jf-background{z-index:999;padding:0px 100px;margin-top: -108px;text-align: left;}
  .jf-background-container{background-color: rgb(255,255,255);height:340px;padding-top:20px;}
  /*.jf-background-container{background-color: rgb(255,255,255);height:340px;}*/
  .jf-background-container>.header{text-align: left;}
  .jf-background-container>.header>.ui.header.h1{float:left;padding-right:10px;margin-left: 20px;font-size: 20px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-background-container>.header>.ui.header.h4{font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-background-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  .jf-background-container>img{float: left;padding-right:20px;padding-top: 30px;}
  .jf-background-container>.ui.segment.section{background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 30px;}
  .jf-background-container>.ui.segment.section>p{line-height: 30px;color: #646464;padding-right:25px;}
  /*行间距加小三角*/
  .line{width:100%;background-color:rgb(245,245,245);height:35px;}
  .line>.line-location-Tri{float:right;width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(245,245,245);position:relative;right: 100px;z-index:1;top:33px;}
  /*吉梵理念*/
  .jf-idea-container{background-color: rgb(230,230,230);margin-top: 0px;padding-top: 40px;height:510px;}
  .jf-idea-container>.header{text-align:right;}
  .jf-idea-container>.header>.ui.header.h1{float:right;padding-right:10px;padding-left: 10px;}
  .jf-idea-container>.header>.ui.header.h4{margin-top: 0px;font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: right;margin-top: -10px;}
  .jf-idea-container>img{float: right;padding-right:20px;padding-top: 30px;}
  .jf-idea-container>.ui.segment.section{width:654px;margin-top: 40px;padding-left: 150px;background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 6px;}
  .jf-idea-container>.ui.segment.section>p{line-height: 30px;color:#646464;}
  /*吉梵合作伙伴*/
  .jf-partner-container{background-color: white;padding-top: 20px;padding-left: 20px;}
  .jf-partner-container>.header{text-align: left;}
  .jf-partner-container>.header>.ui.header.h1{float:left;padding-right:10px;font-size: 24px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-partner-container>.header>.ui.header.h4{font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-partner-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  .partner-pic{margin-top:100px;padding: 0px 30px;}
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
  /*7.27调整*/
  /*位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:40px;line-height:40px;vertical-align:middle;padding-left:120px;}
  .ui.container>.twelve.wide.column.main-content{margin-top: 0px;}
  .location-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(230,230,230);position:relative;left: 1005px;top:0px;z-index:1;}
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
