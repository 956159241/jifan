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
                <h2 class="title">吉梵交创量化对冲1号证券投资基金火热预约中</h2>
                <span class="artical-date">2015-08-19</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph">
                <h4>【吉梵交创量化对冲1号证券投资基金】</h4>
                <p>带您烫平震荡，告别杀跌的无奈，斩获稳定高额的收益!</p>
              </div>
              <div class="paragraph">
                <h4>【吉梵交创量化对冲1号证券投资基金】</h4>
                <p>配对交易无风险套利、规避了系统性风险、市场上涨下跌均可获利。</p><p>100万起投。</p>
              </div>
              <div class="paragraph">
                <p>【1】本轮大震荡行情，公司所选投顾的所有产品均无清仓风险，量化对冲系列单日涨幅达3%，业内首屈一指，超越多数知名对冲基金。</p>
              </div>
              <div class="paragraph">
                <p>【2】采用套利策略，把握确定性机会，赚取绝对收益，历史最大回撤仅1%，真正实现“低风险、高收益”。</p>
              </div>
              <div class="paragraph">
                <p>【3】基金经理、投研团队均来自大型私募机构，“前所罕见—私募量化顶级配置”。从业10年以上，资金投向标准金融市场，ETF和分级基金以及期现套利，通过海量数据分析，赚取绝对收益。</p>
              </div>
              <div class="paragraph">
                <p>【4】基金管理人—吉梵资产，以严谨、专业的投资理念，致力于成为资本市场上有重要影响力、受人尊敬的资产管理公司。</p>
              </div>
              <div class="paragraph">
                <p>【5】战略合作伙伴：交大创投（中国创富联盟），挖掘财富管理内在价值，成为高智人群的首选投资理财工具。</p>
              </div>
              <div class="paragraph">
                <p><img src="/static/img/2015-list-img-2.png"></p>
                <p>详情@alone602805428</p>
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
  .artical>.paragraph>p>img{width: 150px;height:100px;}
  .artical>.paragraph>h4{text-indent:2em;}
  .artical>.paragraph-pic{padding: 0px 155px;margin-top: 30px;}
  .artical>.paragraph-pic>.pic-describe{text-align: left;font-size: 18px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}
  .artical>.paragraph-pic>img{width: 100%;padding-top: 15px;padding-bottom:8px;}
  .artical>.paragraph-pic>.pic-number{font-size: 18px;font-family: "Microsoft YaHei";color: rgb(100, 100, 100);}


</style>
