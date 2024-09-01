<template>
    <button @click="count++">
        Count is: {{ count }} 
    </button>
</template>

<script>
export default {
    data() {
        return {
            count: 0
        }
    }
}
</script>


<style scoped>
button {
    font-weight: bold;
    background-color: #4CAF50;
    color: white;
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

/* .button {
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
} */
</style>