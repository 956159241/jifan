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
                <h2 class="title">人民币中间价三连升 美加息预期或增维稳压力</h2>
                <span class="artical-date">2016-07-28</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph">
                <p>7月28日，人民币兑美元中间价上调74点，报6.6597元。人民币中间价已连续三天上调，分析认为，经过5、6月份的大幅波动后，人民币贬值压力已阶段性释放，但考虑到接下来的几个关键时点，预计监管层维稳力量仍强，而美联储的鹰派声明或增加央行维稳压力。</p>
              </div>
              <div class="paragraph">
                <p>人民币兑美元中间价在25日大幅下调后，26日开始回升，27日上调107点至6.6671。今日，中间价上调74点后，在岸人民币开盘大涨近百点，至三周高位。</p>
              </div>
              <div class="paragraph">
                <p>据香港《经济日报》报道，有交易员称中资大行近期维稳已成常态，人民币交易中枢逐渐抬高，但升值空间仍有限。</p>
              </div>
              <div class="paragraph">
                <p>有分析指出，人民币经过5、6月份的大幅波动后，贬值压力已阶段性释放，但接下来人民币将迎来几个关键时点，包括9月份的G20峰会和10月份人民币正式纳入SDR，预计监管层维稳力量仍强。</p>
              </div>
              <div class="paragraph">
                <p>此前，央行行长周小川在G20财长和央行行长会议上表示，经历一段适应期后，市场参与者对人民币汇率形成机制的理解已更深入，目前人民币汇率兑一篮子货币保持基本稳定。</p>
              </div>
              <div class="paragraph">
                <p>国泰君安分析称，6.7作为人民币短期底线，有较强支撑，在G20峰会到来之前可能不会打破。</p>
              </div>
              <div class="paragraph">
                <p>值得注意的是，美联储7月议息会议维持利率不变，但会议纪提到，经济前景的短期风险减弱，市场观点认为这是在为9月的加息做铺垫。有交易员认为，美联储明显偏鹰的声明或增加中国央行维稳压力。</p>
              </div>
              <div class="paragraph">
                <p>来源：和讯网</p>
              </div>
              <div class="paragraph">
                <p>记者：庞凌子</p>
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
