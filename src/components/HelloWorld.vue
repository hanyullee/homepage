<template>
  <div class="hello">
    <h1 class="kr">{{ msg_kr }}</h1>
    <h1 class="en">{{ msg_en }}</h1>
    <h1 class="es">{{ msg_es }}</h1>
    <!-- <button onClick="src='../assets/spain.m4a'">sound</button> -->
    <!-- <p>
      제 블로그에 방문해 주셔서 감사합니다.
    </p> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg_kr: String,
    msg_en: String,
    msg_es: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1.kr {
  color: black;
}
h1.en {
  color: #39386E;
}
h1.es {
  color:#C70419;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
