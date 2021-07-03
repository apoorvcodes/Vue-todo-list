<template>
  <router-view />

  <todolist />
</template>

<style lang="scss"></style>

<script>
import todolist from "./components/todolist.vue";
export default {
  components: { todolist },
};
</script>
