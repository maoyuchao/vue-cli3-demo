<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div>{{aaa}}</div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      aaa: '123'
    }
  },
  created(){
    this.getData();
  },
  methods:{
    getData(){
      console.log(123)
    }
  }
}
</script>
