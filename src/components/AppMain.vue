<script>

</script>

<template>
    <button class="p-absolute">Select category</button>
    <div class="app-wrapper p-relative">
        <div class="container">

        </div>
    </div>

</template>

<style>
    button{
        left: 90px;
        bottom: 450px;
    }

    .p-absolute{
        position: absolute;
    }

    .p-relative{
        position: relative;
    }

    .app-wrapper{
        display: flex;
        justify-content: center;
        align-items: flex-end;
        width: 100%;
        height: 100vh;
        
    }

    .container{
        border: 1px solid;
        width: 80%;
        height: 70%;
    }
</style>
