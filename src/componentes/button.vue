<template>
    <button class="button"> 
        {{ label }}
    </button>
</template>

<script>
export default {
    props: {
        label:{
            type:String,
            required:true
        }
    }, 
    methods:{
        handleClick(){

        }
    }
}
</script>

<style scoped>

.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

</style>