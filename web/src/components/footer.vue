<template>
  <div class="index-bottom">
    <div class="ui container">
      <div class="twelve wide column">
        <div class="ui grid">
          <div class="eight wide column left">
            <h2 class="ui header">
              <!--<img src="/static/img/jf-logo.png">-->
              <!--<img src="/static/img/jf-logo.png">-->
              <!--<div class="content">吉梵财富<div class="sub header">jfan.com</div>-->
              <br/>
              <!--<div class="content">吉梵金融<div class="sub header"></div>-->
              <!--</div>-->
            </h2>
          </div>
          <div class="eight wide column right">
            <p>
              <span v-link="{ path: '/JF-Introduce#location'}">关于我们</span>
              <span v-link="{ path: '/Contact-Addr#location'}">联系我们</span>
              <span v-link="{ path: '/Contact-Join#location'}">加入我们</span>
              <span v-link="{ path: '/JF-Introduce'}">合作伙伴</span>
            </p>
            <p>Copyright ©上海吉梵资产 沪ICP备13028619号-1</p>
            <p>上海黄浦区马当路388号SOHO复兴广场A座29楼</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  export default{
    data () {
      return {
        msg: 'footer'
      }
    }
  }
</script>
<style scoped>
  .ui.container{width: 1380px;}
  .index-bottom{height:192px;line-height: 192px;vertical-align: middle;}
  .twelve.wide.column{background-color: rgb(245,245,245);width:1380px!important;}
  .eight.wide.column.left{padding-left: 102px;margin-top: 70px;}
  .left>h2{width:300px;}
  .left>h2>img{height:3.5em;width: auto;}
  .left>.ui.header>.content{font-size: 20px;}
  .sub.header{font-weight: bold!important;color: black!important;letter-spacing: 0.2em;}
  .eight.wide.column.right{text-align: right;}
  .eight.wide.column.right{margin-top: 70px;padding-right:105px;text-align: right;}
  .eight.wide.column.right>p{padding:0px;margin: 0px;color:#646464;font-size: 14px;line-height: 25px;}
  .eight.wide.column.right>p>span{color: #909090;border-right: 1px solid #909090;margin-right: 10px;padding-right:10px;}
  .eight.wide.column.right>p>span:hover{cursor:pointer;}
  .eight.wide.column.right>p>span:last-child{margin-right: 0px;padding-right:0px;}
  .eight.wide.column.right>p>span:last-child{border-right: 0px solid #909090;}

</style>
