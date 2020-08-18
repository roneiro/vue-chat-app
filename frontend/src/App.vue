<template>
  <div>
    <h1 class=header>
      Header Test
    </h1>
  </div>
</template>

<script>
export default {
  name: "App"  
}
</script>

<style scoped>

  @font-face {
    font-family: "CodeZ";
    src: local("CodeZ"),
    url(./fonts/code-zlyhania/CodeZlyhania-Regular.ttf) format("truetype");
  }

  .header{
    color:maroon; 
    font-family: "CodeZ";
  }

</style>