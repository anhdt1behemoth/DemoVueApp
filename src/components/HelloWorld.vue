<script>
export default {
data(){
  return{
   text:''
    }
  }
}
</script>

<template>
 <input  v-model="text" placeholder="type here">
 <p>{{text}}</p>
</template>

