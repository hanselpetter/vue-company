<template>
  <div>
    <h5>Options</h5>
    <p>We could retrieve the product options from id {{ id }}</p>
  </div>
</template>

<script>
export default {
  name: "OptionsComponent",
  props: ["id"],
  created() {
    //console.log("Options", this.id);
  },
  //to, from
  beforeRouteUpdate() {
    console.log("Component guard - beforeRouteUpdate");
  },
};
</script>

<style scoped></style>
