<template>
    <header class="header">
        <div class="container">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/Yu-Gi-Oh%21_%28Logo%29.jpg/800px-Yu-Gi-Oh%21_%28Logo%29.jpg"
                alt="Yu-Gi-Oh! Logo" class="logo" />
            <span class="title">YU-GI-HO API</span>
        </div>
    </header>
</template>
  
<script>
export default {

};
</script>
  
<style lang="scss" scoped>
.header {
    width: 100%;
    background-color: white;
    color: black;

    .container {
        padding: 50px 0;
        text-align: center;
    }


    .title {
        font-size: 24px;
        font-weight: bold;
    }
}

img {
    width: 50%;
    position: relative;
    left: 300px;
}
</style>
  