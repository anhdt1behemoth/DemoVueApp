<script>
export default {
    mounted(){
        this.$refs.p.textContent = 'Mounted!'
    }
}
</script>

<template>
    <p ref="p">Hello</p>
</template>