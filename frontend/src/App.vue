<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
#app {

  --dark-1: #02244A;
  --dark-1-clear: rgba(2, 36, 74, .8);
  --dark-2: #164869;
  --light-1: #8CE5F5;
  --light-2: #55BDCA;
  --gray: #f6f6f6;
  --accent: #DF622C;

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

.white{
  background-color: white !important;
}
.gray{
  background-color: var(--gray) !important;
}
.dark-1{
  background-color: var(--dark-1) !important;
}
.dark-2{
  background-color: var(--dark-2) !important;
}
.light-1{
  background-color: var(--light-1) !important;
}
.light-2{
  background-color: var(--light-2) !important;
}
.light-3{
  background-color: var(--light-3) !important;
}
.accent-1{
  background-color: var(--accent) !important;
}


#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
}

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

h1, h2, h3, h4, h5, h6{
  font-family: 'Poppins', sans-serif;
  color: black;
}

</style>
