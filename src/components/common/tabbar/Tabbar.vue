<template>
  <div id="tabbar">
    <slot></slot>
  </div>
</template>

<script>

export default {
  name: "tabbar",

}
</script>

<style scoped>

#tabbar{
  display:flex;
  background-color: beige;

  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;

}


</style>
