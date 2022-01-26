<template>
    <div class="main-wrapper">
        <Firstform />
        <Secondform />
        <Thirdform />
        <Fourthform />
        <Fifthform />
        <Sixthform />
        <Seventhform />
        <Eighthform />
    </div>

</template>

<script>
import Firstform from "./Firstform.vue";
import Secondform from "./Secondform.vue";
import Thirdform from "./Thirdform.vue";
import Fourthform from "./Fourthform.vue";
import Fifthform from "./Fifthform.vue";
import Sixthform from "./Sixthform.vue";
import Seventhform from "./Seventhform.vue";
import Eighthform from "./Eighthform.vue";

export default {
    components: { 
        Firstform,
        Secondform,
        Thirdform,
        Fourthform,
        Fifthform,
        Sixthform,
        Seventhform,
        Eighthform,
    },
    name: 'Main',
}
</script>


<style lang="scss">

</style>