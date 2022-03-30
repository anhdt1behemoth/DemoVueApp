<template>
    <div id="my-text">
        This is my text
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Hello World'
            }
        },
        beforeCreate() {
            console.log(this.message)
        }
    }
</script>

<style lang="scss" scoped>
</style>
