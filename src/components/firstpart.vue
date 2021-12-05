<template>
  <div class="father">
    <div class="first">
      <div class="dao">
        <a
          href="https://jobs.bytedance.com/experienced/"
          target="blank"
          class="one"
        >
          <div class="small">ByteDance</div>
          <div class="main">
            <div class="big">字节跳动</div>
            <div class="link">招聘</div>
          </div></a
        >
      </div>
      <div class="hang">
        <a href="https://jobs.bytedance.com/experienced/" class="introduce"
          >主页</a
        >
        <a href="https://jobs.bytedance.com/experienced/position" class="job"
          >职位</a
        >
        <a href="https://jobs.bytedance.com/experienced/product" class="produce"
          >产品与服务</a
        >
        <a
          href="https://jobs.bytedance.com/campus"
          target="blank"
          class="campus"
          >校园招聘</a
        >
        <a class="none">|</a>
        <a href="https://jobs.bytedance.com/experienced/login" class="login"
          >登录</a
        >
      </div>
    </div>
    <div id="lan">
      <button class="btn">↓</button>
    </div>
  </div>
</template>
<style type="text/css">
.father {
  background-image: url(../img/first.jpeg);
  background-size: cover;
  width: 100%;
  height: 620px;
}
.first {
  width: 100%;
  height: 550px;
  display: flex;
  justify-content: space-between;
}
.dao {
  color: white;
  display: flex;
  width: 30%;
  margin-left: 100px;
  margin-top: 10px;
}
.one {
  color: white;
  text-decoration: none;
  width: 197px;
  height: 35px;
}
.link {
  background-color: rgb(240, 244, 255);
  color: #000;

  font-size: 0.6em;
  height: 21px;
  line-height: 21px;
  width: 52px;
  text-align: center;
  border-radius: 8%;
  margin-top: 8px;
  margin-left: 10px;
}
.main {
  font-size: 1.5em;
  display: flex;
  overflow: hidden;
}
.small {
  font-size: 0.5em;
}
.hang {
  display: flex;
  justify-content: space-around;
  width: 40%;
  height: 35px;
  margin-top: 35px;
  overflow: hidden;
  margin-right: 50px;
}
a {
  text-decoration: none;
  color: aliceblue;
}
.introduce,
.job,
.produce,
.campus,
.login {
  font-size: 14px;
  font-weight: 600;
}
.none {
  font-size: 12px;
  font-weight: 400;
}
#lan {
  height: 32px;
  width: 100%;
  margin-left: 620px;
}
.btn {
  border-radius: 50%;
  width: 32px;
  height: 32px;
  background: rgba(0, 0, 0, 0);
  border: 1px solid #dbdbdb;
  color: white;
  font-size: 25px;
}
</style>
