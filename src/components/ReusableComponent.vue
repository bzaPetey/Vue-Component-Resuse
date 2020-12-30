<template>
  <div class="reuse-me" v-for="person in names" :key="person.id">
    <MyComp :person="person" />
  </div>
</template>


<script>
import MyComp from "./MyComp.vue";

export default {
  name: "ReusableCompoent",
  components: {
    MyComp,
  },

  data() {
    return {
      names: [
        { id: 1, name: "Sam" },
        { id: 2, name: "Dean" },
        { id: 3, name: "Bobby" },
      ],
    };
  },
};
</script>


<style scoped>
.reuse-me {
  margin: 1rem 2rem;
  color: black;
}
</style>