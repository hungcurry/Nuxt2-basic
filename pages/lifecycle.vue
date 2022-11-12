<script>
export default {
  data(){
    return{ }
  },
  asyncData(){
    console.log(1 , "asyncData");
  },
  beforeCreate(){
    console.log(2 , "beforeCreate");
  },
  created(){
    console.log(3 , "created");
  },
  fetch(){
    console.log(4 , "fetch");
  },
  mounted(){
    console.log(5 , "mounted");
  },
};
</script>
<template>
  <div>
    <h2>This is an lifecycle</h2>
  </div>
</template>
<style lang='scss' scoped>
h4 {
  font-size: 40px;
  color: red;
}
</style>

