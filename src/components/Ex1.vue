<script>
    export default { 
        // Add Code Here
        // challenge: use array  
            data() {
                return {
                    message: "Choose your favourite fruit: ",
                    fruits:['apple','orange','peach'],
                    selected: '' //optional to store which radio is chosen 
                }
            },
            computed: {
                fruit1(){return this.fruits[0]},
                fruit2(){return this.fruits[1]},
                fruit3(){return this.fruits[2]}
            }
    }
</script>

<template>
    <div id="app">
        {{ message }} </br> <!--inserts current value of message-->
        {{ fruit1 }} <input type="radio" name="fruit">
        {{ fruit2 }} <input type="radio" name="fruit">
        {{ fruit3 }} <input type="radio" name="fruit">
    </div>
</template>

<style scoped>
</style>
