<template>
  <header>
    <div :class="$style.Banner">
      <img src="../../assets/image/banner.jpg" alt="Background_Header">
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      
    }
  }
}
</script>


<style lang="scss" module>
  @import './header';

  /* h1, h2 {
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
  } */
</style>
