<script>
import AppTitle from './AppTitle.vue';

export default {
    components:{
        AppTitle,
    }
}
</script>


<template>
<div class="hero">
    <AppTitle class="title text-white display-1"></AppTitle>
</div>
</template>

<style>
.hero{
background-image: url(../assets/download.jpg);
height: 100vh;
background-size: cover;
display: flex;
justify-content: center;
align-items: center;
}
</style>