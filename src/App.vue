<template>
  <div id="app">
    <counter></counter>
  </div>
</template>

<script>
import Message from './components/Message.vue';
import Counter from './components/Counter.vue';

export default {
  name: 'app',
  components: { Message, Counter },
  data () {
    return {}
  }
}
</script>

<style>

</style>
