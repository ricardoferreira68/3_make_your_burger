<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
    
}
</script>

<style scoped>
#main-banner {
    background-image: url("/public/img/burger.png");
    background-position: 0;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

#main-banner h1 {
    color: #fff;
    text-align: center;
    font-size: 40px;
    background-color: #222;
    padding: 10px 20px;
}
</style>