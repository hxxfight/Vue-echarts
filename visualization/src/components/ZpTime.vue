<template>
  <div id="zptime">
    {{ setDate }}
  </div>
</template>

<script>
export default {
  name: 'zptime',
  data() {
    return {
      date: new Date()
    }
  },
  computed: {
    setDate() {
      return ` ${this.date.getFullYear()}年${
        this.date.getMonth() + 1
      }月${this.date.getDate()}日  ${this.date.getHours()}时${this.date.getMinutes()}分${this.date.getSeconds()}秒`
    }
  },
  mounted() {
    setInterval(() => {
      this.date = new Date()
    }, 1000)
  }
}
</script>
<style scoped>
#zptime {
  line-height:16px;
  font-size: 16px;
}
</style>
