<template>
    <div class="my-component">
        <div>{{ message }}</div>
        <div><button @click="sayHello">click Me!</button></div>
    </div>
</template>



<script>
export default {
    data(){
        return{
            message: 'this is my first component using binding data'
        }
    },
    methods: {
        sayHello(){
             alert('Hello World')
        }
    }
    
}
</script>

<style  scope>
.my-component{
    color:red;
}
</style>