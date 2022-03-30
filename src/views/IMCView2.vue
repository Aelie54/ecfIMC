<template>
  <div>

<h1> MERDE FAIT CHIER TIENS </h1>
    <!-- <form @submit.prevent="$emit('form-submit', user)">
      <br />
      <label for="poids">poids (en kg)</label><br />
      <input type="integer" v-model="user.height" id="poids" min="35" max="200" /><br/><br/>

      <label for="taille">taille (en m)</label><br />
      <input
        type="float" v-model="user.weight" id="taille" min="1,3" max="2.2"/><br /><br />

      <input type="submit" value="Calcul de mon IMC" />
    </form> -->

     <h2>My BMI is {{ bmiCalculation }}</h2>

  </div>
</template>

<style>
  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
</style>

<script setup>
// import Login from "../components/forms/imc.vue";

  let user = {
    height : user.height,
    weight : user.weight
  };

</script>