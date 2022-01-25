<template>
    <div class="main-wrapper">
        <Firstform />
        <Secondform />
        <Thirdform />
    </div>

</template>

<script>
import Firstform from "./Firstform.vue";
import Secondform from "./Secondform.vue";
import Thirdform from "./Thirdform.vue";

export default {
    components: { 
        Firstform,
        Secondform,
        Thirdform,
    },
    name: 'Main',
}
</script>


<style lang="scss">

</style>