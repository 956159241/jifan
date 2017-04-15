<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">



        <!--新闻资讯-->
        <div class="list-box" id="location">
          <div class="ui segment top">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              <span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;新闻资讯&nbsp;>&nbsp;资讯分享</p>
          </div>
        </div>
        <div class="ui grid jf-news">
          <div class="sixteen wide column">
            <div class="artical">
              <div class="header">
                <span class="return-link"  v-link="{ path: '/News-Share'}">返回上一层</span>
                <h2 class="title">银行理财新规吓退A股 流动性名义影响或过万亿</h2>
                <span class="artical-date">2016-07-28</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph">
                <p>银行理财新规对A股市场的冲击不容小觑，多位市场分析师人士对和讯网表示，理财新规里高净值、机构客户之外的客户只能投债基、货基，从权益来说，主要增量资金限制比较明显，对股市流动性的名义影响估计过万亿。</p>
              </div>
              <div class="paragraph">
                <p>昨日，消息人士透露，最新版的《商业银行理财业务监督管理办法（征求意见稿）》已下发至各家银行，相较于2014年12月下发的《商业银行理财业务监督管理办法（意见征求稿）》，有不小的调整。其中强调不得投资股票，禁止发行分级产品。</p>
              </div>
              <div class="paragraph">
                <p>对此，首创证券首席策略分析师邵帅对和讯网表示，银行理财产品的钱，间接进入股市是有的，但由于这部分资金量不太透明，准确数额可能不好说，但情绪和资金面的影响肯定会有。</p>
              </div>
              <div class="paragraph">
                <p>华泰证券(601688,股吧)首席策略分析师戴康虽没有直接点出对资金面影响的具体数额，但他对和讯网称，新规对于理财资金投资权益和非标资产的限制加强，会影响银行理财资金口能给A股带来的增量资金；同时，新规下资产端的投资范围收缩会导致银行理财收益率进一步下行。</p>
              </div>
              <div class="paragraph">
                <p>而这两点对应着：一是存量博弈格局难变，且不断出现的资本市场新规会一直抑制着市场的风险偏好；二是资产荒格局不变且会进一步加剧，大量流动性还是在找出路，资产荒对A股的估值水平又有一定支撑。</p>
              </div>
              <div class="paragraph">
                <p>而华泰金融则明确表示，23万亿银行理财的20%将禁止投权益类和非标类，那么意味着4.6万亿的理财余额受影响，而按照其草根调研，由于部分中小型银行在权益比重上比较激进，对权益类占比的判断比市场高，大概在11%左右，那么权益资金直接由于门槛影响，大概在5000亿，而非标类资产，大概占比在17%，大概影响资金在7800亿左右。主要资金限制反应在增量上，从权益来说，这部分限制还是比较明显的。</p>
              </div>
              <div class="paragraph">
                <p>交银国际研究部负责人洪灏认为，理财新规里高净值、机构客户之外的客户只能投债基、货基，对股市流动性的名义影响估计过万亿。资金或进入债市，但在资产泡沫明显，经济放缓之时，因系统风险上升，所谓的无风险利率难下降。</p>
              </div>
              <div class="paragraph">
                <p>对于A股投资者应该采取怎样的策略，华泰证券称，存量博弈和低风险偏好限制市场的上行空间，但资产荒对A股的估值水平有一定支撑，推荐消费股食品饮料医药家电+供给侧改革煤炭+高股息现金流电力交运。</p>
              </div>
              <div class="paragraph">
                <p>而今日早盘，沪指低开后一路下行，一度下挫超20点，不过之后快速反弹，跌幅收窄。</p>
              </div>
              <div class="paragraph">
                <p>来源：和讯网  </p>
              </div>
              <div class="paragraph">
                <p>记者：许祯</p>
                <br/><br/><br/>
              </div>



              <!--<div class="paragraph-pic">-->
              <!--<div class="pic-describe">上海国际金融中心研究院合影留念</div>-->
              <!--<img src="/static/img/News-Share-List-1-img-3.png">-->
              <!--<div class="pic-number">（图三）</div>-->
              <!--<br/><br/><br/>-->
              <!--</div>-->


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
