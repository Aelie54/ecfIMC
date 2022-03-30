<template>

<div id="app">
    <div class="container-fluid">
        <div class="row">
            <div class=" col-md-12">
                <h1>My height :{{ height }}cm</h1>
                <input v-model="height">
                <h1>My weight :{{ weight }}kg</h1>
                <input v-model="weight">
              
                <h2>My BMI is {{ bmiCalculation }}</h2>
            </div>
        </div>
    </div>
</div>

</template>

<script>

</script>