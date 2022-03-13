<template>
  <div>
  <img class="preview-img" v-for="(item, index) in list" :src="item.src" width="600" height="400" @click="$preview.open(index, list)">
  </div>
</template>

<script>
export default {
  name: 'Album',
  data () {
    return {
      list: [{
        src: 'https://placekitten.com/600/400',
        w: 600,
        h: 400
      }, {
        src: 'https://placekitten.com/1200/900',
        w: 1200,
        h: 900
      }]
    }
  }
}
</script>
<style scoped>
.preview-img{
  margin-left: 20px;
}
</style>
