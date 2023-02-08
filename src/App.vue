<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <el-popover :width="550" trigger="click">
		<template #reference>
			<el-input placeholder="请输入"></el-input>
		</template>
		<el-select multiple placeholder="Select">
			<el-option key="1" label="label1" value="v1" />
      <el-option key="2" label="label2" value="v2" />
      <el-option key="3" label="label3" value="v3" />
		</el-select>
	</el-popover>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
