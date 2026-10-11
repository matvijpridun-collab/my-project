<template>
    <header> 
        <h1> {{ title }} </h1>
    </header>
    </template>


    <script>
    export default {
        name: 'HeaderComponent',
        props: {
            title: {
                type: String,
                required: true
            }
        }
    }
    </script>


    <style scoped>
    header {
        background-color: #0d0d0e;
        color: #ffffff;
        padding: 20px;
        text-align: center;
        font-size: 24px;
        font-weight: bold;
    }
</style>