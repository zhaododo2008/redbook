<template>
  <div class="framework">
    <div class="container">
      <div class="fixed">

        <nav id="navbar" class="nav">
          <a href="/" class="home">
            <img src="//ci.xiaohongshu.com/12999038-d604-46dc-8d14-30b11c2fc93a" alt="小红书" class="logo">
          </a>
          <div class="tools">
            <span  class="icon red-button android">
            </span>
          </div>
        </nav>
        <div class="search-page" style="display: none;">
          <div class="search-recommend">
            <div class="search-title">
              热门搜索
            </div>
            <div class="search-keywords"></div>
          </div>
          <div class="search-result" style="display: none;">
            <div class="item" style="display: none;">
              <div class="item-link"><strong></strong>
                <span class="num">0篇笔记</span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="filters-block">
        <div class="filters">
          <div class="active">
            <div>推荐</div>
          </div>
          <div>
            <div>时尚</div>
          </div>
          <div>
            <div>美妆</div>
          </div>
          <div>
            <div>美食</div>
          </div>
          <div>
            <div>运动</div>
          </div>
          <div>
            <div>影音</div>
          </div>
        </div>
      </div>
      <div class="banner">
        <div class="carousel-item">
          <div class="video intro-video" style="width: 100%;" videofullscreen="true">

            <div class="poster video__poster" style="min-height: 239.625px;">
              <div class="poster-image cube-image normal-image"
                   style="width: 426px; height: 239.625px;">
                <img src="//ci.xiaohongshu.com/9ea6ee30-74e2-4011-80be-77e7bda0d318"></div>
            </div>
            <div class="mini-bar-container">
              <div class="mini-progress-bar" style="width: 0%;"></div>
            </div>
            <div class="icons">
              <svg width="16px" height="16px" class="cube-icon icons__play-icon">
                <use xlink:href="#poster-play-icon"></use>
              </svg>
              <svg width="16px" height="16px" class="cube-icon icons__loading-icon"
                   style="display: none;">
                <use xlink:href="#loading-icon"></use>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="../../static/css/Launcher.css"></style>
<style scoped src="../../static/css/main.css">
</style>
