<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa" target="_blank" rel="noopener">pwa</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router" target="_blank" rel="noopener">router</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h1>Romano</h1>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Bacon</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">comida</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Pizza</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">carne</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Xesque</a></li>
    </ul>
    <h3>Fabio</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">cenoura</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">abacaxi</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">pepino</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">rabanete</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">pimenta</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
