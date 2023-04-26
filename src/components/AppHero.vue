<script>
import AppTitle from '../components/AppTitle.vue';

export default {
    data(){
        return{
        }
    },
    components :{
        AppTitle
    }
}
</script>

<template>
  
<div class="jumbotron">
    <AppTitle />
</div>

</template>

<style>

.jumbotron {
    width: 70%;
    height: 500px;
    margin: 0 auto;
    padding: 10px;
    background-color: blanchedalmond;
    border: 1px solid black;
}
</style>