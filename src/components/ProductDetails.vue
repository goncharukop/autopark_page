<template>
    <div class="product-details">
        <nav class="breadcrumb">
            <a href="#" class="breadcrumb-link">Главная</a>
            <span class="breadcrumb-separator">/</span>
            <a href="#" class="breadcrumb-link">Купить</a>
            <span class="breadcrumb-separator">/</span>
            <a href="#" class="breadcrumb-link">Автомобили Ford</a>
            <span class="breadcrumb-separator">/</span>
            <span class="breadcrumb-current">Ford Edge 2016 - Код товара: 40845</span>
        </nav>
        <div class="product-info">
            <a href="#" class="info-link">Все про авто</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Характеристики</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Дополнительно</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Салон</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Оптика</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Кузов</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Система помощи при парковке</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Безопасность</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Мультимедиа</a>
            <span class="info-separator"></span>
            <a href="#" class="info-link">Отзывы</a>
        </div>
    </div>
</template>

<style scoped>
.product-details {
    display: flex;
    flex-direction: column;
    font-size: 16px;
    color: var(--text-primary-100, var(--text, #161616));
    font-weight: 400;
    text-align: center;
}

.breadcrumb {
    align-self: start;
    display: flex;
    gap: 4px;
    padding: 0 20px;
}

@media (max-width: 991px) {
    .breadcrumb {
        flex-wrap: wrap;
    }
}

.breadcrumb-link,
.breadcrumb-current {
    font-family: Proxima Nova, sans-serif;
}

.breadcrumb-separator {
    font-family: Proxima Nova, sans-serif;
}

.product-info {
    display: flex;
    margin-top: 20px;
    gap: 7px;
    padding: 0 20px;
}

@media (max-width: 991px) {
    .product-info {
        flex-wrap: wrap;
    }
}

.info-link {
    font-family: Proxima Nova, sans-serif;
}

.info-separator {
    border: 1px solid rgba(187, 187, 187, 0.4);
    background-color: rgba(187, 187, 187, 0.4);
    width: 1px;
    height: 20px;
}
</style>