<template>
  <div class="message-header">
    <div class="ui container">
      <div class="twelve wide column content">
        <div class="ui grid contact-info">
          <div class="sixteen wide column">
            <div class="ui dropdown WX">
              <img class="ui avatar image weixin-logo" src="/static/img/weixin-logo.png">
              <div class="menu" style="">
                <div class="item" style=""><img class="image" src="/static/img/weixin.jpg" style="">
                  <div class="sub">订阅号</div></div>


              </div>
            </div>



            <!--<span>-->
	              <!--<div class="ui inline dropdown">-->
		              <!--<div class="text">-->
			                <!--<img class="ui avatar image weixin-logo" src="/static/img/weixin-logo.png">-->
		              <!--</div>-->
		              <!--<div class="menu weixin-box">-->
			                <!--<div class="item  weixin">-->
                        <!--<img class="ui avatar image" src="/static/img/weixin.jpg">-->
                        <!--<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-->
                        <!--订阅号-->
                      <!--</div>-->
		              <!--</div>-->
	              <!--</div>-->
            <!--</span>-->
            <img src="/static/img/phone-logo.png" class="phone-logo">
          </div>
        </div>
        <div class="ui grid nav-row">
          <div class="three wide column jf-logo">
            <h2 class="ui header">
              <!--<img class="ui image" src="/static/img/jf-logo-2.png">-->
              <!--<img class="ui image" src="/static/img/jflogo.png" v-link="{ path: '/home'}">-->
              <img class="ui image" src="/static/img/jf-logo.png" v-link="{ path: '/home'}">
              <!--<div class="content">吉梵金融</div><br/>-->
              <div class="content">吉梵金融 <div class="sub header">JIFAN FINANCIAL</div></div>
            </h2>
          </div>
          <div class="two wide column search">
            <form action="http://www.baidu.com/baidu" target="_blank">
              <table>
                <tr>
                  <td class="baidu-search">
                    <input name="tn" type="hidden" value="baidu">
                    <a href="http://www.baidu.com/"></a>
                    <input type="text" name="word" class="word" id="word" v-el:word-baidu>
                    <input type="submit" value="百度搜索">
                  </td>
                </tr>
              </table>
            </form>
            <!--<div class="ui center aligned basic segment">-->
            <!--<div class="ui left icon action input">-->
            <!--<input placeholder="" type="text">-->
            <!--<div class="ui blue submit button"><a href="http://www.baidu.com">百度搜索</a></div>-->
            <!--</div>-->
            <!--</div>-->
          </div>
          <div class="eight wide column nav">
            <!--导航-->

            <div class="ui big breadcrumb">
              <div class="section" v-link="{ path: '/home', activeClass: 'active'}">首页</div>
              <!--<a class="section" :class="{ 'active': $route.path.indexOf('JF-Introduce') > 0 }" >-->
              <a class="section" :class="{ 'active': $route.path.indexOf('JF') > 0 }">
                <div class="ui pointing dropdown link item">
                  <!--<span class="text">走进吉梵</span>-->
                  <span class="section text-2">走进吉梵</span>
                  <div class="menu into">
                    <div class="item">
                      <h2>关于吉梵</h2>
                      <p>吉梵金融致力于建立一个对社会有积极价值的现代化金融机构，搭建一个能让金融专业人士，投资者，企业家共同成长，共享资源，共赢利益的开放平台。为投资者与客户创造价值，为社会进步贡献力量。
                      </p>
                    </div>
                    <div class="item" v-link="{ path: '/JF-Introduce'}">吉梵简介</div>
                    <div class="item" v-link="{ path: '/JF-Manage'}" >管理团队</div>
                    <div class="item" v-link="{ path: '/JF-Team'}">核心部门</div>
                    <div class="item" v-link="{ path: '/JF-Expert'}">专家团队</div>
                  </div>
                </div>
              </a>
              <a class="section" :class="{ 'active': $route.path.indexOf('PS') > 0 }">
                <div class="ui pointing dropdown link item">
                  <!--<span class="text">走进吉梵</span>-->
                  <span class="section text-3">产品与服务</span>
                  <div class="menu product">
                    <div class="item">
                      <h2>产品与服务</h2>
                      <p>吉梵金融致力于建立一个对社会有积极价值的现代化金融机构，搭建一个能让金融专业人士，投资者，企业家共同成长，共享资源，共赢利益的开放平台。为投资者与客户创造价值，为社会进步贡献力量。
                      </p>
                    </div>
                    <div class="item" v-link="{ path: '/PS-Fortune'}">财富管理</div>
                    <div class="item" v-link="{ path: '/PS-StockRights'}">投资银行</div>
                    <div class="item" v-link="{ path: '/PS-Finance'}">金融服务</div>
                  </div>
                </div>
              </a>
              <a class="section"  :class="{ 'active': $route.path.indexOf('News') > 0 }">
                <div class="ui pointing dropdown link item">
                  <!--<span class="text">走进吉梵</span>-->
                  <span class="section text-4">新闻资讯</span>
                  <div class="menu news">
                    <div class="item">
                      <h2>新闻资讯</h2>
                      <p>吉梵金融致力于建立一个对社会有积极价值的现代化金融机构，搭建一个能让金融专业人士，投资者，企业家共同成长，共享资源，共赢利益的开放平台。为投资者与客户创造价值，为社会进步贡献力量。
                      </p>
                    </div>
                    <div class="item" v-link="{ path: '/News-Share'}">资讯分享</div>
                    <div class="item" v-link="{ path: '/News-Dynamic'}">吉梵动态</div>
                    <div class="item" v-link="{ path: '/News-Box'}">吉梵专栏</div>
                  </div>
                </div>
              </a>
              <a class="section"  :class="{ 'active': $route.path.indexOf('Contact') > 0 }">
                <div class="ui pointing dropdown link item">
                  <span class="section text-5">联系我们</span>
                  <div class="menu contact">
                    <div class="item">
                      <h2>联系我们</h2>
                      <p>吉梵金融致力于建立一个对社会有积极价值的现代化金融机构，搭建一个能让金融专业人士，投资者，企业家共同成长，共享资源，共赢利益的开放平台。为投资者与客户创造价值，为社会进步贡献力量。
                      </p>
                    </div>
                    <div class="item" v-link="{ path: '/Contact-Addr'}">公司地址</div>
                    <!--<div class="item" @click="Contact_Addr">公司地址</div>-->
                    <div class="item" v-link="{ path: '/Contact-Join'}">加入我们</div>
                  </div>
                </div>
              </a>
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
  export default {
    replace: false,
    ready: function () {
      $('.ui.dropdown')
        .dropdown()
    },
    data () {
      return {

      }
    },
    watch: {
      '$route.path': function (newVal, oldVal) {
        this.$els.wordBaidu.value = ''
      }
    },
    methods: {
      JF_Introduce: function () {
//        window.location.href = 'JF-Introduce'
//        $('.text-1').css('color', 'black')
//        $('.section.text-2').css('color', 'yellow')
//        $('.active.section').prop('class', '.section')
      },
      JF_Manage: function () {
        window.location.href = 'JF-Manage'
      },
      JF_Team: function () {
        window.location.href = 'JF-Team'
      },
      JF_Expert: function () {
        window.location.href = 'JF-Expert'
      },
      PS_Fortune: function () {
        window.location.href = 'PS-Fortune'
      },
      PS_StockRights: function () {
        window.location.href = 'PS-StockRights'
      },
      PS_Finance: function () {
        window.location.href = 'PS-Finance'
      },
      News_Share: function () {
        window.location.href = 'News-Share'
      },
      News_Dynamic: function () {
        window.location.href = 'News-Dynamic'
      },
      News_Box: function () {
        window.location.href = 'News-Box'
      },
      Contact_Addr: function () {
        window.location.href = 'Contact-Addr'
      },
      Contact_Join: function () {
        window.location.href = 'Contact-Join'
      }
    },
    components: {
    }
  }
</script>
<style scoped>
  input {outline:none;}
  input:focus {background-color: transparent;}
  input:-webkit-autofill {-webkit-box-shadow: 0 0 0px 1000px white inset;}
  .ui.container{width: 1380px;}
  .two.wide.column{margin: 0px;padding:0px;}
  .twelve.wide.column.content{padding-left: 102px;background-color: rgb(245,245,245);width: 1380px!important;height: 133px;}
  .ui.grid.contact-info{padding:0px;margin: 0px;text-align: right;height:30px;line-height: 30px;vertical-align: middle;padding-right: 58px;}
  .contact-info>.sixteen.wide.column{padding:0px;height:30px;line-height: 30px;vertical-align: top;padding-right:95px; }
  .contact-info>.sixteen.wide.column>img{margin-top: 5px;}
  .ui.grid.contact-info>.sixteen.wide.column>span{line-height: 30px;}
  .sixteen.wide.column>span>.ui.inline.dropdown>.text>img{margin-top: -13px;margin-right: 0px;}
  /*微信下拉*/
  .ui.dropdown>.ui.avatar.image.weixin-logo{width: auto;height: auto;border-radius: 0px;margin-top: -10px;}
  .menu.weixin-box{max-width: 200px!important;min-width: 150px;}
  .item.weixin{width: 150px;}
  .item.weixin>.ui.avatar.image{border-radius: 0px;width: 150px;height:150px;max-height: 150px;}
  .ui.dropdown.WX.active.visible>.menu.transition.visible{width: 200px!important;}
  .ui.dropdown.WX>.menu{max-width:190px;text-align:center;}
  .ui.dropdown.WX>.menu>.item{max-width:190px;margin:0px;padding:0px;}
  .ui.dropdown.WX>.menu>.item>img{min-width:150px;heihgt:150px;min-height:150px;margin:0px;padding:0px;}
  .ui.dropdown.WX>.menu>.item>.sub{text-align:center;max-width:190px;}



  /*导航行*/
  .jf-logo>h2{width: 500px;}
  /*.jf-logo>h2>img{max-width: 70px;}*/
  .jf-logo>h2>img{max-width: 62px;}
  /*.three.wide.column.jf-logo>.ui.header>img{width: 3.5em;margin-top: -40px;margin-left: 60px;}*/
  .three.wide.column.jf-logo>.ui.header>img{margin-top:0px;margin-left: 60px;width:160px;}
  .jf-logo>.ui.header>.content{font-size:28px;margin-left:0px;color: rgb(63,58,57);font-family: "Microsoft YaHei";}
  .jf-logo>.ui.header>.content>.sub.header{color: rgb(63,58,57);margin-top:10px;font-size: 13px;font-family: "Microsoft YaHei";font-weight: bolder;}
  .ui.left.icon.action.input>input{border-radius: 0px;border:solid 1px #909090;width: 191px;height:30px;border-right:1px solid #909090!important; }
  .ui.blue.submit.button{border-radius: 0px!important;border:solid 1px #909090;width:90px;background-color: rgb(245,245,245);
    font-size: 12px;font-family: "Microsoft YaHei";color: rgb(50, 50, 50);margin-left: 10px;height:30px;}
  .ui.blue.submit.button>a{text-decoration: none;color: rgb(50,50,50);}
  .five.wide.column.search{line-height: 58px;vertical-align: middle;}
  .baidu-search>input{height:30px; display: none;}
  .baidu-search>input:nth-child(2){width:199px;}
  .baidu-search>input:nth-child(3){width: 199px;}
  /*导航*/
  .eight.wide.column.nav{margin-top: 20px;padding-left: 50px;padding-right:0px;}
  .eight.wide.column.nav>div{width:620px;}
  .eight.wide.column.nav>div>.section{margin-right: 50px;font-size: 16px;}
  .eight.wide.column.nav>div>.active.section{color: #d10a1b;}
  .eight.wide.column.nav>div>.section:hover{cursor:pointer;}
  .eight.wide.column.nav>div>.section{color: #323232;}
  .eight.wide.column.nav>div>.section:hover{color:#d10a1b;}
  /*导航下拉*/
  .ui.pointing.dropdown.link.item>.menu{width:520px;padding-top:50px;background-image: url("../../static/img/nav-about-img.png");margin-top: 36px!important;}
  .ui.pointing.dropdown>.menu:after {display: block;position: absolute;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width: .5em;height: .5em;box-shadow: -1px -1px 0 1px rgba(34,36,38,.15);
    background: #FFF;z-index: 2;top: -.25em;left: 6%;margin: 0 0 0 -.25em;}
  .menu>.item:nth-child(1){float:left;height:220px!important;width:250px!important;white-space:normal;margin-right: 35px;color: black;
    text-align: justify;background: rgba(0,0,0,0)!important;margin-left: 10px;}
  .menu>.item{width:0px;padding-left: 0px!important;font-size: 14px;color: #646464;background-color: rgba(0,0,0,0);}
  .menu>.item:hover{background: rgba(0,0,0,0)!important;color: red!important;z-index: 13;}
  .menu>.item:visited{background: rgba(0,0,0,0)!important;}
  .menu>.item:nth-child(1):hover{color: #646464;}
  .menu>.item:nth-child(1):visited{color: #646464; font-weight:100!important;}
  .ui.dropdown>.menu>.item {font-size: 14px;color:#646464;}
  .ui.dropdown .menu .active.item {font-weight: 100;color: rgba(0,0,0,1);box-shadow: none;z-index: 12;background-color: rgba(0,0,0,0);}
  .ui.pointing.dropdown.link.item>.menu>.item>h2{font-size: 18px;color: #646464;}
  .ui.pointing.dropdown.link.item>.menu>.item>p{font-size: 12px;color: #646464;line-height: 20px;text-align:justify;}
  /*确定每一个下拉所在位置*/
  .ui.pointing.dropdown.link.item>.menu.into{margin-left: -60px;border-radius:0px 0px 10px 10px;border: 0px;border-top:2px solid #d10a1b;}
  .ui.pointing.dropdown.link.item>.menu.into:after{content: "";position: absolute;background-color: rgba(245,245,245,0);top:-18px;
    left:85px;width: 0px;height: 0px;box-shadow: 0px 0px transparent;border: 8px solid transparent;border-bottom-color:#d10a1b;transform: rotate(0deg);}

  .ui.pointing.dropdown.link.item>.menu.product{margin-left: -179px;border-radius:0px 0px 10px 10px;border: 0px;border-top:2px solid #d10a1b;}
  .ui.pointing.dropdown.link.item>.menu.product:after{content: "";position: absolute;background-color: rgba(245,245,245,0);top:-18px;
    left:215px;width: 0px;height: 0px;box-shadow: 0px 0px transparent;border: 8px solid transparent;border-bottom-color:#d10a1b;transform: rotate(0deg);}

  .ui.pointing.dropdown.link.item>.menu.news{margin-left: -313px;border-radius:0px 0px 10px 10px;border: 0px;border-top:2px solid #d10a1b;}
  .ui.pointing.dropdown.link.item>.menu.news:after{content: "";position: absolute;background-color: rgba(245,245,245,0);top:-18px;
    left:342px;width: 0px;height: 0px;box-shadow: 0px 0px transparent;border: 8px solid transparent;border-bottom-color:#d10a1b;transform: rotate(0deg);}

  .ui.pointing.dropdown.link.item>.menu.contact{margin-left: -434px;border-radius:0px 0px 10px 10px;border: 0px;border-top:2px solid #d10a1b;}
  .ui.pointing.dropdown.link.item>.menu.contact:after{content: "";position: absolute;background-color: rgba(245,245,245,0);top:-18px;
    left:462px;width: 0px;height: 0px;box-shadow: 0px 0px transparent;border: 8px solid transparent;border-bottom-color:#d10a1b;transform: rotate(0deg);}


  @media screen and (max-width:1330px) {
    .five.wide.column.search{display: none;}
  }
  @media screen and (max-width:920px) {
    .three.wide.column.jf-logo{display: none;}
  }

</style>
<!–[if IE]>
<style type=”text/css”>
  .sixteen.wide.column>span>.ui.inline.dropdown>.text>img{margin-top: 0px;margin-right: 0px;}
</style>
<![endif]–>
