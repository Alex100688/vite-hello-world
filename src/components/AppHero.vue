<script>
export default {
  data() {
    return {
      JumboTron:'JumboTron'  
     
    }
  }
}
</script>

<template>
    <div>
     <h3>{{JumboTron}}</h3>   
    </div>
</template>

<style scoped>
   div{
    width: 37.5rem;
    height: 25rem;
    background-color: black;
    background-size: cover;
    display: flex;
    justify-content: center;
    margin: auto;
   }
   h3{
    display: flex;
    align-items: center;
    font-size: 1.5625rem;
    font-weight: bold;
    color: #ffff;
   }
</style>