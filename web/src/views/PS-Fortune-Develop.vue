<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;产品与服务&nbsp;>&nbsp;财富管理</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">财富管理</h1>
                <h2 class="ui header">WEALTH  MANAGEMENT</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>在财富管理领域，涵盖了财务规划、投资组合管理和一系列综合金融资产配置的投资咨询服务，针对财富积累、财富增值、财富保全以及财富传承等方面的专业建议，运用各种金融工具为高净值人群、家族及企业提供资产配置规划、法律服务、税收规划、金融资产投资管理、海外资产配置及家族账户委托管理等全方位财富管理服务。
                </p>
              </div>
            </div>
            <img src="/static/img/PS-Study-img.png">
            <div class="Tri-1"></div>
          </div>
        </div>
        <!--注资集团背景-->
        <div class="ui grid jf-background">
          <div class="sixteen wide column">
            <!--吉梵金服-->
            <div class="jf-background-container">
              <div class="header">
                <h1 class="ui header h1">财富管理</h1>
                <h3 class="ui header h4">WEALTH MANAGEMENT</h3>
                <hr/>
              </div>
              <div class="ui grid center">
                <div class="sixteen wide column">
                  <div class="ui grid nav">
                    <div class="five column row">
                      <div class="column"><a v-link="{ path: '/PS-Fortune'}">产品中心</a></div>
                      <div class="column"><a v-link="{ path: '/PS-Fortune-Bank'}">私人银行</a></div>
                      <div class="column"><a v-link="{ path: '/PS-Fortune-Office'}">家族办公室</a></div>
                      <div class="column"><a v-link="{ path: '/PS-Fortune-Finance'}">吉梵环球金融</a></div>
                      <div class="column active"><a v-link="{ path: '/PS-Fortune-Develop'}">财富管理研究与发展</a></div>
                    </div>
                  </div>
                 <!--四张图片-->
                  <div class="ui grid pic-list">
                    <div class="four wide column">
                      <img src="/static/img/PS-Develop-img-1.png">
                      <p>行业研究</p>
                    </div>
                    <div class="four wide column">
                      <img src="/static/img/PS-Develop-img-2.png">
                      <p>家族配置白皮书</p>
                    </div>
                    <div class="four wide column">
                      <img src="/static/img/PS-Develop-img-3.png">
                      <p>高端访谈</p>
                    </div>
                    <div class="four wide column">
                      <img src="/static/img/PS-Develop-img-4.png">
                      <p>金融私董会</p>
                    </div>
                  </div>
                  <br/><br/>


                </div>
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
  /*.into-jf-container{background-color: rgb(245,245,245);height:380px;width:921px;float: right;text-align: center;padding-top:58px;padding-right:160px;padding-left:100px;}*/
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
  .jf-background-container{background-color: rgb(255,255,255);padding-top:20px;}
  /*.jf-background-container{background-color: rgb(255,255,255);height:340px;}*/
  .jf-background-container>.header{text-align: left;}
  .jf-background-container>.header>.ui.header.h1{float:left;padding-right:10px;margin-left: 20px;}
  .jf-background-container>.header>.ui.header.h4{}
  .jf-background-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  /*内部导航*/
  .ui.grid.center{position:relative;margin:50px 0px 0px 0px;padding:0px;padding:0px 90px;}
  .ui.grid.center>div{background-color: white;padding-left: 0px;padding-right:0px;}
  .ui.grid.nav{height:140px;padding-left: 14px;}
  .ui.grid.nav>.five.column.row>.column{margin:0px 8px;height: 50px;line-height: 50px;vertical-align: middle;text-align: center;
    border: 1px solid rgb(209,10,27);color: rgb(209,10,27);width: 18%!important;}
  .ui.grid.nav>.five.column.row>.column:first-child{margin-left: 0px;}
  .ui.grid.nav>.five.column.row>.column:last-child{margin-right: 0px;}
  .ui.grid.nav>.five.column.row>.column>a{text-decoration: none;}
  .ui.grid.nav>.five.column.row>.column.active{color: white;background-color: rgb(209,10,27);}
  .ui.grid.nav>.five.column.row>.column.active>a{color: white;}
  .ui.grid.nav>.five.column.row>.column>a{color: rgb(209,10,27);}
  .ui.grid.nav>.five.column.row>.column.active:after{display: block;position: absolute;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width: 1.5em;height: 1.5em;
    background:rgb(209,10,27);z-index: 2;bottom: -.7em;left: 50%;margin: 0 0 0 -.25em;}
  /*第一行图文*/
  .text-pic{height:383px;overflow: hidden;}
  .text-pic>img{margin: 0px;padding:0px;left: 0px;z-index: -1;}
  .text-pic>.ui.icon.header{width:485px;margin-left: -160px!important;text-align: left;background-color:white;padding-left: 20px;padding-top:30px;}
  .text-pic>.ui.icon.header:after{display: block;position:relative;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width: 1em;height: 1em;
    background-color:white;z-index: 0;bottom: 8em;left:-25px;margin: 0 0 0 -.25em;bottom:170px;}
  .text-pic>.ui.icon.header>.content>span{font-size: 16px!important;}
  .text-pic>.ui.icon.header>.content>.sub.header{padding-top: 18px;}
  /*第二行图文*/
  /*.text-pic-1{display:table-cell}*/
  .text-pic-1{height:353px;overflow: hidden;margin-bottom: 30px;}
  .text-pic-1>.ui.icon.header{width: 500px;z-index: 2;margin-right: -300px;text-align: left;padding-left: 20px;padding-top: 149px;}
  .text-pic-1>.ui.icon.header>.content{background-color: white;}
  .text-pic-1>img{float: right;z-index: -1;margin-left:130px;}
  .text-pic-1>.ui.icon.header>.content>.sub.header{padding-top: 18px;padding-right: 30px;}
  .text-pic-1>.ui.icon.header>.content:before{display: block;position:relative;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width: 1em;height: 1em;
    background-color:white;z-index: 0;bottom: 8em;left:473px;margin: 0 0 0 -.25em;bottom:-53px;}
  .text-pic-1>.ui.icon.header>.content>span{font-size: 16px!important;}
  .ui.grid.pic-list{text-align: center;}
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
  .jf-idea-container>.header>.ui.header.h1{float:right;padding-right:10px;padding-left: 10px;font-size: 24px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.header>.ui.header.h4{margin-top: 0px;font-size: 14px;font-family: "Microsoft YaHei UI";font-weight: bold;}
  .jf-idea-container>.ui.segment.section>p{line-height: 30px;color:#646464;text-align: justify;}
  /*位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:40px;line-height:40px;vertical-align:middle;padding-left:120px;}
  .ui.container>.twelve.wide.column.main-content{margin-top: 0px;}
  .location-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(230,230,230);position:relative;left: 1005px;top:0px;z-index:1;}
  /*内容红色小导航*/
  .ui.grid.nav>.four.column.row{width:100%;}
  .ui.grid.nav>.four.column.row>.column{width: 23%!important;}
  .ui.grid.nav>.five.column.row>.column>a{text-decoration: none;font-size: 16px;}
  .ui.grid.nav>.five.column.row>.column.active>a{color: white;font-weight: bold;  }



  @media screen and (max-width:1275px ){
    .into-jf>div>img{display: none;}
  }
</style>
