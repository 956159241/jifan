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
                <span class="artical-date">2016-07-16</span><span class="artical-author">作者：吉梵金融</span>
              </div>

              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-3-img-1.png">
                <div class="pic-number">（图一）</div>
              </div>
              <div class="paragraph">
                <p>7月14日至16日由阳明教育研究院主办的《致良知是一种伟大的力量》2016年第一季学习会在吉梵金融举行，现场30多位参加本次学习会。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-3-img-2.png">
                <div class="pic-number">（图二）</div>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-3-img-3.png">
                <div class="pic-number">（图三）</div>
              </div>
              <div class="paragraph">
                <p>王阳明作为中国历史上罕见的“立德、立功、立言”三不朽的伟人，其思想500多年以来，流传绵绵不绝。阳明先生提出的“心即理、知行合一、事上磨练以及致良知”等思想，对于中国、日本、朝鲜以及东南亚部分国家的社会和文化的发展都产生过巨大的作用。</p>
              </div>
              <div class="paragraph">
                <p>很多时候，人们习惯将这种心境上、形而上的理论归结为“情怀”，我们的确厌恶贩卖情怀，但不论是产业发展还是企业管理，都离不开情怀，我们必须对于某件事情怀有敬畏并且坚持相信。</p>
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
