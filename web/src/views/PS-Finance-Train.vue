<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">
        <!--位置导航-->
        <div class="location" id="location">
          <span><span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;产品与服务&nbsp;>&nbsp;金融服务</span>
          <div class="location-Tri"></div>
        </div>



        <div class="ui grid into-jf">
          <div class="sixteen wide column">
            <div class="into-jf-container">
              <div class="header">
                <h1 class="ui header">金融服务</h1>
                <h2 class="ui header">Financial &nbsp;Services</h2>
                <hr/>
              </div>
              <div class="ui segment section">
                <p>在金融服务领域，投资创建了集办公与金融会所功能为一体的吉梵金融空间作为实体平台，组织并承办财经沙龙、金融培训及项目路演等各类活动，同时链接互联网资源，搭建金融市场的交流学习与商务合作平台，通过线上为机构输出财经直播、研究资讯、品牌推广等服务。
                </p>
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
                <h1 class="ui header h1">金融服务</h1>
                <h3 class="ui header h4">Financial &nbsp;&nbsp; Services</h3>
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
                      <div class="column"><a v-link="{ path: '/PS-Finance'}">财经沙龙</a></div>
                      <div class="column active"><a v-link="{ path: '/PS-Finance-Train'}">专业培训</a></div>
                      <div class="column"><a v-link="{ path: '/PS-Finance-Study'}">吉梵学习坊</a></div>
                      <div class="column"><a v-link="{ path: '/PS-Finance-Space'}">金融空间运营</a></div>
                    </div>
                  </div>
                  <!--列表-->
                  <!--培训列表-->

                  <div class="ui grid manager">
                    <div class="eight wide column">
                      <h2 class="ui icon header manager">
                        <img src="/static/img/PS-Train-img-1.png">
                        <div class="content">傅吾豪
                          <div class="sub header"><hr/></div>
                          <div class="sub header">上海傅吾豪投资管理有限公司   董事长</div>
                          <div class="sub header">海峡金融营销研究中心   执行长</div>
                        </div>
                      </h2>
                      <div class="ui segment manager-Introduce">
                        <p>曾任：</p>
                        <p>台湾德扬证券投资顾问股份有限公司          总经理</p>
                        <p>上海红顶金融工程研究中心 教育推广部      总经理</p>
                        <p>上海社会科学院『证券市场研究』  杂志社 营运长</p>
                        <p>上海证豪投资管理有限公司                        董事长</p>
                        <p>台湾康和证券集团大陆区                           总顾问</p>
                        <p>经历：</p>
                        <p>全国102家证券公司营销服务管理专业讲师</p>
                        <p>工、农、中、建、交、招商银行个金部专任讲师</p>
                        <p>11家基金公司特约讲师</p>
                        <p>12省证券业协会从业人员后续职业培训讲师</p>
                        <p>海内外投资理财讲座、金融营销管理服务教育训练1300场</p>
                        <p>著作：</p>
                        <p>【股票直效技术分析秘籍Securities Straight Analysis Bible一至九册】</p>
                        <p>【操盘圣经】、【股票投资决策流程与风险控制】</p>
                        <p>2001年上海巡讲【股票投资风险控制与执行】</p>
                        <!--<p>2002年全国巡讲【证券营销与服务技能提升】</p>-->
                        <!--<p>2003年全国巡讲【第二次理财革命】</p>-->
                        <!--<p>2004年全国巡讲【具有中国特色的理财顾问】</p>-->
                        <!--<p>2005年全国巡讲【投资风险教育与投资技巧】</p>-->
                        <!--<p>2006年全国巡讲【营业部创新经营之道】【营业部长期创利之道】</p>-->
                        <!--<p>2007年发表著作【操盘圣经】，成为财经类排行榜畅销书</p>-->
                        <!--<p>2008年全国巡讲【国内券商营业部经营危机与解决方案】</p>-->
                        <!--<p>2009年全国巡讲【新竞争环境下传统业务新思维】【证券服务模式创新】</p>-->
                        <!--<p>2010年全国巡讲【解读证券经纪业务转型与发展的方向和途径】</p>-->
                        <!--<p>2011年全国巡讲【证券行业蓝海战略的运用】【投资顾问专业能力提升】</p>-->
                        <!--<p>2012年发表著作【投资工具书：股票投资决策流程与风险控制】</p>-->
                        <!--<p>2013年全国巡讲【创新行销与财富管理专业能力提升】</p>-->
                        <!--<p>2014年全国巡讲【投资决策流程与风险控制高级讲座】 </p>-->
                        <!--<p>2015年全国巡讲【财富管理时代管理者思路创新与变革】</p>-->
                        <div class="ui accordion">
                          <div class="title">点击查看更多</div>
                          <div class="content">
                            <!--<p class="transition hidden">【操盘圣经】、【股票投资决策流程与风险控制】</p>-->
                            <!--<p class="transition hidden">2001年上海巡讲【股票投资风险控制与执行】</p>-->
                            <p class="transition hidden">2002年全国巡讲【证券营销与服务技能提升】</p>
                            <p class="transition hidden">2003年全国巡讲【第二次理财革命】</p>
                            <p class="transition hidden">2004年全国巡讲【具有中国特色的理财顾问】</p>
                            <p class="transition hidden">2005年全国巡讲【投资风险教育与投资技巧】</p>
                            <p class="transition hidden">2006年全国巡讲【营业部创新经营之道】【营业部长期创利之道】</p>
                            <p class="transition hidden">2007年发表著作【操盘圣经】，成为财经类排行榜畅销书</p>
                            <p class="transition hidden">2008年全国巡讲【国内券商营业部经营危机与解决方案】</p>
                            <p class="transition hidden">2009年全国巡讲【新竞争环境下传统业务新思维】【证券服务模式创新】</p>
                            <p class="transition hidden">2010年全国巡讲【解读证券经纪业务转型与发展的方向和途径】</p>
                            <p class="transition hidden">2011年全国巡讲【证券行业蓝海战略的运用】【投资顾问专业能力提升】</p>
                            <p class="transition hidden">2012年发表著作【投资工具书：股票投资决策流程与风险控制】</p>
                            <p class="transition hidden">2013年全国巡讲【创新行销与财富管理专业能力提升】</p>
                            <p class="transition hidden">2014年全国巡讲【投资决策流程与风险控制高级讲座】</p>
                            <p class="transition hidden">2015年全国巡讲【财富管理时代管理者思路创新与变革】</p>
                          </div>
                        </div>
                      </div>
                      <h2 class="ui icon header link">
                        <div class="content">
                          <div class="sub header" v-link="{ path: '/PS-Finance-Train-lesson-1#location'}">进入课程</div>
                        </div>
                      </h2>
                    </div>
                    <div class="eight wide column">
                      <h2 class="ui icon header manager">
                        <img src="/static/img/PS-Train-img-2.png">
                        <div class="content">夏文庆
                          <div class="sub header"><hr/></div>
                          <div class="sub header">上海鑫舟投资咨询有限公司CEO、</div>
                          <div class="sub header">上海鑫舟保险代理有限公司董事长、</div>
                          <div class="sub header">上海鑫航信息科技有限公司董事长</div>
                        </div>
                      </h2>
                      <div class="ui segment manager-Introduce">
                        <p>  学历：工商管理学硕士MBA（澳大利亚Deakin University）；金融、国际商业学士学位（澳大利亚 悉尼理工大学UTS）工作背景：20年财富管理经验</p>
                        <p>现任上海鑫舟投资咨询有限公司CEO、上海鑫舟保险代理有限公司董事长、上海鑫航信息科技有限公司董事长。</p>
                        <p>历任：第六、七、八届上海十佳理财之星评委；首届（2012）、第二、三届全国独立财富管理机构和理财明星榜评委；首届(2012)全国金融理财师大赛评选委员；各大金融机构内部理财规划大赛评委（较近期的包括兴业银行总行、建行浙江分行、建行山东分行、浦发银行山东分行等）台湾：弘利投资顾问有限公司 副总经理；香港：ipac财务策划公司 高级副总裁；澳大利亚：HSBC 汇丰银行私人银行高级理财经理、ipac 金融服务集团高级理财经理、GIO保险公司理财经理、Sax bridge 金融集团理财顾问；</p>
                        <!--<p>著有《理财师实务手册》，现在《投资有道》，《江苏银行业》，《第一财经日报》撰写投资和理财专栏。</p>-->
                        <!--<p>讲师经历：10年讲师经验，始终站在理财第一线的培训师</p>-->
                        <!--<p>2005年起，即在香港受邀参与FCHFP特许认证理财规划师在华南及华东地区的培训授课。</p>-->
                        <!--<p>2006年初回国后，即参与中国金融理财标准委员会AFP、CFP、EFP的培训授课，是国内最资深、授课时间最多、授课内容范围最广的CFP认证系列讲师之一。</p>-->
                        <!--<p>2008年后，开始自行研发鑫舟理财师实务培训体系，以理财经理职业生涯发展路径为节点，完成了PFP预备役理财师培训课程、新晋理财经理上岗培训、后认证时代资深理财经理实务培训、财富管理和私人银行实务培训、理财业务营销实务培训等5大系列课程的设计，并在各大金融机构进行内训授课，广受好评。</p>-->
                        <!--<p>2011年后针对培训课堂在解决学员具体问题的局限性，带领团队自行开发设计信息化答疑解惑平台，2014年度年亲自完成1850条来自一线理财经理的问题，对国内理财业务第一线有着非常深刻的认识。</p>-->
                        <!---->
                        <div class="ui accordion">
                          <div class="title">点击查看更多</div>
                          <div class="content">
                            <p class="transition hidden">著有《理财师实务手册》，现在《投资有道》，《江苏银行业》，《第一财经日报》撰写投资和理财专栏。</p>
                            <p class="transition hidden">讲师经历：10年讲师经验，始终站在理财第一线的培训师</p>
                            <p class="transition hidden">2005年起，即在香港受邀参与FCHFP特许认证理财规划师在华南及华东地区的培训授课。</p>
                            <p class="transition hidden">2006年初回国后，即参与中国金融理财标准委员会AFP、CFP、EFP的培训授课，是国内最资深、授课时间最多、授课内容范围最广的CFP认证系列讲师之一。</p>
                            <p class="transition hidden">2008年后，开始自行研发鑫舟理财师实务培训体系，以理财经理职业生涯发展路径为节点，完成了PFP预备役理财师培训课程、新晋理财经理上岗培训、后认证时代资深理财经理实务培训、财富管理和私人银行实务培训、理财业务营销实务培训等5大系列课程的设计，并在各大金融机构进行内训授课，广受好评。</p>
                            <p class="transition hidden">2011年后针对培训课堂在解决学员具体问题的局限性，带领团队自行开发设计信息化答疑解惑平台，2014年度年亲自完成1850条来自一线理财经理的问题，对国内理财业务第一线有着非常深刻的认识。</p>
                          </div>
                        </div>
                      </div>
                      <h2 class="ui icon header link">
                        <div class="content">
                          <div class="sub header" v-link="{ path: '/Lesson-Empty#location'}">进入课程</div>
                        </div>
                      </h2>
                    </div>
                    <div class="eight wide column">
                      <h2 class="ui icon header manager">
                        <img src="/static/img/manager-2.png">
                        <div class="content">甘懋旭
                          <div class="sub header"><hr/></div>
                          <div class="sub header">吉梵资产管理有限公司合伙人  副总裁</div>
                        </div>
                      </h2>
                      <div class="ui segment manager-Introduce">
                        <p>简历：金融行业从业二十年，曾供职于中银国际，国信证券，长城证券等多家国内大型券商。是国内券商从坐商向行商转变的践行者，具有丰富的团队建设和管理经验。曾作为中国银行福建省分行的首席投资顾问负责全辖三级财富体系的高净值客户资产管理，具备丰富的基金、股票、债券市场的业务管理经验。曾多年任福建证券业协会新员工入职培训讲师。</p>
                        <br/><br/>
                      </div>
                      <h2 class="ui icon header link">
                        <div class="content">
                          <div class="sub header" v-link="{ path: '/Lesson-Empty#location'}">进入课程</div>
                        </div>
                      </h2>
                    </div>
                    <div class="eight wide column">
                      <h2 class="ui icon header manager">
                        <img src="/static/img/manager-1.png">
                        <div class="content">敖宇
                          <div class="sub header"><hr/></div>
                          <div class="sub header">上海吉梵金融董事长兼总裁</div>
                        </div>
                      </h2>
                      <div class="ui segment manager-Introduce">
                        <p>经历：十五年金融机构管理的经验，曾供职于中银国际证券、东北证券、大华期货、港九期货等公司，长期参与证券二级市场、海外市场投资及新三板企业投融资业务。所在营业部业绩由地区中下游水平提升至地区一百多家营业部中排名第一，并连续数年保持。多年参与香港市场证券业务，熟悉香港、台湾地区证券业务实践经验。近年参与多项证券业务创新项目，联合金融IT公司，金融数据库、金融云计算、证券研究等机构，发起网络理财社区、移动财经应用、证券量化投资等创新项目研发。</p>
                      </div>
                      <h2 class="ui icon header link">
                        <div class="content">
                          <div class="sub header" v-link="{ path: '/Train-Aoyu-Lesson-1#location'}">进入课程</div>
                        </div>
                      </h2>
                    </div>
                    <div class="eight wide column">
                      <h2 class="ui icon header manager">
                        <img src="/static/img/PS-Train-img-3.png">
                        <div class="content">黄律圣
                          <div class="sub header"><hr/></div>
                          <div class="sub header">台湾期权和财富管理专家</div>
                        </div>
                      </h2>
                      <div class="ui segment manager-Introduce">
                        <p>简历：企管硕士学位，为现任台湾期权和财富管理专家，2001年进入期货业开始教授权全台湾券商期货选择权(当时刚推出)，曾经担任数百家证券分公司期货专业讲师、期货顾问事业研究员，并任教于大学（具备合格大学讲师资格）、台湾金融研训院讲师、台湾期货公会讲师(CTA,期货信托基金)、台湾最大金融证照考照班（期货业务员证照及证券分析师证照）讲师、中国银河证券2000万资产人民币核心客户、一对一(10亿人民币资产客户)期货讲师等；还担任过台湾最大报财经专栏主笔、中国最大入口网站「新浪网」股指期货专栏作家。现为台湾最大金控银行理财讲师(10年),直接和全台湾前10大银行理财专员做商品教学和资产管理建议。</p>
                      </div>
                      <h2 class="ui icon header link">
                        <div class="content">
                          <div class="sub header" v-link="{ path: '/Lesson-Empty#location'}">进入课程</div>
                        </div>
                      </h2>

                      <br/><br/><br/> <br/><br/><br/>
                    </div>

                  </div>
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
      $('.ui.accordion')
        .accordion()
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
    border: 1px solid rgb(209,10,27);color: rgb(209,10,27);}
  .ui.grid.nav>.four.column.row>.column:first-child{margin-left: 0px;}
  .ui.grid.nav>.four.column.row>.column:last-child{margin-right: 0px;}
  .ui.grid.nav>.four.column.row>.column>a{text-decoration: none;color: rgb(209,10,27);}
  .ui.grid.nav>.four.column.row>.column.active{color: white;background-color: rgb(209,10,27);}
  .ui.grid.nav>.four.column.row>.column.active>a{color: white;background-color: rgb(209,10,27);}
  .ui.grid.nav>.four.column.row>.column.active:after{display: block;position: absolute;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width: 1.5em;height: 1.5em;
    background:rgb(209,10,27);z-index: 2;bottom: -.7em;left: 50%;margin: 0 0 0 -.25em;}
  /*培训导航内列表列表*/
  .ui.grid.manager{text-align: center;margin-top: 100px;}
  .manager>div>.sub.header{ font-size: 16px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);font-weight: bold;    margin-top: 10px;}
  .ui.icon.header.manager>img{width: auto;height:100%;}
  .ui.icon.header.manager>.content{margin-top: 20px;}
  .sub.header>hr{width:30px;border: 2px solid #d10a1b;}
  .ui.segment.manager-Introduce{text-align: left;border: 0px;box-shadow: 0px 0px transparent;padding-left:80px;padding-top: 0px;margin-top: 0px;}
  .ui.segment.manager-Introduce>.ui.accordion>.title{color:rgb(209,10,27);}
  .ui.segment.manager-Introduce:nth-of-type(odd){padding-right:50px;}
  .ui.segment.manager-Introduce>p{line-height:20px;font-size: 14px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);margin:5px 0px;text-align:justify;}
  .eight.wide.column:nth-child(2)>.manager-Introduce{margin-top:16px;}
  .eight.wide.column:nth-child(2)>.manager-Introduce>p{line-height: 26px;}
  .ui.icon.header.link>.content>.sub.header{height: 50px;width:190px;border: 1px solid rgb(209,10,27);line-height: 50px;vertical-align: middle;color: rgb(209,10,27);cursor: pointer;}
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
  .ui.grid.nav>.four.column.row>.column>a{text-decoration: none;font-size: 16px;}
  .ui.grid.nav>.four.column.row>.column.active>a{color: white;font-size: 18px!important;  }





  @media screen and (max-width:1275px ){
    .into-jf>div>img{display: none;}
  }
</style>
