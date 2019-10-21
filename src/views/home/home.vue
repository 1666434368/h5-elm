<template>
  <div class="home">
    <div class="search">
      <div class="content">
        <span>搜索饿了么商家、商品名称</span>
      </div>
    </div>
    <tab-bar />
  </div>
</template>

<script>
import TabBar from '@/components/tabBar.vue'
export default {
  name: 'Home',
  components: {
    TabBar
  }
}
</script>

<style lang="scss" scoped>
.home {
  min-height: 100%;
  .search{
    position: sticky;
    z-index: 999;
    top: 0;
    background-image: linear-gradient(90deg,#0af,#0085ff);
    padding: .2rem .373333rem;
    margin: -.133333rem 0;
    .content{
      display: flex;
      width: 100%;
      height: .96rem;
      justify-content: center;
      align-items: center;
      border-radius: .026667rem;
      background: #fff;
      color: #999;
      font-size: .373333rem;
    }
  }
}
</style>
