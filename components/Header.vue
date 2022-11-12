<script>
export default {
  data() {
    return {
    };
  },
};
</script>
<template>
  <nav>
    <NuxtLink class="Title" to="/">index</NuxtLink>
    <NuxtLink to="/about">about</NuxtLink>
    <NuxtLink to="/async">async</NuxtLink>
    <NuxtLink to="/fetch">fetch</NuxtLink>
    <NuxtLink to="/lifecycle">lifecycle</NuxtLink>
    <NuxtLink to="/metaTag">metaTag</NuxtLink>
  </nav>
</template>
<style lang='scss' scoped>
a {
  display: inline-block;
  padding: 20px 10px;
  text-decoration: none;
  font-size: 24px;
  color: aqua;
}
</style>

