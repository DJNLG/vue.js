<template>

  <div class="hello">
    <!--<h2>{{view()}}</h2>-->
    <!--<input type="checkbox" v-model="class1"/>修改颜色-->
    <!--<div v-bind:class="{'class1':class1}" >-->
      <!--changebackgroun-->
    <!--</div>-->
    <!--<div v-if="Math.random()>0.5">    right-->
    <!--</div>-->
  </div>
</template>

<script>
export default {
  name: 'HeloWorld',
  data () {
    return {
      Object: {
        name: '菜鸟教程',
        url: 'http://www.runoob.com',
        slogan: '学的不仅是技术，更是梦想！'
      },
      msg: 'HELLO，WORLD',
      class1: false,
      seen: true
    }
  },
  methods: {
    deatail: function () {
      return this.msg
    },
    view: function () {
      return this.msg.slice(1)
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
