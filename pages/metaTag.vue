<script>
export default {
  // 第一種物件
  // head: {
  //   title: 'lifecycle',
  //   meta: [
  //     {
  //       hid: 'description',
  //       name: 'description',
  //       content: 'lifecycle page '
  //     }
  //   ],
  //   script: [
  //     { src: 'JS檔案路徑' }
  //   ],
  // },

  // 第二種函式 可以跟資料連動
  head(){
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'lifecycle page '
        }
      ],
      script: [
        { src: 'JS檔案路徑' }
      ],
    }
  },
  data(){
    return{ 
      title : "curry白爛貓"
    }
  },
};
</script>
<template>
  <div>
    <h2>This is an metaTag</h2>
  </div>
</template>
<style lang='scss' scoped>
h4 {
  font-size: 40px;
  color: red;
}
</style>

