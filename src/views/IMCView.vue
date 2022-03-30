<template>
  <div>
    <h1>ici est censé être importé le formulaire</h1>
    <imc @form-submit="FormSubmit" />
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

<script>
import imc from "../components/forms/imc.vue";

  // let user = {
  //   height : user.height,
  //   weight : user.weight,
  // };

</script>