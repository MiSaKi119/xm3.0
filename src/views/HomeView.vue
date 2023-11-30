<template>
  <div><p>丁卓肖12321312321321123</p></div>
</template>

<script>
import axios from 'axios'
export default {
  data() {
    return {}
  },
  methods: {},
  computed: {},
  filters: {},
  watch: {},
  created() {
    axios
      .post('/api/sys/login', {
        mobile: '17764049967',
        password: 123456
      })
      .catch((res) => {
        console.log(res)
      })
  }
}
</script>

<style lang="scss" scoped></style>
