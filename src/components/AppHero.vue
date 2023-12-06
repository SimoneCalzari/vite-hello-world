<script>
export default {
  data() {
    return {
      title: "Ciao sono Jumbotron, benvenuto nella mia pagina!",
      par: "I am a simple hero unit, a simple jumbotron-style component for calling a extra attention to featured content of information",
    };
  },
};
</script>

<template>
  <div class="jumbo">
    <div class="container">
      <h2>{{ title }}</h2>
      <p>{{ par }}</p>
    </div>
  </div>
</template>

<style scoped>
.jumbo {
  background-color: gainsboro;
  height: 300px;
  display: flex;
}

.container {
  width: 75%;
  margin: auto;
}

h2 {
  color: white;
  font-size: 45px;
  margin-bottom: 20px;
}

p {
  font-size: 30px;
  color: #1a73e8;
}
</style>
