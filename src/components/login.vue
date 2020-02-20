<template>
  <div class="login_wrapper">
    <el-form :model="loginRuleForm" :rules="loginRuleFormRules" ref="loginRuleForm" label-width="100px" class="demo-ruleForm">
      <el-form-item label="活动名称" prop="name">
        <el-input v-model="loginRuleForm.name"></el-input>
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  components: {},
  props: {},
  data () {
    return {
      loginRuleForm: {
        username: 'admin',
        password: 123456
      },
      loginRuleFormRules: {}
    }
  },
  watch: {},
  computed: {},
  methods: {},
  created () {},
  mounted () {}
}
</script>
<style lang="less" scoped>
  .login_wrapper{}
</style>
