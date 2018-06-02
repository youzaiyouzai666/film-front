<template>
    <section class="nav">
          <div class="center-wrap">
              <a href="/" class="logo" title="回到首页"></a>
              <div class="cityWrap">北京</div>
              <a href="/" class="nav-wrap active" target="_top">首页</a>
              <a href="/" class="nav-wrap" target="_top">影片</a>
              <a href="/" class="nav-wrap" target="_top">影院</a>
          </div>
         

    </section>
</template>
<style scoped >
    .nav {
        width: 100%;
        border: 1px solid;
    }
    .logo {
        display: inline-block;
        width: 150px;
        height: 72px;
        background: url(~assets/img/logo.png) left center no-repeat;
        vertical-align:-30px;
    }
    .cityWrap{
        display: inline-block;
        font-size: 18px;
        color: #333;
        vertical-align: middle;
        padding: 0 30px 0 15px;
    }
    .nav-wrap{
        display: inline-block;
        vertical-align: middle;
        font-size: 18px;
        color: #333;
        padding: 0 15px;
        line-height: 42px;
    }
    .nav-wrap.active{
        border-bottom: 3px #eb002a solid;
        color: #eb002a;
        vertical-align: -3px;
        
    }
</style>

