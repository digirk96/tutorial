<template>
  <the-header title="Remember Me"></the-header>
<the-resource></the-resource>
</template>

<script>

import TheHeader from './components/layouts/TheHeader.vue'

import TheResource from './components/learningresource/TheResource.vue'
export default {
    name: 'App',
    components: {
      TheResource,
        TheHeader
    },

 

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,500;0,700;0,900;1,300;1,400;1,500;1,700;1,900&display=swap');
*{
  box-sizing: border-box;
}
html{
  font-family: 'Roboto', sans-serif;
}
body{
  margin: 0;
}

</style>
