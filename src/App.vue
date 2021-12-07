<template>
  <div id="app">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <h1>hello wolrd</h1>

    <p>
      <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aperiam at aut cum cumque eius error iste magni maiores neque odio omnis quibusdam, quidem quo recusandae sed temporibus veritatis voluptatem!</span><span>At ducimus eveniet mollitia quas sequi? Ab accusamus amet dignissimos et illo illum iure provident recusandae sapiente? Autem consectetur dolores iure nesciunt obcaecati officia pariatur quam. Non optio quidem quod!</span><span>Ad aperiam aspernatur cumque, dolore ducimus, ea ex facere incidunt ipsa magni molestias nam obcaecati quas quidem quos tempore ut, vero! Dolore facilis, iste molestias nemo sequi tempora voluptas voluptatem?</span><span>Animi atque autem blanditiis, commodi dignissimos doloribus eum, exercitationem incidunt iure molestiae neque possimus praesentium quod soluta tempora! Adipisci consequatur consequuntur ducimus harum iusto laudantium magni neque quisquam repellat vitae.</span><span>Ad amet assumenda autem doloribus est ex id illo laudantium nesciunt porro provident quis quod reprehenderit, sequi sunt unde voluptatibus. Culpa distinctio eius eum, expedita incidunt nam repudiandae temporibus. Tempore.</span><span>Ab ad atque autem dicta, ducimus et hic id incidunt libero modi nobis possimus quod recusandae sapiente ullam unde veniam voluptatibus? Adipisci corporis deleniti dignissimos fuga, fugit nam quam voluptas!</span><span>Cupiditate ducimus earum hic maxime numquam odio possimus quo saepe sapiente. Autem commodi consectetur ducimus eveniet ex facere id minima minus, neque nesciunt temporibus tenetur, voluptas? Cupiditate illum inventore unde!</span><span>Corporis, quo, recusandae? A asperiores delectus dicta doloribus maiores, repellat voluptas? Animi corporis debitis dolores ducimus natus neque optio perferendis, possimus ratione rem totam vero. Eaque harum iure veniam voluptatum!</span><span>Distinctio doloremque, dolores eius fuga libero numquam voluptas. Accusantium amet aut blanditiis deleniti doloremque dolorum expedita incidunt, nemo nostrum, perferendis porro quos repudiandae sapiente similique sit tempore tenetur veniam voluptatem.</span><span>Accusamus aperiam eaque eos ex illo maiores modi nam necessitatibus numquam odit, officiis quisquam sequi sint suscipit, vel veritatis voluptas. Architecto blanditiis, consequatur delectus dolorem harum molestias nisi provident similique.</span>
    </p>

    <Car/>
    <Student/>

  </div>
</template>

<script>
import Car from './components/Car.vue'
import Student from "@/components/Student";

export default {
  name: 'App',
  components: {
    Car,
    Student
  }
}
</script>


