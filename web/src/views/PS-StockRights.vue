
<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location" id="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;产品与服务&nbsp;>&nbsp;股权投资</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">投资银行</h1>
                <h2 class="ui header">INVESTMENT BANK</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>在投资银行领域，主要开展投资、并购、财务顾问等业务，帮助企业借力资本市场。现阶段主要从事以新三板为主的股权投资业务，涵盖定向增发、市值规划、并购重组及相关投资业务。以股权投资为主要投资方式，立足新三板市场7000多家企业；以新模式、新视角挖掘优质项目，树立风险管理理念，打造股权投资新蓝海。
                </p>
              </div>
            </div>
            <img src="/static/img/JF-Manage-img.png">
            <div class="Tri-1"></div>
          </div>
        </div>
        <!--注资集团背景-->
        <div class="ui grid jf-background">
          <div class="sixteen wide column">
            <!--吉梵金服-->
            <div class="jf-background-container">
              <div class="header">
                <h1 class="ui header h1">股权投资</h1>
                <h4 class="ui header h4">EQUITY INVESTMENT</h4>
                <hr/>
              </div>
              <img src="/static/img/PS-StockRights-img.png">
              <div class="ui segment section">
                <p>股权业务：<br/>
                  吉梵资产拥有专业化的股权投资团队。通过海内外各项精准科学的核算方式、优质的经营资源、挂牌上市并购等金融指导、先进的经营管理理念，在股权投资领域开展募投管退等多项为企业溢价增值之业务，与被投企业的业务共同蓬勃成长，享受实体及资本交互发展之盛宴。</p>
              </div>
            </div>
            <div class="line">
              <div class="location-Tri"></div>
            </div>
            <!--吉梵理念-->
            <div class="jf-idea-container">
              <div class="header">
                <h1 class="ui header h1">新三板投资</h1>
                <h4 class="ui header h4">THREE NEW BOARD INVESTMENT</h4>
                <hr/>
              </div>
              <img src="/static/img/PS-StockRights-img-1.png">
              <div class="ui segment section">
                <p>新三板业务：<br/>
                  立足于新三板7000多家企业，筛选具有高成长性、符合国家战略转型方向的中小企业，挖掘新能源、新材料、新技术、节能环保、高端制造、大健康、消费升级、TMT等领域的投资机会。为企业提供资金支持、进行资源整合；实现与企业优势互补、共同发展、共同创造价值，最终实现共赢。</p>
              </div>
            </div>
            <div class="line"></div>
            <!--合作伙伴-->



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
  .two.wide.column{margin: 0px;padding:0px;height:0px;}
  .home-message{margin-bottom: 0px!important;padding-bottom:0px!important;}
  /*.home-message>.ui.grid{margin-bottom: 0px!important;padding-bottom:0px!important;}*/
  .twelve.wide.column.main-content{width: 1380px!important;overflow: hidden;padding-left: 0px;text-align: center;padding-right:0px;background-color: rgb(245,245,245);
    padding-top:0px;margin-top: 14px;margin-bottom: 0px;}
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
  .into-jf-container>.ui.segment.section>p{line-height: 20px!important;letter-spacing: 0.2em;}
  .into-jf>div>img{margin-top: 66px;margin-right: -30px;}
  .Tri-1{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(229,27,48);position:absolute;left: 140px;bottom:75px;z-index:1; }
  /*吉梵金服*/
  .ui.grid.jf-background{z-index:999;padding:0px 100px;margin-top: -108px;text-align: left;}
  .jf-background-container{background-color: rgb(255,255,255);height:340px;padding-top:20px;}
  /*.jf-background-container{background-color: rgb(255,255,255);height:340px;}*/
  .jf-background-container>.header{text-align: left;}
  .jf-background-container>.header>.ui.header.h1{float:left;padding-right:10px;margin-left: 20px;}
  .jf-background-container>.header>.ui.header.h4{}
  .jf-background-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  .jf-background-container>img{float: left;padding-right:20px;padding-top: 30px;}
  .jf-background-container>.ui.segment.section{background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 50px;}
  .jf-background-container>.ui.segment.section>p{line-height: 30px;}
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
  .jf-idea-container>.ui.segment.section{width:600px;margin-top: 40px;padding-left: 150px;background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 50px;}
  .jf-idea-container>.ui.segment.section>p{line-height: 25px;}
  /*吉梵合作伙伴*/
  .jf-partner-container{background-color: white;padding-top: 20px;padding-left: 20px;}
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
  .jf-background-container>.ui.segment.section>p{line-height: 30px;color: #646464;text-align: justify;padding-right: 20px;}
  /*第二行标题与内容*/
  .jf-idea-container>.header>.ui.header.h1{float:right;padding-right:30px;padding-left: 10px;font-size: 24px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.header>.ui.header.h4{margin-top: 0px;font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.ui.segment.section>p{line-height: 30px;color:#646464;text-align: justify;}
  /*位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:40px;line-height:40px;vertical-align:middle;padding-left:120px;}
  .ui.container>.twelve.wide.column.main-content{margin-top: 0px;}
  .location-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(230,230,230);position:relative;left: 1005px;top:0px;z-index:1;}








  @media screen and (max-width:1275px ){
    .into-jf>div>img{display: none;}
  }
</style>
