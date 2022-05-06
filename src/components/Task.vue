<template>
<div class="task">
<h3>{{task.title}}   
<i class="fas fa-times "></i>

</h3>
<p>{{task.description}}</p>    </div>
</template>
<script>
export default{
name:'Task',
props:{
  task:Object,
},
}
</script>
<style scoped>
.task{
    background-color: #f5f5f5;
  padding:20px;
  border:1px solid #ccc;
  margin-bottom:20px;
  border-radius:4px;
}

</style>>
