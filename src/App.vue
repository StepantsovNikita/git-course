<template>
 <div>
  <div>
    <h1>1 задание</h1>
  </div>
  <div :style=" customStyles"></div>
 </div>
</template>

<script>


export default {
  name: 'App',
computed: {
  customStyles() {
    return{
      backgroundColor: 'red',
      color: 'black',
      width: '40px',
      height: '40px',
      border: '3px solid black'
    }
  }
}
 
}
</script>

<style>

</style>
