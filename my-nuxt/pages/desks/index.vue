<template>
  <div class="desks">
    To desks id
    <input type="text" name="" v-model="id" placeholder="Nhap id" id="" />
    <button @click="gotoDesk">Submit</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      id: 1,
    };
  },
  methods: {
    gotoDesk() {
      this.$router.push(`/desks/${this.id}`);
    },
  },
};
</script>

<style>
</style>