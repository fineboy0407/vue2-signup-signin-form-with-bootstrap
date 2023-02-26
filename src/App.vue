<template>
   <div class="vue-template">
     <!-- Navigation -->
     <nav class="navbar shadow bg-white rounded justify-content-between flex-nowrap flex-row fixed-top">
        <div class="container">
            <a class="navbar-brand float-left" href="https://github.com" target="_blank">fineboy</a>
        </div>
        <ul class="nav navbar-nav flex-row float-right">
          <li class="nav-item">
            <router-link class="nav-link pr-3" to="/login">Sign in</router-link>
          </li>
          <li class="nav-item">
            <router-link class="btn btn-outline-primary" to="/">Sign up</router-link>
          </li>
        </ul>
     </nav>

     <!-- Main -->
     <div class="App">
        <div class="vertical-center">
          <div class="inner-block">
            <router-view/>
          </div>
        </div>
     </div>
   </div>
</template>
<script>
export default {
   name: '',
   components: {
     
   },
   mixins: [],
   props: {
     
   },
   data() {
     return {
       
     }
   },
   computed: {
     
   },
   watch: {
     
   },
   mounted() {
     
   },
   methods: {
     
   }
};
</script>
<style lang='' scoped>
</style>