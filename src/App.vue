<template>
  <HelloWorld/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>


@media (prefers-color-scheme: light) {
  * {
    --bg: #eeeff7;
    --text_color: #2c3e50;
    --logo_l_background: #209CEE;
    --logo_l_color: #efdbc5;
    --logo_omni_color: #4f515d;
    --yellow: #eaccab;
    --green:#42b983;
  }
}

@media (prefers-color-scheme: dark) {
  * {
    --bg: #22272e;
    --text_color: #cadae7;
    --logo_l_background: #345890;
    --logo_l_color: #ffecdb;
    --logo_omni_color: #ccd2e6;
    --yellow: #eaccab;
    --green:#42b983;
  }
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: var(--text_color);
}

body{
  background-color: var(--bg);
  margin: 5em;
}

</style>
