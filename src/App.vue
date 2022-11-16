<template>
  <div id="app">
    <div class="cards">
      <div id="R" class="card">
        <h1>R</h1>
        <ul>
          <li class="movement">The</li>
          <li>Content</li>
          <li>Goes</li>
          <li>Here</li>
        </ul>
      </div>

      <div id="I" class="card">I</div>
      <div id="C" class="card">C</div>
      <div id="RI" class="card">RI</div>
      <div id="RC" class="card">RC</div>
      <div id="IC" class="card">IC</div>
      <div id="RIC" class="card">RIC</div>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style>
.card {
  background-color: Green;
  color: Black;
  padding: 1rem;
}

.cards {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-gap: 1rem;
}
.movement{
  background-color:Orange ;
}
#R {
  background-color: ;
}

/* Screen larger than 600px? 2 column */
@media (min-width: 600px) {
  .cards {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Screen larger than 900px? 3 columns */
@media (min-width: 900px) {
  .cards {
    grid-template-columns: repeat(3, 1fr);
  }
}
</style>
