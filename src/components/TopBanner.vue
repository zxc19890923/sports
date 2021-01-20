<template>
  <div class="topBanner">
    <div class="topBannerLeft">
      <div class="topBannerTitle">山东省智体评估</div>
    </div>
    <div class="topBannerRight">
        <div class="topBannerRightText">
            <span>登录</span>
            <span>注册</span>
        </div>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style scoped>
.topBanner {
  height: 64px;
  line-height: 20px;
  background-color: rgba(255, 255, 255, 100);
  text-align: center;
  border: 1px solid rgba(255, 255, 255, 100);
  display: flex;
  flex-direction: row;
  align-items: center;
  width: 1024px;
  margin: 0 auto;
}
.topBannerLeft {
  flex: 1;
  text-align: left;
}
.topBannerRight {
  width: 200px;
  text-align: left;
}
.topBannerTitle {
  color: rgba(16, 16, 16, 100);
  font-size: 25px;
  font-family: SourceHanSansSC-bold;
}
</style>
