<template>
  
  <main>
    <div>
      <a id="msg">
        Hello My Name Is Khaled
      </a>
  
  
  
    </div>
  </main>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",

};
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


#app{
  background-image: url('../assets/background-home.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main {
  min-height: 100vh;
  padding: 25px;

  background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.25), rgba(0, 0, 0, 0.75));
}
#msg{

  font-size: 150px;
  font-style: italic;
  color: beige;
  
}

</style>
