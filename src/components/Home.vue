<template>
    <div>
      <h1>Hello From New Trial Component By Me</h1>
      <h2>{{data}}</h2>
      <h3>{{msg}}</h3>
    </div>
</template>
<script>
export default {
    name : 'Home',
    props: {
        data: String,
        msg: String,
        butterfly: Image
    }
}
</script>

<style>
img {
  border: 5px solid rgba(226, 157, 46, 0.616);
}
body {
  background-color: rgb(26, 19, 17);
}
</style>