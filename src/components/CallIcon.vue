<script setup>
/* eslint-disable */
</script>

<template>
    <div class="container">
        <div class="icon-container">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/8a53d55638d76db5480a7311d4271dfda9589774e4a9bc0836967109959356c5?apiKey=9c541dfc93764c3c87ea7e394d1d154c&"
                alt="Icon" class="icon-image" />
        </div>
        <div class="wrap"></div>

    </div>
</template>

<style scoped>
.container {

    position: absolute;
    top: 0;
    left: 90%;
    width: 60px;

}

.wrap {
    min-height: 6000px;
}

.icon-container {
    position: sticky;
    top: 250px;
    width: 60px;
    height: 60px;
    padding: 14px;
    border-radius: 30px;
    background-color: var(--Secondary-active, #40a600);
    cursor: pointer;

}

.icon-image {
    width: 32px;
    margin: 0;
    aspect-ratio: 1;
    object-fit: contain;
    object-position: center;
}
</style>