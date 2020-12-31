<script>
export default {
  data() {
    return { msg: 'zbc', cc: '123', afd: 'adfsdf' };
  },
};
</script>

<template>
  <div v-for="a in 5" :key="a" cl2ass="hello" cl3ass="hello" cla4ss="hello">
    {{ msg }}
  </div>
</template>

<style lang="less">
.app {
  color: red;
  font-size: 16px;
  span {
    font-weight: bold;
  }
}
</style>
