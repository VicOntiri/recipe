<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to cook<br>
      check out the following...
    </p>

    <p>
Not everybody loves cooking, but once in a blue moon, we always get the urge to jump into the kitchen 
and whip up something delicious. However, it is hard to keep your culinary game fresh if you lack new 
ideas and always prepare the same old dish that you inherited from your mum. This is why you need to check
 out various recipe from Home Cooks for inspiration. But, how do you know the right recipe, considering that there 
 are thousands of them out there?
 This is why we have scoured through the internet and brought you one of the best recipe website.
</p>
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
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 10px;
}
a {
  color: #42b983;
}
</style>
