<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Документация:
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">
        vue-cli documentation
      </a>
    </p>
    <h3>Стартовый проект на Vue CLI</h3>
    <p>Здесь нет ничего лишнего</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
