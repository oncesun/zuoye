<template>
  <div class="seventh">
    <div class="content1">
      <div class="left">
        <div class="title1">信息助力公益<br />创造社会价值</div>
        <ul>
          <li><div class="work">头条寻人 科技向善</div></li>
          <li>
            <div class="explain1">
              “头条寻人”是一个面向全国的公益寻人项目。基于庞大的用户量，“头条寻人”根据走失人员的走失位置，回溯其有可能出现的地点，精确地将走失信息推送给该位置附近的用户。每一位打开定位和弹窗功能的用户，都有可能参与到寻人的公益活动中，帮助失散家庭团圆。截至
              2020 年 4 月 27 日，已经帮助 13000
              个家庭团圆，最快找到走失者仅用时 60 秒
            </div>
          </li>
          <li><div class="work1">抖音助力文旅扶贫</div></li>
          <li>
            <div class="explain1">
              通过字节跳动在流量倾斜、人才培训、产品扶持和抖音认证的四个方面投入及运营，帮助国家级贫困县的特色文旅资源打造品牌，提升拉动当地文旅品牌影响力并持续带动相关产业的经营发展。截至目前，“山里
              DOU 是好风光”已落地实施河南栾川、山西永和、四川甘孜稻城亚丁等项目
            </div>
          </li>
        </ul>
      </div>
      <div class="right">
        <div class="img">
          <img src="../img/ia_100000043.png" />
        </div>
        <div class="img1">
          <img src="../img/ia_100000044.jpg" />
        </div>
        <div class="img2">
          <img src="../img/ia_100000045.jpg" />
        </div>
      </div>
    </div>
    <div class="content2">
      <div class="title2">员工故事</div>
      <div class="story">
        <a href="#" class="story1">
          <div class="picture">
            <img src="../img/ia_100000046.png" />
          </div>
          <div class="para">从大学老师到算法工程师</div>
          <div class="name">沈池 I AI - Lab 图像算法</div>
          <div class="experience">
            怀着一颗想出来闯荡的心，从学术界跳到了工业界；公司有着丰富的应用场景和海量数据资源，技术落地非常有保证。
          </div>
          <div class="link">
            <a href="#" class="link1">→ </a>
          </div>
        </a>
        <a class="story2">
          <div class="picture">
            <img src="../img/ia_100000047.png" />
          </div>
          <div class="para">在多元兼容的环境里持...</div>
          <div class="name">Gill I 国际化产品经理</div>
          <div class="experience">
            不同文化背景下的沟通是一种挑战，公司鼓励多元兼容，提倡集思广益，让我看到了广大可能性和成长空间。
          </div>
          <div class="link">
            <a href="#" class="link1">→ </a>
          </div>
        </a>
        <a class="story3">
          <div class="picture">
            <img src="../img/ia_100000048.jpg" />
          </div>
          <div class="para">在这里，看见更大的世界</div>
          <div class="name">左儒哲 I 飞书 - 客户端</div>
          <div class="experience">
            比起其他公司，字节跳动可能更浪漫，或者说，有更大的梦想。这里不设边界，只要连接人与信息的事情，我们都会尝试…
          </div>
          <div class="link">
            <a href="#" class="link1">→ </a>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>
<style scoped>
.content1 {
  width: 100%;
  height: 650px;
  display: flex;
}
.content2 {
  width: 100%;
  height: 650px;
}
.title1 {
  font-size: 26px;
  line-height: 36px;
  color: #1f2329;
  width: 336px;
  height: 36px;
  text-align: left;
  margin-left: 40px;
  font-weight: 550;
  margin-bottom: 90px;
}
li {
  list-style: none;
  display: block;
}
.explain1 {
  width: 360px;
  height: 154px;
  color: #646a73;
  font-size: 14px;
  margin-top: 12px;
  line-height: 24px;
}
.work {
  margin-top: 50px;
  font-size: 20px;
  line-height: 1.2;
  font-weight: 600;
}
.work1 {
  margin-top: 150px;
  font-size: 20px;
  line-height: 1.2;
  font-weight: 600;
}
.right {
  margin-top: 60px;
  margin-left: 60px;
}
.left {
  margin-left: 40px;
  margin-top: 80px;
}
.img {
  border-radius: 2%;
  margin-top: 130px;
}
.img1,
.img2 {
  display: inline-block;
  margin-top: 40px;
}
.img1 {
  margin-right: 25px;
}
.title2 {
  font-size: 26px;
  color: #1f2329;
  line-height: 41px;
  margin-left: 560px;
  margin-top: 300px;
  width: 336px;
  height: 41px;
  font-weight: 600;
}
.story {
  display: flex;
  justify-content: center;
  margin-bottom: 72px;
  margin-top: 80px;
  width: 90%;
}
.story1 {
  width: 324px;
  height: 480px;
  margin-left: 270px;
  margin-right: 120px;
}
.picture {
  margin-left: 20px;
}
.story1:hover {
  box-shadow: 0px 0px 25px #f6f6f6;
}
.story2:hover {
  box-shadow: 0px 0px 25px #f6f6f6;
}
.story3:hover {
  box-shadow: 0px 0px 25px #f6f6f6;
}
.story2,
.story3 {
  width: 324px;
  height: 480px;
  margin-right: 120px;
}
.para {
  width: 264px;
  margin-left: 15px;
  margin-top: 32px;
  height: 36px;
  line-height: 36px;
  font-size: 22px;
  color: #1f2329;
}
.name {
  width: 146px;
  height: 22px;
  margin-bottom: 12px;
  line-height: 22px;
  font-size: 12px;
  color: #1f2329;
  margin-left: 65px;
}
.experience {
  text-align: center;
  width: 264px;
  height: 66px;
  margin-bottom: 24px;
  line-height: 22px;
  font-size: 13px;
  color: #646a73;
  overflow: hidden;
  margin-left: 5px;
}
.link {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  color: #51565d;
  border: 1px solid #51565d;
  opacity: 0.2;
  text-align: center;
  margin-left: 120px;
  margin-top: 40px;
}
.link1 {
  width: 16px;
  height: 30px;
  color: #51565d;
  font-size: 22px;
  line-height: 30px;
  overflow: hidden;
}
.link:hover {
  border: 1px solid #3370ff;
  color: #3370ff;
  opacity: 1;
}
.link1:hover {
  color: #3370ff;
  opacity: 1;
}
</style>
