<script setup>
/* eslint-disable */
</script>

<template>
    <article class="car-description">
        <h2 class="car-description__title">Описание</h2>
        <div class="car-description__details">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/898728162d21b334e30b44c3d8664bb6f631cab53b64c05905c38cf08975bbe0?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Car icon" class="car-description__icon" />
            <span class="car-description__plate">АН 1111 НА</span>
        </div>
        <p class="car-description__text">
            Продажа Ford Edge 2016 года. Автомобиль куплен для личного использования. Почти в полной комплектации Sport
            Двигатель 2.7 Бензин 312 л.с. АКПП – полный привод AWD. Зимняя резина. Новая тормозная система. Android Auto.
            Подогрев всех сидений.
        </p>
        <div class="car-description__more">
            <span class="car-description__more-text">Показать больше</span>
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/2f900e2f13c5f9b5bf9819b743ba60ac9d837658e78977f2104968280aa7e7b0?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Expand icon" class="car-description__more-icon" />
        </div>
    </article>
</template>

<style scoped>
.car-description {
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    color: var(--text-primary-100, var(--text, #161616));
    font-weight: 400;
    padding: 20px;
}

.car-description__title {
    text-align: left;
    font: 700 24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .car-description__title {
        max-width: 100%;
    }
}

.car-description__details {
    border-radius: 4px;
    border: 1px solid rgba(7, 73, 157, 1);
    background-color: #fff;
    align-self: start;
    display: flex;
    margin-top: 20px;
    gap: 8px;
    font-size: 14px;
}

.car-description__icon {
    aspect-ratio: 0.79;
    object-fit: auto;
    object-position: center;
    width: 19px;
}

.car-description__plate {
    font-family: Proxima Nova, sans-serif;
    margin: auto 0;
    padding-right: 5px;
}

.car-description__text {
    margin-top: 20px;
    font: 18px/24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .car-description__text {
        max-width: 100%;
    }
}

.car-descriptionmore {
    align-self: center;
    display: flex;
    margin-top: 12px;
    gap: 4px;
    font-size: 16px;
    text-align: center;
}

.car-description__more {
    font-family: Proxima Nova, sans-serif;
    margin: 10px auto 0;
}

.car-description__more-icon {
    aspect-ratio: 1;
    object-fit: auto;
    object-position: center;
    width: 24px;
}</style>