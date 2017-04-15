<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">



        <!--新闻资讯-->
        <div class="list-box" id="location">
          <div class="ui segment top">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              <span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;新闻资讯&nbsp;>&nbsp;吉梵动态</p>
          </div>
        </div>
        <div class="ui grid jf-news">
          <div class="sixteen wide column">
            <div class="artical">
              <div class="header">
                <span class="return-link"  v-link="{ path: '/News-Dynamic'}">返回上一层</span>
                <h2 class="title">吉梵金融 | 闽商资本联合会企业家上海行活动纪实</h2>
                <span class="artical-date">2016-07-17</span><span class="artical-author">作者：吉梵金融</span>
              </div>

              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-1-img-1.png">
                <div class="pic-number">（图一）</div>
              </div>
              <div class="paragraph">
                <p>7.17日下午闽商资本联合会企业家一行来到吉梵金融参观，学习，交流，吉梵金融为来自福建的企业家们安排了目前企业家最关心的、高品质的学习交流活动。</p>
              </div>
              <div class="paragraph">
                <p>整个下午的学习交流活动主要分为两个部分，第一部分由东方汇富副总裁项立平分享《企业投融资运作实务》，第二部分由申万宏源总监许弘林分享《股权投资经验》。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-1-img-2.png">
                <div class="pic-number">（图二）</div>
              </div>
              <div class="paragraph">
                <p>东方汇富副总裁项立平先生，有着丰富的项目投资经验，是长白山，桂林旅游等多家上市企业的投资并购顾问，我国现在的企业普遍面临着融资难的问题，对于资本市场的认识度不够，项总从一名专业投资者的角度，站在企业家的立场上，为各位企业家介绍了“如何让自己的企业更值钱”、“如何与专业的投资机构打交道”等企业家关心的问题，并为大家详细介绍了财务投资人的优势与劣势、产业投资人的优势与劣势、战略投资人（财务投资人+产业投资人）的优势与劣势等问题。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-1-img-3.png">
                <div class="pic-number">（图三）</div>
              </div>
              <div class="paragraph">
                <p>申万宏源许弘林博士为大家精彩分享了“股权投资经验”，现在企业的发展与资本市场的结合越来越紧密，能够充分利用资本市场的企业往往可以在激烈的市场竞争中抢占先机，许博士详细给企业家们介绍了多层次的资本市场，分析了新三板，创业板和主板的不同，其中重点讲到了“马太效应” ：任何个体、群体或地区，在某一个方面（如金钱、名誉, 地位等）获得成功和进步，就会产生一种积累优势，就会有更多的机会取得更大的成功和进步。反映赢家通吃.。对于在座的各位企业家触动很大。</p>
              </div>
              <div class="paragraph">
                <p>时间总是太匆匆，一个下午短短三个小时的交流，在座企业家纷纷表示干货很多，但是还不够“解渴”，希望闽商资本联合会能够多跟吉梵金融合作，为企业家带来更多真正切合实际的，符合企业家需求的交流活动，实现企业和吉梵金融的共同发展，共同进步。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-1-img-4.png">
                <div class="pic-number">（图四）</div>
                <br/><br/><br/>
              </div>


            </div>

          </div>
        </div>


      </div>
    </div>
  </div>
</template>

<style scoped>
  .ui.container{width: 1380px;}
  .two.wide.column{margin: 0px;padding:0px;}
  .twelve.wide.column.main-content{width: 1380px!important;overflow: hidden;padding-left: 0px;text-align: center;padding-right:0px;background-color: rgb(245,245,245);}


  /*吉梵新闻*/
  .list-box{background-image: url("/static/img/News-Share-img.png");background-repeat:no-repeat;height:210px;}
  /*top修饰*/
  .list-box>.ui.segment{width: 368px;height:92px;line-height: 92px;vertical-align: middle;background-color: rgb(209,10,27);
    box-shadow: 0px 0px transparent;border: 0px;border-radius: 0px;}
  .list-box>.ui.segment>p{line-height: 60px;vertical-align: middle;color: white;}
  .ui.grid.jf-news{padding-left:134px;padding-right: 134px;margin-top: -118px;}
  .jf-news{padding-left: 0px;}
  .ui.segment.top:after{display: block;position: absolute;pointer-events: none;content: ''; visibility: visible;
    -webkit-transform: rotate(45deg);transform: rotate(45deg);width:30px;height:30px;box-shadow: -1px -1px 0 1px rgba(34,36,38,0);
    background: rgb(209,10,27);z-index: 2;bottom:-15px;left:238px;margin: 0 0 0 -.25em;}
  .jf-news>.sixteen.wide.column{margin-right: 0px;margin-left:0px;padding:60px 80px;background-color: rgb(255,255,255);height: 100%;}
  /*文章内容*/
  .artical>.header{text-align: left;}
  .artical>.header>.return-link{float:right;color: rgb(209,10,27);cursor: pointer;font-size: 16px;}
  .artical>.header>.title{font-size: 24px;font-family: "Microsoft YaHei";color: rgb(50, 50, 50);line-height: 36px;}
  .artical>.header>.artical-date{font-size: 14px;color: rgb(144, 144, 144);line-height: 36px;padding-right: 45px;}
  .artical>.header>.artical-author{font-size: 14px;color: rgb(144, 144, 144);line-height: 36px;}
  .artical>.paragraph{text-align:justify;margin-top:30px;}
  .artical>.paragraph>p{text-indent:2em;font-size: 16px;color: #646464;line-height: 36px;font-family: "Microsoft YaHei";}
  .artical>.paragraph-pic{padding: 0px 155px;margin-top: 30px;}
  .artical>.paragraph-pic>.pic-describe{text-align: left;font-size: 18px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}
  .artical>.paragraph-pic>img{width: 100%;padding-top: 15px;padding-bottom:8px;}
  .artical>.paragraph-pic>.pic-number{font-size: 18px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}


</style>
