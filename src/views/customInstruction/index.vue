<template>
  <div class="dialog">
    <input v-model="value" v-anti-shake="getData" type="text">
  </div>
</template>

<script>
export default {
  name: 'CustomInstruction',
  data() {
    return {
      value: ''
    }
  },
  methods: {
    getData() {
      console.log(this.value)
    }
  }
}
</script>

<style lang="scss" scoped></style>
