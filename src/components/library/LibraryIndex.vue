<template>
  <el-container>
    <el-aside style="width: 200px;margin-top: 20px">
      <switch></switch>
<SideMenu></SideMenu>
    </el-aside>
    <el-main>
    <Books class="books-area"></Books>

    </el-main>
  </el-container>
</template>

<script>
 import SideMenu from './SideMenu'
import Books from './Books'
 export default {
    name: 'AppLibrary',
    components: {Books, SideMenu}
  }
</script>
<style scoped>
  .books-area {
    width: 990px;
    margin-left: auto;
    margin-right: auto;
  }
</style>

