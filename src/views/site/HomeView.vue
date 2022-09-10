<template>
  <div>
    <IndexView />
  </div>
</template>

<script>
import IndexView from "./index/IndexView.vue";
export default {
  name: "HomeView",
  components: { IndexView },
};
</script>
<style scoped lang="scss">
// از پوشه نود ماژول خوانده میشود
@import "bootstrap/scss/bootstrap.scss";

// .home {
//   color: $red;
// }
</style>
