<template>
    <el-dropdown>
      <el-button type="primary">
        Dropdown List<el-icon class="el-icon--right"><arrow-down /></el-icon>
      </el-button>
      <template #dropdown>
        <el-dropdown-menu>
          <el-dropdown-item>Action 1</el-dropdown-item>
          <el-dropdown-item disabled>Action 2</el-dropdown-item>
        </el-dropdown-menu>
      </template>
    </el-dropdown>
</template>

<script lang='ts'>

export default {
    name: '',
    setup() {

        return { }
    },
};
</script>

<style scoped>

</style>