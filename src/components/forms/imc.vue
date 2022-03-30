<template>
  <div>
    <form @form-submit="FormSubmit">
      <br />

      <label for="poids">poids (en kg)</label><br />
      <input type="integer" v-model="user.height" 
      id="poids" min="35" max="200" /><br/><br/>

      <label for="taille">taille (en m)</label><br />
      <input
        type="float" v-model="user.weight" 
        id="taille" min="1,3" max="2.2"/><br /><br />

      <input type="submit" value="Calcul de mon IMC" />

    </form>

     <h2>My BMI is {{ user.bmiCalculation }}</h2>
  </div>
</template>

<script>

export default {
  data() {
    return {
      user: {
        height: "",
        weight: "",
        bmiCalculation : "",7
        },
    };
  },
};

function FormSubmit() {

  let datas = {
    username: user.username,
    password: user.password,
    bmiCalculation : user.bmiCalculation,
  };

    console.log("bonjour");
}


</script> 
