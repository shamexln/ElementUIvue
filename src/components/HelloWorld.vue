<template>
  <div>
    <el-row :gutter="10">
      <el-col :md="24"  align="center">
        <label class="title">胸部电阻抗断层成像术(EIT)监测记录单</label>
      </el-col>
    </el-row>
    <el-row :gutter="10">
      <el-col :md="2"  align="left">
        <label class="title">一、患者信息</label>
      </el-col>
    </el-row>

    <el-row :gutter="10">
      <div>
        <el-col :md="1"  align="left">
          <label>床号:</label>
        </el-col>
        <el-col :md="2">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="1">
          <label>姓名:</label>
        </el-col>
        <el-col :md="2">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="1">
          <label>性别:</label>
        </el-col>
        <el-col :md="2">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>

        <el-col :md="1">
          <label>年龄:</label>
        </el-col>
        <el-col :md="2">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>

        <el-col :md="2">
          <label>住院号:</label>
        </el-col>
        <el-col :md="2">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
      </div>
    </el-row>
    <el-divider></el-divider>

    <el-row :gutter="10">
      <div>
        <el-col :md="1" align="left">
          <label >住院诊断:</label>
        </el-col>
        <el-col :md="7">
          <el-input  v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="2" >
          <label>入住ICU时间:</label>
        </el-col>
        <el-col :md="6">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
      </div>
    </el-row>

        <el-row :gutter="10">
      <div>
        <el-col :md="1" align="left">
          <label >监测时间:</label>
        </el-col>
        <el-col :md="2">
          <el-input  v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="1" >
          <label>患者体位:</label>
        </el-col>
        <el-col :md="3">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="2" >
          <label>体位持续时长:</label>
        </el-col>
        <el-col :md="3">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
      </div>
    </el-row>

     <el-row :gutter="10">
      <div>
        <el-col :md="2" align="left">
          <label >机械通气模式:</label>
           </el-col>
        <el-col :md="2">
          <el-input  v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="1" >
          <label>给氧浓度:</label>
        </el-col>
        <el-col :md="3">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
        <el-col :md="1" >
          <label>PEEP:</label>
        </el-col>
        <el-col :md="1">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
         <el-col :md="2" >
          <label>氧气饱和度:</label>
        </el-col>
        <el-col :md="3">
          <el-input v-model="input" placeholder="请输入内容"></el-input>
        </el-col>
      </div>
    </el-row>


  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

</style>
