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
                <span class="return-link"  v-link="{ path: '/News-Share-2015'}">返回上一层</span>
                <h2 class="title">热烈祝贺吉梵资产与易睦科技签订投资协议</h2>
                <span class="artical-date">2015-05-27</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/2015-list-4-img-1.jpg">
                <div class="pic-number">（图一）</div>
              </div>

              <div class="paragraph">
                <p>2015年5月27日，上海吉梵资产管理有限公司与易睦网络科技（上海）有限公司投资签约仪式在易睦网络会议室举行。上海吉梵资产管理有限公司董事长敖宇与易睦网络科技（上海）有限公司董事长乔月猛在投资协议上签字并互换协议文本。</p>
              </div>
              <div class="paragraph">
                <p>上海吉梵资产管理有限公司董事长敖宇表示，吉梵资产作为一个综合性金融平台公司，致力于为个人和企业提供全方位的财富管理服务，致力于为中小企业融资提供解决方案，用金融的力量推动社会进步。此次与易睦网络的合作，吉梵资产将在多方面助推企业发展，同时在业务方面开展多层次的合作，互惠互利，实现共赢。</p>
              </div>
              <div class="paragraph">
                <p>易睦网络科技（上海）有限公司董事长乔月猛表示，易睦网络此前已获多轮国际顶级投资，表明公司具有巨大的投资前景。此次与吉梵资产的合作，必将对公司的发展起到巨大促进作用，公司今后将加强与吉梵资产的联系，为吉梵资产打造金融合伙人平台提供支持。imo核心使命是，为中国企业提供高效、稳健的网络化通讯、网络化办公和网络化电子商务，实现企业微成本，随时随地掌握企业运营的应用和服务，打造超大规模办公型即时通讯互联网平台和企业/机构的高效率网上办公平台。</p>
              </div>
              <div class="paragraph">
                <p>吉梵资产高管、IT技术团队与易睦网络的有关人员参加了本次签约仪式。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/2015-list-4-img-2.jpg">
                <div class="pic-number">（图二）</div>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/2015-list-4-img-3.jpg">
                <div class="pic-number">（图三）</div>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/2015-list-4-img-4.jpg">
                <div class="pic-number">（图四）</div>
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
  .artical>.paragraph>p>img{width: 150px;height:100px;}
  .artical>.paragraph>p>.bold{font-size: 18px;font-weight: bold;}
  .artical>.paragraph>h4{text-indent:2em;}
  .artical>.paragraph-pic{padding: 0px 155px;margin-top: 30px;}
  .artical>.paragraph-pic>.pic-describe{text-align: left;font-size: 18px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}
  .artical>.paragraph-pic>img{width: 100%;padding-top: 15px;padding-bottom:8px;}
  .artical>.paragraph-pic>.pic-number{font-size: 18px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}


</style>
