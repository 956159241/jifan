<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;联系我们&nbsp;>&nbsp;加入我们</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">加入我们</h1>
                <h2 class="ui header">JOIN &nbsp;&nbsp; US</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>吉梵金服主要运营金融商务服务平台。线下经营吉梵金融空间实体平台，组织并承办财经沙龙、金融培训及项目路演等各类活动。线上通过互联网财经媒体，为用户提供信息交流、品牌推广、财经自媒体平台运营等服务。</p>
              </div>
            </div>
            <img src="/static/img/PS-center-img-1.png">
            <div class="Tri-1"></div>
          </div>
        </div>
        <!--注资集团背景-->
        <div class="ui grid jf-background">
          <div class="sixteen wide column">
            <!--吉梵金服-->
            <div class="jf-background-container">
              <div class="header">
                <h1 class="ui header h1">加入我们</h1>
                <h3 class="ui header h4">JOIN &nbsp;&nbsp; US</h3>
                <hr/>
              </div>
              <div class="ui grid center">
                <div class="sixteen wide column">
                  <div class="ui grid nav">
                    <!--<div class="ui grid four column row">-->
                    <!--<div class="four wide column active">财经沙龙</div>-->
                    <!--<div class="four wide column">专业培训</div>-->
                    <!--<div class="four wide column">吉梵学习坊</div>-->
                    <!--<div class="four wide column">金融空间运营</div>-->
                    <!--</div>-->
                    <div class="four column row">
                      <div class="column"><a v-link="{ path: '/Contact-Join'}">产品经理</a></div>
                      <div class="column"><a v-link="{ path: '/Contact-Join-1'}">高级募资经理</a></div>
                      <div class="column"><a v-link="{ path: '/Contact-Join-2'}">渠道总监</a></div>
                      <div class="column active"><a v-link="{ path: '/Contact-Join-3'}">财务经理</a></div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="ui segment describe">
                <p class="top" ><img src="/static/img/Join-little-img.png">财务经理</p>
                <p class="special">岗位职责：</p>
                <p>1、编制实施公司预决算、财务收支和资金筹措计划，负责成本核算和控制；</p>
                <p>2、 进行合同收付款审核，监督成本、费用支出；</p>
                <p>3、负责帐务问题处理及税务的协调工作，维系好与银行、税务机关及政府部门的关系；</p>
                <p>4、定期组织资产清查盘点，保证财产安全；</p>
                <p>5、 完成各项财务结算、会计核算，上报财务执行情况，为管理层提供分析数据；</p>
                <p>6、 定期清理往来帐户，及时催收和清偿款项，做好帐务核对，组织审计工作；</p>
                <p>7、 审核和编制各类记账凭证，进行帐务处理，及时准确地记录公司业务内容；</p>
                <br/>
                <p class="special">任职要求：</p>
                <p>1、财务、会计、金融、投资、管理等专业本科以上学历，有注册会计师资格者优先；</p>
                <p>2、3年以上金融行业（证券、基金、私募、互联网金融）工作经验； 熟悉公募、私募、专户等业务相关；</p>
                <p>3、熟悉国家金融政策、企业财务制度及流程、会计电算化，精通相关财税法律法规；</p>
                <p>4、较强的成本管理、风险控制和财务分析的能力；</p>
                <p>5、良好的组织、协调、沟通能力和团队协作精神。</p>
                <p class="special last">欢迎致电021-60836214或发送简历至邮箱：<span>fen.cao@jifanzc.com</span>，我们会与您取得联系并进一步沟通。</p>                <br/><br/><br/>
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
  .ui.grid.nav>.four.column.row>.column{margin:0px 8px;height: 50px;line-height: 50px;vertical-align: middle;text-align: center;
    border: 1px solid rgb(209,10,27);color: rgb(209,10,27);width: 23%!important;}
  .ui.grid.nav>.four.column.row>.column:first-child{margin-left: 0px;}
  .ui.grid.nav>.four.column.row>.column:last-child{margin-right: 0px;}
  .ui.grid.nav>.four.column.row>.column>a{text-decoration: none;color: rgb(209,10,27);font-size: 16px;}
  .ui.grid.nav>.four.column.row>.column.active{color: white;background-color: rgb(209,10,27);}
  .ui.grid.nav>.four.column.row>.column.active>a{color: white;background-color: rgb(209,10,27);}
  .ui.grid.nav>.four.column.row>.column.active:after{display: block;position: absolute;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width: 1.5em;height: 1.5em;
    background:rgb(209,10,27);z-index: 2;bottom: -.7em;left: 50%;margin: 0 0 0 -.25em;}
  /*职位描述*/
  .ui.segment.describe{padding: 0px!important;background-color: rgb(245,245,245);border: 1px solid white; box-shadow: 0px 0px transparent; }
  .ui.segment.describe>p{padding-left:90px; font-size: 16px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}
  p.top{height:53px;line-height:53px;vertical-align:middle;background-color:rgb(245,245,245);padding-left: 90px;font-size: 20px;color: rgb(50, 50, 50);margin-bottom: 0px;}
  p.top>img{float:left;margin-top:12px;margin-right:10px;}
  .ui.segment.describe>p.special{padding-left: 90px;background-color: white;height:53px;line-height: 53px;vertical-align: middle;font-size: 18px;font-family: "Microsoft YaHei";
    color: rgb(50, 50, 50);}
  p.special.last{padding-left: 30px!important;color: rgb(100,100,100)!important;font-size: 16px!important;}
  p.special.last>span{color: rgb(209,10,27);}
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




  @media screen and (max-width:1275px ){
    .into-jf>div>img{display: none;}
  }
</style>
