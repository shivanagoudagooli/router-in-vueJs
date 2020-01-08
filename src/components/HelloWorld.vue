<template class="back">
  <div >
    <!-- <h1>{{ msg }}</h1> -->
    <h1>login Page </h1>
    Enter UserName :<input type="text"/><br>
    <br>
    Entere Password :<input type="text"/>
    <br><br>
     <input type="submit"  value="OK" style="margin-left:30px"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
     <router-link to="/about">
       <input type="submit" value="SignUp" style="margin-left:60px"/>
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.back{
  background-color: aqua;
}
</style>
