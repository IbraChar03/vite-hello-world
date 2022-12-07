<script>
export default{
    data(){
        return{
            msg: "La mia prima app con Vite!",
        }
    }
}
</script>

<template>
    <div id="title">
        <h1>{{msg}}</h1> 
    </div>
 
</template>

<style scoped>
h1 {
    font-size: 30px;
  color: blue;
}
#title{
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
