<template>
       <div class="home">
              <img alt="Vue logo" src="../assets/logo.png" />
              <h1>Hola Mundo</h1>
              <button @click="goToDayBook" class="btn btn-warning">
                     primary
              </button>
              <button class="btn btn-danger">primary</button>
       </div>
</template>

<script>
export default {
       methods: {
              goToDayBook() {
                     this.$router.push({ name: "no-entry" });
              },
       },
};
</script>
