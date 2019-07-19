<template>
  <div class="page-swipe">
    <mt-swipe :auto="4000">
      <mt-swipe-item><img src="http://gzhuayihs.com/advance/pics/20190718/1563440423.jpg"></mt-swipe-item>
      <mt-swipe-item><img src="http://gzhuayihs.com/advance/pics/20190718/1563440432.jpg"></mt-swipe-item>
      <mt-swipe-item><img src="http://gzhuayihs.com/advance/pics/20190718/1563441135.jpg"></mt-swipe-item>
    </mt-swipe>
  </div>
</template>

<script>
import { Swipe, SwipeItem } from "mint-ui";
import Vue from "vue";

Vue.component(Swipe.name, Swipe);
Vue.component(SwipeItem.name, SwipeItem);
export default {
  name: "ShoWImg",
  props: {
    // msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.page-swipe {
  height: 300px;
}

.page-swipe .mint-swipe-item {
  line-height: 300px;
}
.page-swipe .mint-swipe-item img{
  width: 100%;
  height: 300px;
}
.mint-swipe {
  height: 100%;
}
</style>
