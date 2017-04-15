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
                <h2 class="title">美联储不加息人民币汇率调整或已到位</h2>
                <span class="artical-date">2016-07-29</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph">
                <p>最新公布的美联储7月议息结果偏鸽派，美联储决定维持联邦现行利率不变。同日，国际货币基金组织（ＩＭＦ）发布报告称，人民币币值大致符合中国的经济基本面。结合国际国内的经济情况来看，记者认为，人民币汇率本轮调整已经到位。从中期看，人民币汇率将在现有的基础上小幅波动，大致维持稳定。</p>
              </div>
              <div class="paragraph">
                <p>美联储此次维持现行利率不变的决定，基本符合市场预期。近期美国经济出现较强的复苏迹象，但仍存隐忧，非农就业数据并不稳定，国际油价回落将引导物价回落，美国经济中期趋势仍不明朗。因此，此次美联储维持现状，等待经济复苏的趋势进一步明朗再出手，应该是一个理性的选择。</p>
              </div>
              <div class="paragraph">
                <p>从国际环境来看，美联储按兵不动的理由更充分。环顾四周，美国的盟友们基本上都还在经济疲软的泥潭里苦苦挣扎。英国脱欧负面影响远远大于正面影响，给英国经济复苏带来很大的不确定性。欧盟饱受恐怖袭击的惊扰，恐怖袭击不仅对欧盟经济带来负面影响，而且还对社会、政治等方面带来冲击。日本经济受老龄化和高汇率双重影响，不得不再度加码经济刺激。在这样的背景下，如果美联储贸然加息，将会使美国和其盟友们在经济政策上背道而驰，这种局面所带来的潜在政治影响，也难以是正面的。</p>
              </div>
              <div class="paragraph">
                <p>无需讳言，美联储此次不加息，将有助于新兴经济体减少汇率波动冲击，也有助于人民币汇率的稳定。但这仅是其中一个因素而已。人民币汇率经过近期一轮调整之后，目前已经回到合理区间，阶段性调整已经结束。</p>
              </div>
              <div class="paragraph">
                <p>6月中旬，IMF第一副总裁利普顿曾称，人民币汇率市场化程度提高，人民币汇率的估值基本合理。记者认为，在中国进出口贸易疲软的时候，人民币适度贬值有助于提高中国产品的国际竞争力。但与此同时，上半年的经济数据表明，中国经济增长达到预期，消费继续保持了两位数的增长，服务业和高端制造业增长幅度好于平均水平，这表明中国经济结构正在向好的方向转变。因此，就中国国内经济而言，人民币汇率不存在继续调整的空间。</p>
              </div>
              <div class="paragraph">
                <p>来源：证券时报  </p>
              </div>
              <div class="paragraph">
                <p>记者：吴智钢</p>
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
