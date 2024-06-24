<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <p>{{ num }}</p>
    <button @click="add">add 1</button>
  </main>
</template>

<script>
  export default {
    data() {
      return {
        num: 0
      }
    },
    methods: {
      add() {
        this.num = this.num + 1
      }
    }
  }
</script>