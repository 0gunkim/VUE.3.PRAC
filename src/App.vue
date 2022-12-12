<script>


export default {
  data() {
    return {
      count: 0
    }
  },

  methods: {
    add() {
      this.count++
    },
    minus() {
      this.count--
    }
  },

  // mounted() {
  //   console.log(`The initial count is ${this.count}.`)
  // }
}
</script>

<template>
  <button @click="add">+</button>
  <button @click="minus">-</button>
  <div> result {{ count }}</div>
</template>