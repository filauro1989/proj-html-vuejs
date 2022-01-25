<template>
    <div class="main-wrapper">
        <Firstform />
        <Secondform />
        <Thirdform />
        <Fourthform />
    </div>

</template>

<script>
import Firstform from "./Firstform.vue";
import Secondform from "./Secondform.vue";
import Thirdform from "./Thirdform.vue";
import Fourthform from "./Fourthform.vue";

export default {
    components: { 
        Firstform,
        Secondform,
        Thirdform,
        Fourthform,
    },
    name: 'Main',
}
</script>


<style lang="scss">

</style>