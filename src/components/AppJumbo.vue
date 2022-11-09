<template>
    <div class="my-jumbo">
        <AppTitle/>
    </div>
</template>

<script>
    import AppTitle from './AppTitle.vue';
    export default {
        name: 'AppJumbo',
        components: {
            AppTitle,
        }
    }
</script>

<style lang="css">
.my-jumbo {
    height: 40vh;
    width: 100%;
    background-color: violet;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>