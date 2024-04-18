<script setup>
/* eslint-disable */
</script>

<template>
    <div class="additional-options">
        <h2 class="title">Дополнительные опции</h2>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Кондиционер" class="icon" />
            <div class="label">Кондиционер:</div>
            <div class="value">Климат-контроль 2-зонный</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Электростеклоподъёмники" class="icon" />
            <div class="label">Электростеклоподъёмники:</div>
            <div class="value">Передние и задние</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Усилитель руля" class="icon" />
            <div class="label">Усилитель руля:</div>
            <div class="value">Электро</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Регулировка руля" class="icon" />
            <div class="label">Регулировка руля:</div>
            <div class="value">По высоте и по вылету</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Запасное колесо" class="icon" />
            <div class="label">Запасное колесо:</div>
            <div class="value">Полноразмерное</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Фары" class="icon" />
            <div class="label">Фары:</div>
            <div class="value">Ксеноновые/Биксеноновые</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Регулировка сидений салона по высоте" class="icon" />
            <div class="label">Регулировка сидений салона по высоте:</div>
            <div class="value">Электрорегулировка передних сидений</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Память положения сидения" class="icon" />
            <div class="label">Память положения сидения:</div>
            <div class="value">Передние сиденья</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Подогрев сидений" class="icon" />
            <div class="label">Подогрев сидений:</div>
            <div class="value">Передние и задние сиденья</div>
        </div>
        <div class="option">
            <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                alt="Вентиляция сидений" class="icon" />
            <div class="label">Вентиляция сидений:</div>
            <div class="value">Передние сиденья</div>
        </div>
    </div>
</template>

<style scoped>
.additional-options {
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    align-items: start;
    font-size: 18px;
    font-weight: 400;
    line-height: 135%;
    padding: 20px;
}

.title {
    color: var(--text-primary-100, var(--text, #161616));
    text-align: left;
    font: 700 24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .title {
        max-width: 100%;
    }
}

.option {
    display: flex;
    margin-top: 12px;
    gap: 8px;
}

@media (max-width: 991px) {
    .option {
        flex-wrap: wrap;
    }
}

.icon {
    width: 24px;
    height: 24px;
    object-fit: auto;
    object-position: center;
}

.label {
    color: rgba(22, 22, 22, 0.7);
    font-family: Proxima Nova, sans-serif;
}

.value {
    color: var(--text-primary-100, var(--text, #161616));
    font-family: Proxima Nova, sans-serif;
}</style>