<template>
  <header class="ui-header">
    <div class="ui-header-container">
       <div class="ui-logo">
         <a href="/">
           <img src="https://vuejs.org/images/logo.png" alt="Vue Forum">
         </a>
       </div>
       <div class="ui-panel">
         <ul class="ui-header-funciton">
           <li class="ui-header-search">
             <a class="ui-search-button">
               <i class="icon-search"></i>
             </a>
           </li>
           <li class="ui-header-hamburger-menu">
             <a class="ui-hamburger-menu-button">
               <i class="icon-hamburger-menu"></i>
             </a>
           </li>
           <li class="ui-header-current-user">
             <a class="ui-current-user">
               <img src="" />
             </a>
           </li>
         </ul>
       </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {},
  data() {
    return {
      isSearch: false,
      isMenu: false,
      isUser: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
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
