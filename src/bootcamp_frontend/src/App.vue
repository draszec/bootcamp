
<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Hello there!
    <br/>
    <button @click="increase">Podbij</button>
      {{ counter }}
  </main>
</template>

<script>
export default {
  data() {
    return {
      counter: 0
    }
  },
  methods: {
    increase() {
      this.counter++
    }
  }
}
</script>