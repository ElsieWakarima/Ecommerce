<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/Order">Order</router-link>
    <router-link to="/cart"><img src="@/components/img/cart2.jpg" class="cart"></router-link>
  </nav>
  <router-link to="/contact"><img src="@/components/img/icon.jpeg" class="icon"></router-link>
  <router-view/>
</template>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.icon{
  position:fixed;
  width:60px;
  bottom:10%;
  right:0;
}
.icon:hover{
  width:50px;
  border:3px solid rgb(146, 139, 139);
  border-radius:30%;
}
nav {
  padding: 10px;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.cart{
  width: 40px;
  border-radius:30%;
  position:fixed;
  right: 2px;
}
.cart:hover{
  width:50px;
  border:3px solid rgb(88, 63, 23);

}
</style>
