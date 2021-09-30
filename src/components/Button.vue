<template>
    <button @click="showTask()" :style="{background:color}" class="btn">{{text}}</button>
</template>

<script>
    export default {
        name:"Button",
        props:{
            text:String,
            color:String
        },
        methods:{
            showTask(){
                console.log('I am triggered');
            }
        }
    }
</script>

