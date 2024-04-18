<script setup>
/* eslint-disable */
</script>

<template>
    <div class="multimedia-container">
        <h2 class="multimedia-title">Мультимедиа</h2>
        <div class="multimedia-content">
            <div class="multimedia-column multimedia-column-left">
                <div class="multimedia-item">
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Android Auto icon" class="multimedia-icon" />
                        <span class="multimedia-label">Android Auto</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="AUX icon" class="multimedia-icon" />
                        <span class="multimedia-label">AUX</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Bluetooth icon" class="multimedia-icon" />
                        <span class="multimedia-label">Bluetooth</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="USB icon" class="multimedia-icon" />
                        <span class="multimedia-label">USB</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Акустика icon" class="multimedia-icon" />
                        <span class="multimedia-label">Акустика</span>
                    </div>
                </div>
            </div>
            <div class="multimedia-column">
                <div class="multimedia-item">
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Аудиоподготовка icon" class="multimedia-icon" />
                        <span class="multimedia-label">Аудиоподготовка</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Голосовое управление icon" class="multimedia-icon" />
                        <span class="multimedia-label">Голосовое управление</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Мультимедиа система с LCD-экраном icon" class="-icon" />
                        <span class="multimedia-label">Мультимедиа система с LCD-экраном</span>
                    </div>
                    <div class="multimedia-icon-wrapper">
                        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                            alt="Навигационная система icon" class="multimedia-icon" />
                        <span class="multimedia-label">Навигационная система</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.multimedia-container {
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    padding: 20px;
}

.multimedia-title {
    color: var(--text-primary-100, var(--text, #161616));
    text-align: left;
    font: 700 24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .multimedia-title {
        max-width: 100%;
    }
}

.multimedia-content {
    margin-top: 20px;
    gap: 20px;
    display: flex;
}

@media (max-width: 991px) {
    .multimedia-content {
        max-width: 100%;
        flex-direction: column;
        align-items: stretch;
        gap: 0;
    }
}

.multimedia-column {
    display: flex;
    flex-direction: column;
    line-height: normal;
    width: 31%;
    margin-left: 0;
}

.multimedia-column-left {
    width: 345px;
    margin-right: 20px;
}

@media (max-width: 991px) {
    .multimedia-column {
        width: 100%;
    }
}

.multimedia-item {
    display: flex;
    flex-grow: 1;
    padding-right: 80px;
    flex-direction: column;
    align-items: start;
    font-size: 18px;
    color: var(--text-primary-100, var(--text, #161616));
    font-weight: 400;
    line-height: 135%;
}

@media (max-width: 991px) {
    .multimedia-item {
        margin-top: 40px;
    }
}

.multimedia-icon-wrapper {
    display: flex;
    gap: 8px;
    margin-top: 12px;
}

.multimedia-icon {
    aspect-ratio: 1;
    object-fit: auto;
    object-position: center;
    width: 24px;
}

.multimedia-label {
    font-family: Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .multimedia-icon-wrapper {
        white-space: initial;
    }
}

.multimedia-column:last-child {
    width: 69%;
    margin-left: 20px;
}

@media (max-width: 991px) {
    .multimedia-column:last-child {
        width: 100%;
        max-width: 100%;
        margin-top: 40px;
    }
}</style>