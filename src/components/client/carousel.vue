<template lang="">
    <div class="w-screen flex justify-center items-center">
        <div class="max-w-[93vw] flex justify-between items-center">
            <div class="w-4/12">
                Bienvenu chez nous
            </div >
            <div class="w-8/12"><img src="../../assets/alexander.jpg" alt=""></div>
        </div>
    </div>
</template>
<script>
import Transition  from 'vue';
export default {
    components:{
        
    }
}
</script>
<style scoped>
    .v-enter-active {
        transition:transform  0.5s;
    }
    .v-enter-from{
        transform: translateX(200px);
    }
</style>