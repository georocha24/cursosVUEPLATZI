<template>
    <div>
        <p>Lorem Ipsun</p>
        <div>
            {{ text }}
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                text: "Hola"
            }
        },
    }
</script>

<style>
    p {
        color: red;
    }
</style>