<template>
   <div>
          <table class="table table-striped">
              <thead>
                  <tr>
                      <th>name</th>  <th> surname</th>  <th>age</th>
                  </tr>
              </thead>

            <tbody>
                 <tr v-for="item in talabalar" :key="item">
                       <td>{{item.name}}</td>   <td>{{item.surname}}</td>  <td>{{item.age}}</td>
                 </tr>
            </tbody>

          </table>
   </div>

</template>


<script>
    export default {
         name:"Student",
        data(){
           return{
               talabalar:[
                 {
                   name:"ali",
                   surname:"vali",
                   age:24
                 },
                 {
                   name:"vali",
                   surname:"vali",
                   age:24
                 },
                 {
                   name:"alisher",
                   surname:"vali",
                   age:24
                 },
                 {
                   name:"sherali",
                   surname:"vali",
                   age:27
                 }
               ]
           }
        }
    }
</script>