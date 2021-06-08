<template>
  <div class="desks-id">This is desks {{ $route.params.id }}</div>
</template>

<script>
export default {
  validate(context) {
    return context.params.id;
  },
};
</script>

<style>
</style>