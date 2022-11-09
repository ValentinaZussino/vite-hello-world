<template>
    <div class="ciao">
        <span>{{title}}</span>
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
    line-height: 25px;
    font-weight: bold;
    font-size: 20px;
}
span {
  color: rgb(255, 130, 255);
}
</style>