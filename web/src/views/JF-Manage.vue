<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;走进吉梵&nbsp;>&nbsp;管理团队</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">管理团队</h1>
                <h2 class="ui header">MANAGEMENT TEAM</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>随着公司的发展壮大，吉梵金融成为业内高端人才的汇聚地，来自各个领域的专业人才，专注于投资与专业金融服务。</p>
              </div>
            </div>
            <img src="/static/img/JF-Manage-img.png">
            <div class="Tri-1"></div>
          </div>
        </div>
        <!--注资集团背景借用-->
        <div class="ui grid jf-background">
          <div class="sixteen wide column">
            <!--吉梵金服借用-->
            <div class="jf-background-container">
              <br/>
              <div class="header">
                <h1 class="ui header h1">管理团队</h1>
                <h4 class="ui header h4">MANAGEMENT TEAM</h4>
                <hr/>
              </div>

              <div class="ui grid manager">
                <div class="sixteen wide column">
                  <h2 class="ui icon header manager">
                    <img src="/static/img/JF-Manage-1-1.png">
                    <div class="content">敖宇
                      <div class="sub header"><hr/></div>
                      <div class="sub header">董事长</div>
                    </div>
                  </h2>
                  <div class="ui segment manager-Introduce">
                    <p>现任吉梵金融董事长兼总裁，全面负责吉梵金融经营管理工作。十五年金融机构管理经验，曾供职于中银国际证券、东北证券、大华期货公司、港九期货公司，长期参与证券一、二级市场及海外金融市场投资，新三板企业投融资业务。</p>
                  </div>
                </div>
                <div class="eight wide column">
                  <h2 class="ui icon header manager">
                    <img src="/static/img/JF-Manage-2.jpg">
                    <div class="content">甘懋旭
                      <div class="sub header"><hr/></div>
                      <div class="sub header">董事、副总裁</div>
                    </div>
                  </h2>
                  <div class="ui segment manager-Introduce">
                    <p>现任吉梵金融副总裁，主要负责吉梵金服业务板块的运营管理。二十年金融从业经验，曾供职于中银国际、国信证券、长城证券等多家国内大型券商，是国内券商从坐商向行商转变的践行者，具有丰富的团队建设和管理经验。曾作为中国银行福建省分行的首席财富顾问，负责全辖高净值客户的管理，具备丰富的基金、股票、债券等金融产品的投资和管理经验。</p>
                  </div>
                </div>
                <div class="eight wide column">
                  <h2 class="ui icon header manager">
                    <img src="/static/img/JF-Manage-3-3.png">
                    <div class="content">黄云芳
                      <div class="sub header"><hr/></div>
                      <div class="sub header">董事、财务总监</div>
                    </div>
                  </h2>
                  <div class="ui segment manager-Introduce">
                    <p>现任上海吉梵资产管理有限公司董事兼财务总监，具有高级会计师职称。曾在上海国资企业从事财务管理专业35年，曾任职上海住总物资总公司、上海建工物资有限公司、上海城建物资有限公司总会计师，为企业经营格局、管理模式调整过程中的财务治理、价值管理、战略控制及规范运作发挥了重要作用。具备较高的业务水平和丰富的财务管理经验。</p>
                    <br/><br/>
                  </div>
                </div>
              </div>

            </div>
            <br/><br/><br/>


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
  .into-jf-container>.ui.segment>section>p{line-height: 20px;}
  .into-jf>div>img{margin-top: 66px;margin-right: -30px;}
  .Tri-1{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(229,27,48);position:absolute;left: 130px;bottom:75px;z-index:1; }
  /*吉梵金服*/
  .ui.grid.jf-background{z-index:999;padding:0px 100px;margin-top: -108px;text-align: left;}
  .jf-background-container{background-color: rgb(255,255,255);}
  .jf-background-container>.header{text-align: left;}
  .jf-background-container>.header>.ui.header.h1{float:left;padding-right:10px;margin-left: 20px;}
  .jf-background-container>.header>.ui.header.h4{}
  .jf-background-container>.header>hr{width:25px;border: 2px solid #d10a1b;float: left;margin-top: -10px;}
  .jf-background-container>img{float: left;padding-right:20px;padding-top: 30px;}
  .jf-background-container>.ui.segment.section{background-color: rgba(255,255,255,0);border:0px;box-shadow: 0px 0px transparent;padding-top: 50px;}
  .jf-background-container>.ui.segment>section>p{line-height: 30px;}
  /*高管简介*/
  .ui.grid.manager{text-align: center;margin-top: 100px;}
  .ui.grid.manager>.sixteen.wide.column>.ui.segment.manager-Introduce{padding:0px 355px;}
  .manager>div>.sub.header{ font-size: 16px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);font-weight: bold;    margin-top: 10px;}
  .ui.icon.header.manager>img{width: auto;height:236px;border-radius: 10px;}
  .ui.icon.header.manager>.content{margin-top: 20px;font-size: 24px;}
  .sub.header>hr{width:30px;border: 2px solid #d10a1b;}
  .ui.segment.manager-Introduce{border: 0px;box-shadow: 0px 0px transparent;padding-left:80px;margin-top: 0px;padding-top: 0px;text-align: justify;}
  .ui.segment.manager-Introduce:nth-of-type(odd){padding-right:50px;}
  .ui.segment.manager-Introduce>p{line-height: 30px;color: #646464;letter-spacing: 0.2em;}
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
  .line>.line-location-Tri{float:right;width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(245,245,245);position:relative;right: 100px;z-index:1;top:33px;}




  @media screen and (max-width:1275px ){
    .into-jf>div>img{display: none;}
  }
</style>
