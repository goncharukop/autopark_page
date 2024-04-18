<script setup>
/* eslint-disable */
import { ref, computed } from 'vue';

const images = ref([
    { src: 'https://cdn.builder.io/api/v1/image/assets/TEMP/da7112dcea707a9f074074d00513284c38f340a9acae293b82042fdba4d71fab?apiKey=941722781dcd4bc79a2c09d8279b9fb0&', text: '1AAAXXXXXXXXXXXXX' },
    { src: 'https://cdn.builder.io/api/v1/image/assets/TEMP/26659cd95c3413c93d37ae30f37b05d60299fcb4509ee7633199c2409b1803cb?apiKey=941722781dcd4bc79a2c09d8279b9fb0&',text: 'tnban4ne3lb007941' }
]);

const currentIndex = ref(0);

const currentImage = computed(() => images.value[currentIndex.value].src);
const currentText = computed(() => images.value[currentIndex.value].text);

function changeImage() {
    currentIndex.value = (currentIndex.value + 1) % images.value.length;
}
</script>

<template>
    <section class="characteristics">
        <h2 class="characteristics__title">Характеристики</h2>
        <div class="characteristics__content">
            <div class="characteristics__columns">
                <div class="characteristics__column characteristics__column-left">
                    <div class="characteristics__details characteristics__item">            
                        <div class="characteristics__vin">
                            <div class="characteristics__vin-label">VIN-код:</div>
                            <div class="characteristics__vin-value">{{ currentText }}</div>
                        </div>
                        <img :src="currentImage" alt="Characteristics icon" class="characteristics__icon" @click="changeImage" style="cursor: pointer;">
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Растаможено:</div>
                        <div class="characteristics__value">ДА</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Страна регистрации:</div>
                        <div class="characteristics__value">Украина</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Техническое состояние:</div>
                        <div class="characteristics__value">Идеальное</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Тип кузова:</div>
                        <div class="characteristics__value">Внедорожник / Кроссовер</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Год выпуска:</div>
                        <div class="characteristics__value">2016</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Пробег:</div>
                        <div class="characteristics__value">180 000 км</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Коробка передач:</div>
                        <div class="characteristics__value">Автомат</div>
                    </div>
                    <div class="characteristics__item">
                        <div class="characteristics__label">Руль:</div>
                        <div class="characteristics__value">Левый</div>
                    </div>
                </div>
                <div class="characteristics__column">
                    <div class="characteristics__list">
                        <div class="characteristics__item">
                            <div class="characteristics__label">Объем двигателя:</div>
                            <div class="characteristics__value">2,7 л</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Топливо:</div>
                            <div class="characteristics__value">Бензин</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Мощность двигателя, л.с.:</div>
                            <div class="characteristics__value">315</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Количество дверей:</div>
                            <div class="characteristics__value">5</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Количество мест:</div>
                            <div class="characteristics__value">5</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Цвет кузова:</div>
                            <div class="characteristics__value">Белый</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Цвет салона:</div>
                            <div class="characteristics__value">Черный</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Салон отделка:</div>
                            <div class="characteristics__value">Кожа</div>
                        </div>
                        <div class="characteristics__item">
                            <div class="characteristics__label">Колесная формула:</div>
                            <div class="characteristics__value">4x4</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.characteristics {
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    padding: 20px;
}

.characteristics__title {
    color: var(--text-primary-100, var(--text, #161616));
    text-align: left;
    font: 700 24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .characteristics__title {
        max-width: 100%;
    }
}

.characteristics__content {
    margin-top: 20px;
}

@media (max-width: 991px) {
    .characteristics__content {
        max-width: 100%;
        padding-right: 20px;
    }
}

.characteristics__columns {
    gap: 20px;
    display: flex;
}

@media (max-width: 991px) {
    .characteristics__columns {
        flex-direction: column;
        align-items: stretch;
        gap: 0;
    }
}

.characteristics__column {
    display: flex;
    flex-direction: column;
    line-height: normal;
    width: 61%;
    margin-left: 0;
}

.characteristics__column-left {
    width: 345px;
    margin-right: 20px;
}

@media (max-width: 991px) {
    .characteristics__column {
        width: 100%;
    }
}

.characteristics__details {
    display: flex;
    flex-grow: 1;
    font-size: 16px;
    font-weight: 400;
    line-height: 1;
}

@media (max-width: 991px) {
    .characteristics__details {
        margin-top: 40px;
    }
}

.characteristics__list {
    display: flex;
    flex-grow: 1;
    flex-direction: column;
    font-size: 16px;
    font-weight: 400;
    line-height: 135%;
}

.characteristics__vin {
    display: flex;
    width: 245px;
    gap: 8px;
    font-size: 14px;
    border-radius: 4px;
    border: 1px solid rgba(7, 73, 157, 1);
}

.characteristics__vin-label {
    font-family: Proxima Nova, sans-serif;
    background-color: #07499d;
    color: var(--Text-secondary, #fff);
    justify-content: center;
    padding: 12px 8px;
}

.characteristics__vin-value {
    color: var(--text-primary-100, var(--text, #161616));
    font-family: Proxima Nova, sans-serif;
    text-transform: uppercase;
    margin: auto 0;
}

.characteristics__icon {
    aspect-ratio: 1;
    object-fit: auto;
    object-position: center;
    width: 24px;
}

.characteristics__item {
    display: flex;
    margin-top: 12px;
    gap: 8px;
    white-space: nowrap;
}

@media (max-width: 991px) {
    .characteristics__item {
        white-space: initial;
    }
}

.characteristics__label {
    color: rgba(22, 22, 22, 0.7);
    font-family: Proxima Nova, sans-serif;
}

.characteristics__value {
    color: var(--text-primary-100, var(--text, #161616));
    font-family: Proxima Nova, sans-serif;
}
</style>