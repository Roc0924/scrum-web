<template>
  <div id="Home">
    <el-container>
        <commonHeader/>
    </el-container>
    <!--<test/>-->
  </div>
</template>

<script>
import CommonHeader from '@/components/CommonHeader'
import Test from '@/components/Test'
export default {
  name: 'Home',
  data () {
    return {
      placeHolder: 'this is Home'
    }
  },
  components: {
    'commonHeader': CommonHeader,
    'test': Test
  }
}
</script>

<style scoped>
</style>
