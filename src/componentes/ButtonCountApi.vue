<script>
export default {
    data(){
        return {
            count:0
        }
    },


    methods:{
        increment(){
            this.count++ 
        }
    }, 
    mounted(){
        console.log('The inicial count is ${this.count}.')
    }
}
</script>

<template>
    <button @click="increment">Count is: {{ count }}</button>
</template>