<template>
  <div class="main">
    <div class="container">
    <div class="nav">
      <div class="logo">
        <img src="@/assets/logo.png">
      </div>
      <div class="item-list">
        <ul>
          <li>
            <router-link to='/'>首页</router-link>
            </li>
          <li><router-link to='/product'>产品</router-link></li>
          <li> <router-link to='/'>新闻</router-link></li>
          <li> <router-link to='/'>关于我们</router-link></li>
          <li><button class="ask-use">申请使用</button></li>
        </ul>
      </div>
    </div>
    </div>
    
    <div class="content">
      <div class="carousel">
        <p>任何一个功能都是精心打磨</p>
      </div>
      
    </div>
    <!-- 产品介绍 -->
    <div class="product-info">
      <div class="product-info-text">
        <p class="info-title">产品功能</p>
        <p class="info-detail">六大核心功能，全面协助律师办案</p>
      </div>
      <div class="info-cell">
        <div class="cell">
          <div>
            <img src="/static/images/intro-1.png" alt="">
            <div>
              <p>诉讼引导系统</p>
              <p>功能介绍</p>
            </div>
          </div>
        </div>
        <div class="cell">
          <div>
            <img src="/static/images/intro-1.png" alt="">
            <div>
              <p>策略分析系统</p>
              <p>功能介绍</p>
            </div>
          </div>
        </div>
        <div class="cell">
          <div>
            <img src="/static/images/intro-3.png" alt="">
            <div>
              <p>协作办案系统</p>
              <p>功能介绍</p>
            </div>
          </div>
        </div>
        <div class="cell">
          <div>
            <img src="/static/images/intro-4.png" alt="">
            <div>
              <p>知识管理系统</p>
              <p>功能介绍</p>
            </div>
          </div>
        </div>
        <div class="cell">
          <div>
            <img src="/static/images/intro-5.png" alt="">
            <div>
              <p>文书撰写系统</p>
              <p>功能介绍</p>
            </div>
          </div>
        </div>
        <div class="cell">
          <div>
            <img src="/static/images/intro-6.png" alt="">
            <div>
              <p>档案管理系统</p>
              <p>功能介绍</p>
            </div>
          </div>
        </div>
      </div>
      <p>我们的功能不止这些</p>
      <button class="get-more">了解更多</button>
    </div>

    <!-- 优势介绍 -->
    <div class="strength">
       <p class="info-title">我们的优势</p>
       <div class="info-cell">
          <div class="info-child">
          <div>
          <div class="img-container"><img src="/static/images/strength-1" alt=""></div>
          <p class="append-info">面向办案的全方位解决方案</p>
          </div>
        </div>
        <div class="info-child">
         <div>
      <img src="" alt="">
      <p class="append-info">全凭平台支持(同时支持手机/电脑)</p>
    </div>
  </div>
  <div class="info-child">
    <div>
      <img src="" alt="">
      <p class="append-info">专业全面的知识内容</p>
    </div>
  </div>
  <div class="info-child">
    <div>
      <img src="" alt="">
      <p class="append-info">强大的的人工智能技术积累和开发能力</p>
    </div>
  </div>
  <div class="info-child">
    <div>
      <img src="" alt="">
      <p class="append-info">两周一次的功能升级和知识升级</p>
    </div>
  </div>
  <div class="info-child">
    <div>
      <img src="" alt="">
      <p class="append-info">专业全面的知识内容</p>
    </div>
  </div>
</div>
    </div>
    <div class="characteristic">
       <p class="info-title">安全稳定</p>
       <p class="info-detail">安全稳定是律呗软件核心优势之一。我们采用目前最好的加密技术，对所有数据（文字、图片、语音、视频）都进行了128位不可逆加密，存储过程采取软硬结合加密、立体式防窃取、可追踪、可还原、自动备份、快速恢复等先进技术策略。系统通过MAC地址对每个帐号进行校验，每次操作过程系统始终都安全稳定。</p>
       <img src="static/images/characristic.png" alt="" class="info-detail-img">
    </div>
    <div>
       <p class="info-title">服务支持</p>
    
      <div class="info-cell">
     
      <div class="service-cell">
        <img src="" alt="">
        <p>在线客服</p>
        <p></p>
      </div>
      <div class="service-cell">
        <img src="" alt="">
        <p>视屏教程</p>
        <p></p>
      </div>
      <div class="service-cell">
        <img src="" alt="">
        <p>技术支持</p>
        <p></p>
      </div>
      <div class="service-cell">
        <img src="" alt="">
        <p>行业交流群</p>
        <p></p>
      </div>
    </div>
    </div>
    <div class="customer">
      <p class="info-title">成功客户</p>
    <div class="info-cell">
      <div class="partner"><img src="" alt="" class="partner-detail">1</div>
      <div class="partner"><img src="" alt="" class="partner-detail">2</div>
      <div class="partner"><img src="" alt="" class="partner-detail">3</div>
      <div class="partner"><img src="" alt="" class="partner-detail">4</div>
    </div>
    </div>
    <div class="try">
      <p class="left">FREE TRIAL | 免费试用</p>
      <p class="right">找不到合适的产品?小律可以帮您<button>点我呦</button></p>
    </div>
    <div class="footer">

    </div>
  </div>
  
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {};
  }
};
</script>


<style scoped>
.container {
  width: 100%;
}
.content {
  margin-top: 100px;
}
.nav {
  width: 100%;
  position: fixed;
  top: 0px;
  background-color: burlywood;
  z-index: 10;
}
.logo img {
  position: relative;
  left: 100%;
  top: 10px;
}
.item-list {
  position: relative;
  left: 35%;
}
.nav .item-list ul {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;

  align-content: center;
}
.nav .item-list ul li {
  list-style: none;
  display: inline;
  align-content: space-between;
  padding: 10px;
}
.ask-use {
  width: 137px;
  height: 44px;
  background: rgba(86, 154, 249, 1);
  border-radius: 3px;
  position: relative;
  top: -15%;
  /* box-shadow:2px 6px 3px rgba(118,174,251,1); */
}
.logo,
.item-list {
  display: inline-block;
  margin-left: 20px;
}
.item-list {
}
.logo img {
  width: 40px;
  height: 40px;
}

.info-cell {
  display: flex;
  flex-wrap: wrap;
  align-content: space-around;
  text-align: center;
  justify-content: center;
  padding-top: 5px;
}
.product-info {
  text-align: center;
}
.info-title {
  font-size: 30px;
  text-align: center;
}
.cell {
  width: 450px;
  margin: 20px;
}
.info-child {
  width: 300px;
  height: 100px;
}
.info-child > div {
  height: 100px;
  width: 200px;
  margin: 0px;
}
.info-child .img-container {
  height: 90px;
}
.info-child div img {
  width: 80px;
  height: 80px;
}
@media (max-width: 1020px) {
  .cell {
    width: 200px;
  }
}
.cell div {
  display: inline-block;
}
.cell img {
  width: 30px;
  height: 30px;
  display: inline;
  position: relative;
  top: -20px;
}

.get-more {
  width: 231px;
  height: 56px;
  background: rgba(86, 154, 249, 1);
  border-radius: 28px;
  font-size: 20px;
  color: #fff;
}

.service-cell {
  width: 200px;
  background-color: bisque;
  margin-left: 30px;
}
.partner {
  width: 200px;
  height: 100px;
  background-color: aquamarine;
  margin: 20px;
}
.try {
  display: flex;
  background-color: blue;
  justify-content: center;
  color: #fff;
  align-content: space-between;
}
.try .left {
  padding-right: 100px;
}
.try .right button {
  background: rgba(0, 118, 248, 1);
  border-radius: 3px;
  box-shadow: 2px 6px 3px rgba(118, 174, 251, 1);
  font-size: 20px;
  font-family: MicrosoftYaHei;
  color: rgba(255, 255, 255, 1);
  line-height: 0px;
}
</style>
