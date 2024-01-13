<template lang="">
    <div>
        <headers></headers>
        <carousel></carousel>
        <div class="w-screen flex justify-center items-center">
            <div class="w-[93vw] grid grid-cols-3 justify-center items-center gap-x-8">
                <div>
                    <h4>
                        Titre
                    </h4>
                    <p>
                        lloremasgdjgajsgdjhagsjhdgajsjdhgajsgdjga jagsjdgajsgdjagsjdg
                    </p>
                </div>
                <div>
                    <h4>
                        Titre
                    </h4>
                    <p>
                        lloremasgdjgajsgdjhagsjhdgajsjdhgajsgdjga jagsjdgajsgdjagsjdg
                    </p>
                </div>
                <div>
                    <h4>
                        Titre
                    </h4>
                    <p>
                        lloremasgdjgajsgdjhagsjhdgajsjdhgajsgdjga jagsjdgajsgdjagsjdg
                    </p>
                </div>
                
            </div>
        </div>
        <div class="w-screen flex justify-center items-center">
            <div class="min-w-[93vw] flex justify-between items-center">
                <div class="w-1/2">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quis obcaecati asperiores dicta, excepturi illo assumenda rem aperiam velit tenetur dolorem inventore sunt quisquam magni repellat deleniti voluptate aliquam dolor?</p>
                </div>
                <div class="w-1/2 "><img class="" src="../../assets/alexander.jpg" alt=""></div>
               
            </div>
        </div>
    </div>
</template>
<script>
import carousel from '@/components/client/carousel.vue';
import headers from '@/components/client/header.vue';
export default {
    components: {
        headers, carousel
    }
}
</script>
<style lang="">
    
</style>