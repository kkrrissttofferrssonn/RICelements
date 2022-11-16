<template>
  <div id="app">
    <div class="cards">
      <div id="R" class="card">
        <h1 class="cardTitle">R</h1>
        <ul>
          <li class="movement">The</li>
          <li class="route">Content</li>
          <li class="neuro">Goes</li>
          <li>Here</li>
        </ul>
      </div>
      <div id="I" class="card">
        <h1 class="cardTitle">I</h1>
        <ul>
          <li id="" class=""></li>
        </ul>
      </div>
      <div id="C" class="card">
        <h1 class="cardTitle">C</h1>
        <ul>
          <li id="" class=""></li>
        </ul>
      </div>
      <div id="RI" class="card">
        <h1 class="cardTitle">RI</h1>
        <ul>
          <li id="" class=""></li>
        </ul>
      </div>
      <div id="RC" class="card">
        <h1 class="cardTitle">RC</h1>
        <ul>
          <li id="" class=""></li>
        </ul>
      </div>
      <div id="IC" class="card">
        <h1 class="cardTitle">IC</h1>
        <ul>
          <li id="" class=""></li>
        </ul>
      </div>
      <div id="RIC" class="card">
        <h1 class="cardTitle">RIC</h1>
        <ul>
          <li id="" class=""></li>
        </ul>
      </div>
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
/*Card*/
.card {
  background: DarkGreen;
  color: Black;
  padding: 1rem;
  padding-top: 0.3rem;
}

.cards {
  max-width: 1200px;
  margin: 0 auto;
  display: grid;
  grid-gap: 0.5rem;
}
.cardTitle {
  display: flex;
  justify-content: center;
  font-weight: Bold;
  color: Black;
  text-decoration: underline;
  margin-top: 0.1rem;
}

li {
  padding: 0.3rem;
}

/*Movement or Route or Neuro*/

.movement {
  background: Orange;
}
.route {
  background: SkyBlue;
}
.neuro {
  background: Violet;
}
#R {
  background-color: ;
}

/*Grid*/

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
