<template>
<div class="my-component">
    <div>{{ReverseMessage}}</div>
</div>    
</template>

<script>
export default {
    data(){
    return {
     message: 'this is text'
  }
    },
    computed: {
        ReverseMessage(){
            return this.message.split('').reverse().join('')
        }
    }

}
</script>