<template>
   <div v-if="spinner"><Spinner/></div>
    <div v-else><Products/></div>
</template>
<script>
import Products from "../components/ProductsView.vue";
import Spinner from "../components/SpinnerView.vue";
export default {
    components: {
        Products,
        Spinner
    },
    data (){
        return {
            spinner:false
        }
    }
}
</script>
<style>
    
</style>