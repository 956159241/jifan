<template>
  <div class="home-message">
    <div class="ui container">
      <div class="twelve wide column main-content">



        <!--新闻资讯-->
        <div class="list-box">
          <div class="ui segment top" id="location">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              <span v-link="{ path: '/home'}" class="home-link">首页</span>&nbsp;>&nbsp;新闻资讯&nbsp;>&nbsp;吉梵动态</p>
          </div>
        </div>
        <div class="ui grid jf-news">
          <div class="sixteen wide column">
            <div class="artical">
              <div class="header">
                <span class="return-link"  v-link="{ path: '/News-Dynamic'}">返回上一层</span>
                <h2 class="title">首席体育官思享会:《体育、营销与体育营销》</h2>
                <span class="artical-date">2016-05-22</span><span class="artical-author">作者：吉梵金融</span>
              </div>
              <div class="paragraph">
                <p>	体育市场是一个特殊的行业市场，是体育有形产品和体育服务产品的交换市场。体育市场营销成功与否，涉及多方面的因素。其中根据体育市场营销具体特点，制定和实施适宜的营销战略至关重要。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/News-Share-List-4-img-1.jpg">
                <div class="pic-number">（图一）</div>
              </div>
              <div class="paragraph">
                <p>5月22日下午首席体育官思享会在吉梵金融空间举办了《体育、营销与体育营销》活动。</p>
              </div>
              <div class="paragraph">
                <p>活动由首席体育官思享会顾伟先生主持，上海体育学院经济管理学院、复旦大学管理学院工商管理、芬兰Jyvaskyla大学体育管理与规划、上海市侨联委员、青海省“昆仑学者”、山西省“领军人才”刘兵教授；遥顺青少年高尔夫学院总裁宓遥先生；智美体育集团执行总裁沈伟先生；动吧斯博体育文化（北京）有限公司创始人白强先生；吉梵金融副总裁甘懋旭先生等行业专家共聚一堂，开启一场充满智慧的思想交流盛宴。</p>
              </div>
              <div class="paragraph-pic">
                <div class="pic-describe"></div>
                <img src="/static/img/News-Share-List-4-img-2.jpg">
                <div class="pic-number">（图二）</div>
              </div>
              <div class="paragraph">
                <p>	当今，在体育产业的价值创造过程中，体育营销平台发挥着越来越重要的作用。而体育越来越与人们的生活息息相关，体育营销也越来越广泛地被企业所接受。</p>
              </div>
              <div class="paragraph">
                <p>	体育是什么？体育的表象是一种身体运动或精神享受；本质是一种教育或文化；核心点是培养一种社会责任；品质是一种生活的态度。很多人对于体育理解的不够，体育的产品质量不高，它的转化能力不够，所以需要创造认识、构建标准、培养人才。</p>
              </div>
              <div class="paragraph">
                <p>	而体育要营销什么？是运动本身，一个供给侧结构的矛盾。体育所服务的对象就是体育和人。它的产业边界是一个需要思考的整合模式。而当前体育营销的思考需要惑有所思、恒有所得、静有所听、清有所见。</p>
              </div>
              <div class="paragraph">
                <p>	现场精彩不断，与会人员纷纷表示受益匪浅。活动在热烈的氛围中，圆满落幕。</p>
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
