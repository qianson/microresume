<template>
  <div class="hello">
    你是什么意思
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'
@Component({})
export default class HelloWorld extends Vue {
  get getMount () {
    return 1
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  font-size: 30px;
}
</style>
