<template>
  <div id="Home">
    <el-container>
        <commonHeader/>
    </el-container>
  </div>
</template>

<script>
import CommonHeader from '@/components/CommonHeader'
export default {
  name: 'Home',
  data () {
    return {
      placeHolder: 'this is Home'
    }
  },
  components: {
    'commonHeader': CommonHeader
  }
}
</script>

<style scoped>
</style>
