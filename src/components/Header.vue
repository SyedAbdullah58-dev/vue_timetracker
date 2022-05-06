<template>
    <header>
<h1>{{title}}</h1>
<Button text="Add Tasks" color="grey"></Button>
    </header>
</template>
<script>
import Button from './Button.vue'

export default{
    components:{
     Button
       
    },
    name:"Header",
    props:{
        title:{
type:String,
default:"Task Tracko"

        }
    }
}
</script>
<style scoped>
header{
display: flex;
justify-content: space-between;
}
</style>