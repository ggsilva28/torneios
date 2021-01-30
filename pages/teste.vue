<template>

</template>

<script src="../components/request.vue"></script>

<script>
    export default {
        async asyncData({
            $axios
        }) {
            const ip = await $axios.$get('https://my-json-server.typicode.com/ggsilva28/torneios/usuariosm')
            return {
                ip
            }
        }
    }
</script>