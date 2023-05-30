<template>
    <h1>{{ title }}</h1>
</template>
<script setup>
// const title= "hola mundo"; esto es para ponerle el mismo valor a todos. esto esta en abc.vue
defineProps({title: String}) //esto es para asignar un parametro diferente a cada pagina, esto esta en home y about.vue
</script>