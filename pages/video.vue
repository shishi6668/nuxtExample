<template>
  <div class="connection">
    <div class="banner">
      <video autoplay loop width="100%">
        <!-- src属性中指定要播放视频地址,可直接写在video标签内，也可以使用source标签 -->
        <!-- <source> 标签为媒介元素（比如 <video> 和 <audio>）定义媒介资源。 -->
        <!-- <source> 标签 h5 允许您规定可替换的视频/音频文件供浏览器根据它对媒体类型或者编解码器的支持进行选择。 -->
        <source src="../static/video/connection.mp4" />mp4加载失败
      </video>
    </div>
    <div class="container">
      <div>
        <h3>能力介绍</h3>
        <div></div>
      </div>
      <div>
        <h3>优势</h3>
        <div></div>
      </div>
      <div>
        <h3>核心产品介绍</h3>
        <div></div>
      </div>
      <div>
        <h3>应用场景</h3>
        <div></div>
      </div>
      <div>
        <h3>关于平台</h3>
        <div></div>
      </div>
    </div>
  </div>
</template>
<style lang="less" scoped>
.connection{
    .container{
        & > div:nth-child(2) h3{
            color: #fff;
        }
    }
}
</style>
