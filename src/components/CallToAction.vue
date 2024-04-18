<script setup>
/* eslint-disable */
</script>

<template>
    <section class="call-to-action">
        <h2 class="call-to-action__title">Оставьте заявку и мы вам перезвоним</h2>
        <button class="call-to-action__button">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/c95e8e39d101f0ccc83e273c615ecf0a6a2aff49c875d3c9140aa07acf419071?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="" class="call-to-action__icon" />
            <span class="call-to-action__text">Заказать звонок</span>
        </button>
    </section>
</template>

<style scoped>
.call-to-action {
    display: flex;
    flex-direction: column;
    max-width: 445px;
    text-align: center;
    font-weight: 700;
    margin: 0 auto;
}

.call-to-action__title {
    width: 100%;
    color: #e73a3f;
    font: 700 22px Proxima Nova, sans-serif;
}

.call-to-action__button {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    margin-top: 20px;
    padding: 8px 20px;
    color: var(--Text-secondary, #fff);
    background-color: #e73a3f;
    border-radius: 4px;
    font: 700 16px Proxima Nova, sans-serif;
    gap: 4px;
    cursor: pointer;
}

.call-to-action__icon {
    width: 24px;
    aspect-ratio: 1;
    object-fit: contain;
    object-position: center;    
}
</style>