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


              <div class="paragraph">
                <p>7月2日湖南省证券业协会会长丁小平及秘书长刘丹岳一行来吉梵金融参观交流。吉梵金融总裁敖宇及副总裁甘懋旭热情的接待了来访客人，并详细的介绍了公司的现状和发展愿景。</p>
              </div>
              <div class="paragraph">
                <p>随着金融体制改革的不断深化,这也对金融岗位培训师资队伍提出了更高的要求。目前吉梵金融正在搭建自己的金融培训团队，如何逐步强化和完善金融岗位培训师资队伍建设的各项制度和措施,真正建立一支在理论和实践上过得硬的师资队伍,以适应金融事业发展的需要,就此大家都进行了一些探讨。</p>
              </div>
              <div class="paragraph">
                <p>吉梵金融培训属于吉梵金融服务领域，组织并承办财经沙龙及项目路演等各类活动，同时链接互联网资源，搭建金融市场的交流学习与商务合作平台，通过线上为机构输出财经直播、研究资讯、品牌推广等服务。</p>
              </div>


              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/Box-List-4-img-1.jpg">
                <div class="pic-number">（图一）</div>
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
