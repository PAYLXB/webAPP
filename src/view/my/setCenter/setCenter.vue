<template>
  <div class="canCash">
     <mt-header title="设置中心">
      <router-link to="/home/my" slot="left">
        <mt-button icon="back"></mt-button>
      </router-link>
    </mt-header>
    <div>
      <mt-cell title="平台合作协议" to="/cooperation"  is-link></mt-cell>
      <mt-cell title="关于我们" to="/about"  is-link></mt-cell>
      <mt-cell title="版本更新" to="/update"  is-link></mt-cell>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
    };
  },
  methods: {


  },

  watch: {
  }
};
</script>

<style scoped>
.canCash{
  margin-top: 90px;
}
</style>
