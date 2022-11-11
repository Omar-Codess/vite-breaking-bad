<script>

</script>

<template>
    <button class="p-absolute">Select category</button>
    <div class="app-wrapper p-relative">
        <div class="container">
            <div class="results-bar">
                <p>Found 62 characters</p>
            </div>
            <div class="cards">
                <div class="card">

                </div>
                <div class="card">

                </div>
                <div class="card">

                </div>
                <div class="card">

                </div>
                <div class="card">

                </div>
            </div>
        </div>
    </div>
</template>

<style>
    button{
        left: 180px;
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
        background-color: white;
    }

    .results-bar{
        color: white;
        height: 50px;
        width: 90%;
        background-color: #212529;
        display: flex;
        align-items: center;
        margin: 0 auto;
        margin-top: 1em;
    }

    .cards{
        width: 100%;
        display: flex;
        justify-content: space-around;
    }

    .card{
        height: 300px;
        width: calc(100% / 5 - 20px);
        border: 1px solid;
        margin-top: 20px;
    }
</style>
