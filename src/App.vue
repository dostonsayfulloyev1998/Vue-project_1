<template>
  <div id="app">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <form action=""  class="w-50 m-5">

      <div class="form-group">
        <label for="">name</label>
        <input type="text" class="form-control" v-model="newName">
      </div>

      <div class="form-group">
        <label for="">surname</label>
        <input type="text" class="form-control" v-model="newSurname">
      </div>

      <div class="form-group">
        <label for="">age</label>
        <input type="text" class="form-control" v-model="newAge">
      </div>

      <button @click="add" class="btn btn-success" type="button">button</button>
    </form>

    <Student  :todo="talabalar" @remove="talabalar.splice(index,1)"/>

  </div>

</template>

<script>

// import Count from './components/Count.vue'
import Student from "./components/Student"
// import Form from "./components/Form"

export default {
  name: 'App',
  data(){
    return{
      newId:6,
      newName:"",
      newSurname:"",
      newAge:"",
      talabalar:[
        {
          id: 1,
          name:"Ali",
          surname:"Vali",
          age:25
        },
        {
          id: 2,
          name:"Ali",
          surname:"sherali",
          age:40
        },
        {
          id: 3,
          name:"Alisher",
          surname:"Vali",
          age:25
        },
        {
          id: 4,
          name:"Alijon",
          surname:"Vali",
          age:25
        },
        {
          id: 5,
          name:"sherali",
          surname:"Valiyev",
          age:35
        }
      ]
    }
  },
  components:{
    // Count,
    Student
    // Form
  },
  methods:{
    add(){
        this.talabalar.push({
          id:this.newId++,
          name: this.newName,
          surname: this.newSurname,
          age:this.newAge
        }),
         this.newName='',
         this.newSurname='',
         this.newAge=''
    }
  }
}

</script>


