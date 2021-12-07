<template>

  <div id="one">
       <h1>count: {{count}}</h1>
        <button class="btn btn-primary" @click="plus">plus</button>
        <button class="btn btn-danger" @click="minus">minus</button>
  </div>

</template>

<script>

export default {
  data(){
    return{
      count:0
    }
  },
  methods:{
    plus(){
       this.count++
    },
    minus(){
      if (this.count>0)
       this.count--
    }
  }
}

</script>


<style>
#one{
  border:1px solid #000;
  margin: 20px;
  padding: 20px;
  border-radius:10px;
}

</style>