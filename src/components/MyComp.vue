<template>
  <p class="person">{{person.name}}</p>
</template>



<script>
export default {
  name: "MyComp",
  props: {
    person: {
      Object,
      required: true,
    },
  },
};
</script>



<style scoped>
.person {
  padding: 1rem;
  color: antiquewhite;
  background-color: darkgreen;
}
</style>