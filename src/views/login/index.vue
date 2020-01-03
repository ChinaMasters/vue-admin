<template>
  <div class="login"></div>
</template>

<script>
export default {
  name: "login",
  data() {
    return {};
  },
  mounted() {
    const arr = [1, 2, 3];
    const total = arr.reduce((all, item, index) => {
      all.push({
        index,
        label: item
      });
      return all
    }, []);
    console.log("tag", total);
  },
  methods:{

  }
};
</script>

<style scoped lang="scss">
.login {
  min-height: 100%;
  width: 100%;
  overflow: hidden;
}
</style>
