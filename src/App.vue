<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <!-- <HelloWorld message="Welcome to the jungle.js App" /> -->
    <h1>Liste des fournisseurs</h1>
    <button v-on:click="onSuppliersListClic">
      amine
    </button>
    <button v-on:click="onMapClick">
      wesh
    </button>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    //     HelloWorld // = HelloWorld: HelloWorld
  },
  methods: {
    onSuppliersListClic: function(event) {
      alert("Hello " + "amine" + "!");
      alert(event.target.tagName);
    },
    onMapClick: function(event) {
      alert("Hello " + "tout le mondes" + "!");
      alert(event.target.tagName);
    }
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
