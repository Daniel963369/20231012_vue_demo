<script>
    import { RouterLink, RouterView} from 'vue-router';
    export default {
        components:{
            RouterLink
        }
    }
</script>


<template>
    <nav class="topNav">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/VtextAndVmodel">VtextAndVmodel</RouterLink>
    </nav>
</template>

<style lang="scss" scoped>
.topNav{
    width:100%;
    height:100%;
    background-color:aqua;
    color:palevioletred;
    font-size:26pt;
}
</style>