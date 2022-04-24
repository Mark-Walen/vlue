<template>
  <div class="bm-header-container">
    <a href="/">
      <div class="left bm-logo">
        <div class="bm-zh">
          <span id="text-yellow">蓝</span>
          <span id="text-blue">芒</span>开源
        </div>
        <div class="bm-en">Blue Monster</div>
      </div>
    </a>
    <ul class="center bm-navigation">
      <li class="bm-nav-item">
        <i></i>
        <a href="#" class="bm-a-home">首页</a>
      </li>
      <li class="bm-nav-item">
        <a href="#" class="bm-a-exhibition">开源馆</a>
      </li>
      <li class="bm-nav-item">
        <i></i>
        <a href="#">档案馆</a>
      </li>
      <li class="bm-nav-item">
        <i></i>
        <a href="#">游戏厅</a>
      </li>
      <li class="bm-nav-item">
        <i></i>
        <a href="#">关于我</a>
      </li>
    </ul>
    <div class="bm-toolbox">
      <span class="bm-button">搜索</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "BM-Header",
};
</script>

<style scoped lang="less">
.bm-header-container {
  width: 100%;
  height: 75px;
  display: inline-flex;

  .bm-logo {
    width: 200px;
    text-align: justify;
    text-align-last: justify;
    div {
      &.bm-zh {
        font-size: 32px;
        span {
          &#text-yellow {
            color: var(--theme-color-light-yellow);
          }
          &#text-blue {
            color: var(--theme-color-light-blue);
          }
        }
      }

      &.bm-en {
        font-size: 24px;
        text-transform: uppercase;
      }
    }
  }

  ul.bm-navigation {
    display: inline-flex;
    align-content: center;
    align-items: center;
    justify-content: center;
    list-style: none;
    flex-grow: 1;
    li {
      float: left;
      padding: 0 30px;
      &:first-child {
        padding-left: 0;
      }
      &:last-child {
        padding-right: 0;
      }
      a {
        text-decoration: none;
        font-size: 20px;
      }
    }
  }
  .bm-toolbox {
    flex-grow: 0.25;
  }
}
</style>
