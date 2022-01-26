<template>
    <div class="main-wrapper">
        <Firstform />
        <Secondform />
        <Thirdform />
        <Fourthform />
        <Fifthform />
        <Sixthform />
    </div>

</template>

<script>
import Firstform from "./Firstform.vue";
import Secondform from "./Secondform.vue";
import Thirdform from "./Thirdform.vue";
import Fourthform from "./Fourthform.vue";
import Fifthform from "./Fifthform.vue";
import Sixthform from "./Sixthform.vue";

export default {
    components: { 
        Firstform,
        Secondform,
        Thirdform,
        Fourthform,
        Fifthform,
        Sixthform,
    },
    name: 'Main',
}
</script>


<style lang="scss">

</style>