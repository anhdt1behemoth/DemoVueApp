<script>
export default {
data(){
  return {
    titleClass: 'title'
  }
 }
}



</script>

<template>
<h1 :class="titleClass">Make me red</h1>
</template>

<style>
.title:hover{
  color: red;
  font-size: 30px;
}
</style>


