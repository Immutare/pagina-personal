<template lang="html">
<div class="centrar">
  <img class="diamond" src="/static/images/perfil.jpg" alt="image">
</div>
</template>

<script>
export default {
}
</script>

<style lang="scss">
.centrar{
  margin: 0 auto;
  position: absolute;
  left: 35vw;
  top: 90vh;
  height:17vw;

  .diamond {
    max-width: 30vw;
    -webkit-clip-path: polygon(50% 0, 100% 50%, 50% 100%, 0 50%);
    clip-path: polygon(50% 0, 100% 50%, 50% 100%, 0 50%);
    transition: 1s;
    &:hover {
    -webkit-clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
    }
  }
}


</style>
