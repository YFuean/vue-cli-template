<template>
  <div>
    <h3>Welcome to this page</h3>
    <router-link to="/home">
      <h3>to home page</h3>
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'Welcome',
  data() {
    return {}
  },
  components: {},
  created() {},
  mounted() {},
  methods: {},
  computed: {}
}
</script>

<style scoped lang="scss">
div {
  background: #85acb1;
  height: 100vh;
}
</style>
