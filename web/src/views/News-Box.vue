<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">



        <!--新闻资讯-->
        <div class="list-box" id="location">
          <div class="ui segment">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              <span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;新闻资讯&nbsp;>&nbsp;吉梵专栏</p>
          </div>
          <div class="ui grid jf-news">
            <div class="sixteen wide column">
              <!--布置-->
              <div class="ui six steps jf-news-nav">
                <div class="step first">
                  <div class="jf-news-Tri"></div>
                  <div class="content">
                    <div class="title">
                      <div class="header">
                        <h1 class="ui header">吉梵专栏</h1>
                        <h2 class="ui header">JIFAN&nbsp;&nbsp;BOX</h2>
                        <hr/>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="active step" v-link="{ path: '/News-BOX'}">
                  <div class="content">
                    <div class="title">
                      <div class="header little">
                        <h1 class="ui header">2016</h1>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="step stay first">
                  <div class="content">
                    <div class="title">
                      <div class="header little">
                        <h1 class="ui header">2015</h1>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="step  stay">
                  <div class="content">
                    <div class="title">
                      <div class="header little">
                        <h1 class="ui header">2014</h1>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="step  stay">
                  <div class="content">
                    <div class="title">
                      <div class="header little">
                        <h1 class="ui header">2013</h1>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="step stay">
                  <div class="content">
                    <div class="title">
                      <div class="header little">
                        <h1 class="ui header">·&nbsp;·&nbsp;·</h1>
                      </div>
                    </div>
                  </div>
                </div>

              </div>
              <!--菜单-->
            </div>
          </div>
        </div>
        <!--新闻列表-->
        <div class="ui grid jf-news-list">
          <div class="sixteen wide column">
            <h1>更新中……</h1>
            <!--<div class="ui comments">-->
              <!--<div class="comment">-->
                <!--<a class="avatar">-->
                  <!--<img src="/static/img/Box-List-1-img-1.png">-->
                <!--</a>-->
                <!--<div class="content">-->
                  <!--<a class="author" v-link="{ path: '/Box-List-1#location'}">吉梵金融 | 闽商资本联合会企业家上海行活动纪实</a>-->
                  <!--<div class="text">7.17日下午闽商资本联合会企业家一行来到吉梵金融参观，学习，交流，吉梵金融为来自福建的企业家们安排了目前企业家最关心的、高品质的学习交流活动。-->
                    <!--　　</div>-->
                  <!--<a class="author little" v-link="{ path: '/Box-List-1#location'}">阅读全文&nbsp;>&nbsp;</a>-->
                <!--</div>-->
              <!--</div>-->
            <!--</div>-->
          </div>
          <!--<div class="sixteen wide column">-->
            <!--<div class="ui comments">-->
              <!--<div class="comment">-->
                <!--<a class="avatar">-->
                  <!--<img src="/static/img/Box-List-2-img-1.png">-->
                <!--</a>-->
                <!--<div class="content">-->
                  <!--<a class="author" v-link="{ path: '/Box-List-2#location'}">《全国证券营业部总经理实战研讨交流会》活动纪实</a>-->
                  <!--<div class="text">7.16-7.17日来自全国各地的24名营业部总经理共聚上海吉梵金融空间，与各位专业老师一起共同探讨、共同交流营业部管理的新思路，新方法。 整个活动为期两天，总共邀请了4位金融领域的四名专家，他们都是从事金融领域工作20年以上的“老兵”，他们理论知识丰富……</div>-->
                  <!--<a class="author little" v-link="{ path: '/Box-List-2#location'}">阅读全文&nbsp;>&nbsp;</a>-->
                <!--</div>-->
              <!--</div>-->
            <!--</div>-->
          <!--</div>-->
          <!--<div class="sixteen wide column">-->
            <!--<div class="ui comments">-->
              <!--<div class="comment">-->
                <!--<a class="avatar">-->
                  <!--<img src="/static/img/Box-List-3-img-1.png">-->
                <!--</a>-->
                <!--<div class="content">-->
                  <!--<a class="author" v-link="{ path: '/Box-List-3#location'}">《致良知是一种伟大的力量》2016年第一季学习会</a>-->
                  <!--<div class="text">7月14日至16日由阳明教育研究院主办的《致良知是一种伟大的力量》2016年第一季学习会在吉梵金融举行，现场30多位参加本次学习会。</div>-->
                  <!--<a class="author little" v-link="{ path: '/Box-List-3#location'}">阅读全文&nbsp;>&nbsp;</a>-->
                <!--</div>-->
              <!--</div>-->
            <!--</div>-->
          <!--</div>-->
          <!--<div class="sixteen wide column">-->
            <!--<div class="ui comments">-->
              <!--<div class="comment">-->
                <!--<a class="avatar">-->
                  <!--<img src="/static/img/Box-List-4-img-1.jpg">-->
                <!--</a>-->
                <!--<div class="content">-->
                  <!--<a class="author" v-link="{ path: '/Box-List-4#location'}">湖南省证券业协会一行来吉梵参观交流</a>-->
                  <!--<div class="text">7月2日湖南省证券业协会会长丁小平及秘书长刘丹岳一行来吉梵金融参观交流。吉梵金融总裁敖宇及副总裁甘懋旭热情的接待了来访客人，并详细的介绍了公司的现状和发展愿景。</div>-->
                  <!--<a class="author little" v-link="{ path: '/Box-List-4#location'}">阅读全文&nbsp;>&nbsp;</a>-->
                <!--</div>-->
              <!--</div>-->
            <!--</div>-->
          <!--</div>-->
          <div class="sixteen wide column bottom">
            <h2 class="ui center aligned icon header" @click="News_Share">查看更多</h2>
          </div>
        </div>


      </div>
    </div>
  </div>
</template>
<script>
  export default{
    replace: false,
    data () {
      return {
      }
    },
    methods: {
      News_Share: function () {
        window.location.href = 'News-Share'
      }
    }
  }
</script>
<style scoped>
  .ui.container{width: 1380px;}
  .two.wide.column{margin: 0px;padding:0px;}
  .twelve.wide.column.main-content{width: 1380px!important;overflow: hidden;padding-left: 0px;text-align: center;padding-right:0px;background-color: rgb(245,245,245);}


  /*吉梵新闻*/
  .list-box{background-image: url("/static/img/News-Share-img.png");background-repeat:no-repeat;}
  /*top修饰*/
  .list-box>.ui.segment{width: 368px;height:92px;line-height: 92px;vertical-align: middle;background-color: rgb(209,10,27);
    box-shadow: 0px 0px transparent;border: 0px;border-radius: 0px;}
  .list-box>.ui.segment>p{line-height: 60px;vertical-align: middle;color: white;}
  .ui.grid.jf-news{padding-left:134px;padding-right: 134px;}
  .jf-news{padding-left: 0px;}
  .jf-news>.sixteen.wide.column{margin-right: 0px;margin-left:0px;padding:0px;}
  .jf-news-nav{border: 0px; border-radius: 0px;box-shadow: 0px 0px 0px;margin-right: 0px;}
  .jf-news-nav>.step{background-color:#666666;border-radius: 0px!important;}
  .jf-news-nav>.step.first{width: 247px; height:119px;text-align: right!important;justify-content: flex-end;}
  .jf-news-nav>.step.first:after{background-color: #666666;}
  .step.first>.content{margin-top: 20px;}
  /*吉梵新闻-导航标题*/
  /*.title>.header{padding-left: 20px;}*/
  .title>.header>h1,.title>.header>h2{margin:0px!important;padding:0px!important;color:white;}
  .title>.header>h1{font-size: 30px;}
  .title>.header>h2{font-size: 18px;}
  .title>.header>hr{width:30px;border: 2px solid #d10a1b;float:right;}
  .title>.header.little>h1{font-size: 25px;}
  .title>.header.little>h2{font-size: 12px;}
  .jf-news-nav>.active.step{background-color: #d10a1b;width:173px;text-align: center!important;}
  .jf-news-nav>.active.step:after{background-color: #d10a1b;}
  /*未激活状态*/
  .jf-news-nav>.step.stay{background:rgba(120,120,120,0.6);border: 0px;text-align: center!important;width:173px;margin: 0px 1px;}
  .jf-news-nav>.step.stay.first{background:rgba(209,10,27,0.5)!important;justify-content: center;padding-top: 0px;}
  .jf-news-nav>.step.stay:after{display: none;}
  .jf-news-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(209,10,27);position:absolute;left:100px;top:-5px;z-index:1;}
  /*吉梵新闻-新闻列表*/
  .jf-news-list>.sixteen.wide.column{padding-left: 134px;padding-right:134px;margin-top: 30px;}
  .ui.comments{max-width:100%!important;text-align: left;border-bottom: 1px solid #e2dddd;height:150px;overflow: hidden;}
  .comment>.avatar>img{width: 120px!important;height:120px!important;}
  .ui.comments>.comment>.content {margin-left: 150px;padding-top: 10px;}
  .ui.comments>.comment>.content>.author {font-size: 18px;font-weight: bold;}
  .ui.comments>.comment>.content>a {text-decoration: none;color: #323232;}
  .ui.comments>.comment>.content>a:hover {text-decoration: none;color: #323232;}
  .ui.comments>.comment>.content>.author.little{font-size: 14px;font-weight: bold;color: #d10a1b;margin-left: 0px;}
  .ui.comments>.comment>.content>.text {font-size: 14px;padding-top:38px;}
  .sixteen.wide.column.bottom{text-align: center;}
  .ui.center.aligned.icon.header{width:190px;height:50px; border: 1px solid #d10a1b;line-height: 50px;vertical-align: middle;
    font-size: 18px;color: #d10a1b;}
  /*位置行*/
  .location{width:100%;text-align:left;background-color:rgb(230,230,230);height:40px;line-height:40px;vertical-align:middle;padding-left:120px;}
  .ui.container>.twelve.wide.column.main-content{margin-top: 0px;}
  .location-Tri{width:0;height:0;border-left:20px solid transparent;border-right:20px solid transparent;
    border-top:20px solid rgb(230,230,230);position:relative;left: 1005px;top:0px;z-index:1;}

</style>
