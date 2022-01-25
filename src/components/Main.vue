<template>
    <div class="main-wrapper">
        <Firstform />
        <Secondform />
    </div>

</template>

<script>
import Firstform from "./Firstform.vue";
import Secondform from "./Secondform.vue";

export default {
    components: { 
        Firstform,
        Secondform,
    },
    name: 'Main',
}
</script>


<style lang="scss">

</style>