<template>
    <div >
        <NavBar/>
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import NavBar from '@/components/NavBar.vue'
  
  export default {
    name: 'AdminAccountView',
    components: {
      NavBar, 
    }
  }
  </script>