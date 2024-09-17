<template>
    <div>
        <h1>{{ mensaje }}</h1>
    </div>
</template>

<script>
    export default{
        name: 'MiPrueba',
        data(){
            return{
                mensaje: 'Hola desde el componente!'
            };
        }
    };
</script>

<style scoped>
    h1{
        color: green;
    }
</style>