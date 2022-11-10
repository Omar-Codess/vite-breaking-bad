<script>
import AppTitle from "../src/components/AppTitle.vue";
import AppMain from "../src/components/AppMain.vue";

export default{
  components: {
    AppTitle,
    AppMain
  }
}
</script>


<template>
<AppTitle />
<AppMain />
</template>

<style>
  body{
    background-color: #2e3a46;
  }
</style>
