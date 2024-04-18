<script setup>
/* eslint-disable */
</script>

<template>
    <main class="parking-assistance">
        <h2 class="parking-assistance__title">Система помощи при парковке</h2>
        <div class="parking-assistance__features">
            <div class="feature feature-left">
                <div class="feature__item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Rear camera icon" class="feature__icon" />
                    <span class="feature__label">Задняя камера</span>
                </div>
                <div class="feature__item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Rear parking sensor icon" class="feature__icon" />
                    <span class="feature__label">Парктроник задний</span>
                </div>
                <div class="feature__item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Front parking sensor icon" class="feature__icon" />
                    <span class="feature__label">Парктроник передний</span>
                </div>
            </div>
            <div class="feature">
                <div class="feature__item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Front camera icon" class="feature__icon" />
                    <span class="feature__label">Передняя камера</span>
                </div>
                <div class="feature__item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Automatic parking system icon" class="feature__icon" />
                    <span class="feature__label">Система автоматической парковки</span>
                </div>
            </div>
        </div>
    </main>
</template>

<style scoped>
.parking-assistance {
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    padding: 20px;
}

.parking-assistance__title {
    color: #161616;
    text-align: left;
    font: 700 24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .parking-assistance__title {
        max-width: 100%;
    }
}

.parking-assistance__features {
    display: flex;
    margin-top: 20px;
    padding-right: 80px;
    gap: 20px;
    font-size: 18px;
    font-weight: 400;
    line-height: 135%;
}

@media (max-width: 991px) {
    .parking-assistance__features {
        flex-wrap: wrap;
        padding-right: 20px;
    }
}

.feature {
    display: flex;
    flex-direction: column;
    color:  #161616;
}

.feature-left {
    width: 345px;
    margin-right: 20px;
}

.feature__item {
    display: flex;
    align-items: center;
    gap: 8px;
    margin-top: 12px;
}

.feature__icon {
    width: 24px;
    height: 24px;
    object-fit: contain;
}

.feature__label {
    font-family: Proxima Nova, sans-serif;
}
</style>