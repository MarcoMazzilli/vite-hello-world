<script>
import AppTitle from '../components/AppTitle.vue';

export default {
    data(){
        return{
            AppTitle,
        }
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
    width: 300px;
    height: 500px;
    background-color: blanchedalmond;
    border: 1px solid black;
}
</style>