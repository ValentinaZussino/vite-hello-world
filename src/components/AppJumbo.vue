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
    height: 50vh;
    width: 100%;
    background-image: url(https://picsum.photos/1980/460?grayscale);
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>