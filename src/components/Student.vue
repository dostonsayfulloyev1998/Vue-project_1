<template>
     <div>
            <table class="table table-striped">
                 <thead>
                      <tr>
                         <th>name</th>  <th>surname</th>  <th>age</th>
                      </tr>
                 </thead>

                 <tbody>
                     <tr :key="todo">
                         <td>{{todo.name}}</td>  <td>{{todo.surname}}</td>  <td>{{todo.age}}</td>
                         <td> <button @click="$emit('remove')" class="btn btn-danger">Remove</button> </td>
                     </tr>
                 </tbody>

            </table>
     </div>
</template>

<script>
    export default {
      props:['todo'],
      data(){
         return{

         }
      }
    }
</script>