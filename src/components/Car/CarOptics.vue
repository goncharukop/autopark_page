<script setup>
/* eslint-disable */
</script>

<template>
    <section class="optics-section">
        <h2 class="section-title">Оптика</h2>
        <div class="features-container">
            <div class="feature feature-left">
                <div class="feature-item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Датчик света" class="feature-icon" />
                    <p class="feature-text">Датчик света</p>
                </div>
                <div class="feature-item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Дневные ходовые огни" class="feature-icon" />
                    <p class="feature-text">Дневные ходовые огни</p>
                </div>
            </div>
            <div class="feature">
                <div class="feature-item">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/59327d19b328a2eaec39751b64d742e3771d8bde573c04ef674128852573c1c4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
                        alt="Противотуманные фары" class="feature-icon" />
                    <p class="feature-text">Противотуманные фары</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.optics-section {
    border-radius: 8px;
    display: flex;
    flex-direction: column;
    padding: 20px;
}

.section-title {
    color: var(--text-primary-100, var(--text, #161616));
    text-align: left;
    font: 700 24px Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .section-title {
        max-width: 100%;
    }
}

.features-container {
    display: flex;
    margin-top: 20px;
    padding-right: 80px;
    gap: 20px;
    font-size: 18px;
    font-weight: 400;
    line-height: 135%;
}

@media (max-width: 991px) {
    .features-container {
        flex-wrap: wrap;
        padding-right: 20px;
    }
}

.feature {
    display: flex;
    flex-direction: column;
    color: var(--text-primary-100, var(--text, #161616));
}

.feature-left {
    width: 345px;
    margin-right: 20px;
}

.feature-item {
    display: flex;
    gap: 8px;
    margin-top: 12px;
}

.feature-icon {
    width: 24px;
    height: 24px;
    object-fit: contain;
}

.feature-text {
    font-family: Proxima Nova, sans-serif;
}

.feature:last-child {
    align-self: start;
    color: var(--logo-black, #000);
}
</style>