<script setup>
/* eslint-disable */
</script>

<template>
    <header class="main-header">
        <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/e89fe9355976ae7ee19973447e6cc53adb751bd8a59f1457ab4fe932fb0b52c3?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
            alt="Company Logo" class="company-logo" />
        <nav class="main-nav">
            <a href="#" class="nav-link">Купить</a>
            <a href="#" class="nav-link">Продать</a>
            <a href="#" class="nav-link">Услуги</a>
            <a href="#" class="nav-link">Блог</a>
            <a href="#" class="nav-link">Вакансии</a>
            <a href="#" class="nav-link">Контакты</a>
        </nav>
        <button class="login-button">Войти</button>
    </header>
</template>

<style scoped>
.main-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 20px;
    background-color: var(--Text-secondary, #fff);
    box-shadow: 0px 4px 9px 2px rgba(22, 22, 22, 0.1);
    font-size: 16px;
    text-align: center;
}

@media (max-width: 991px) {
    .main-header {
        flex-wrap: wrap;
    }
}

.company-logo {
    width: 270px;
    max-width: 100%;
    object-fit: auto;
    object-position: center;
    aspect-ratio: 5.26;
}

.main-nav {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 16px;
    color: var(--text-primary-100, var(--text, #161616));
    font-weight: 400;
    font-family: Proxima Nova, sans-serif;
}

@media (max-width: 991px) {
    .main-nav {
        white-space: initial;
    }
}

.nav-link {
    color: inherit;
    text-decoration: none;
}

.login-button {
    padding: 17px 20px;
    border: none;
    border-radius: 4px;
    background-color: var(--Primary-active, #e73a3f);
    color: var(--Text-secondary, #fff);
    font-weight: 700;
    font-family: Proxima Nova, sans-serif;
    cursor: pointer;
}

@media (max-width: 991px) {
    .login-button {
        white-space: initial;
    }
}
</style>