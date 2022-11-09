<template>
    <div class="ciao">
        <h1>{{title}}</h1>
    </div>
</template>

<script>
export default {
    name: 'AppTitle',
    data(){
        return {
        title: 'La mia prima app con Vite!'
    }
},
}
</script>

<style lang="css">
.ciao {
    width: 80%;
    height: 50px;
    background-color: black;
    text-align: center;
    padding: 10px;
    margin: 0 auto;
}
h1 {
  color: violet;
}
</style>