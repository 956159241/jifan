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
                <h2 class="title">吉梵学习坊——家族财富传承方案的设计与实施（保险篇）</h2>
                <span class="artical-date">2016-05-24</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph">
                <p>	家族财富传承面临「大考」——在家族财富传承方案中应充分考虑各类资产，境内、 境外，不动产、保险、企业股权、 现金、证券投资，由于性质特点不同，需要不同的筹划安排。</p>
              </div>
              <div class="paragraph">
                <p> 规划工具的使用，应当因人、 因时、因地而异，订制成分较强。从时间上考虑，鉴于高昂的遗产税，以及全球对离岸账户的监管日趋收紧， 超高净值个人和家庭应当及时进行规划和布局，降低未来可能遭遇的潜在的重大财产损失。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/News-Share-List-3-img-1.jpg">
                <div class="pic-number">（图一）</div>
              </div>
              <div class="paragraph">
                <h4>1、家族财富传承方案的分析与探讨</h4>
                <p>财富传承规划与目的</p>
                <p>财富传承的案例介绍</p>
                <p>财富传承中保险产品的分类（储蓄类产品与重疾类产品）配置与功能</p>
                <p>储蓄类产品与重疾类产品在传承方案中的功能</p>
                <p>家族财富管理服务的基本流程</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/News-Share-List-3-img-2.jpg">
                <div class="pic-number">（图二）</div>
              </div>
              <div class="paragraph">
                <p>按照美国标准普尔的建议，当财富积聚到一定程度的时候，就需要对家庭财富做合理的规划和安排，科学建立家庭财富四大账户！     </p>
              </div>
              <div class="paragraph">
                <h4>2、家族财富传承方案的设计与实施（保险篇）培训时间</h4>
                <p>培训时间：2016/05/26(周四) 18:30 至 20:30</p>
                <p> 培训地点：上海黄浦区马当路388号新天地SOHO复兴广场29楼</p>
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
