<script setup>
/* eslint-disable */
</script>

<template>
    <footer class="footer">
        <div class="footer-content">
            <div class="footer-logo">
                <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/d82f35ae4b434faa1ac21d6b2f97561f5feb92ec981260e3f044023ee57646f0?apiKey=9c541dfc93764c3c87ea7e394d1d154c&"
                    alt="Company Logo" class="logo-image" />
                <div class="logo-text">
                    <img src="https://cdn.builder.io/api/v1/image/assets/TEMP/d4a62d355c3776503e446e61ac4551535f36cb5de1c350cfea7471aca5885cac?apiKey=9c541dfc93764c3c87ea7e394d1d154c&"
                        alt="Linktree Icon" class="linktree-icon" />
                    <span class="linktree-text">Лінктрі</span>
                </div>
                <div class="copyright">© 2023 Autopark.ua</div>
            </div>
            <nav class="footer-nav">
                <div class="nav-column">
                    <a href="#" class="nav-link buy-link">Купить</a>
                    <a href="#" class="nav-link">Продать</a>
                    <a href="#" class="nav-link">Trade-In</a>
                    <a href="#" class="nav-link">Кредит</a>
                    <a href="#" class="nav-link">Страхування</a>
                </div>
                <div class="nav-column">
                    <a href="#" class="nav-link">Шины и запчасти</a>
                    <a href="#" class="nav-link">Новости</a>
                    <a href="#" class="nav-link">Блог</a>
                    <a href="#" class="nav-link">Отзывы</a>
                    <a href="#" class="nav-link">О нас</a>
                </div>
                <div class="nav-column">
                    <div class="nav-heading">Автосалон Винница</div>
                    <a href="#" class="nav-link">Trade-In Винница</a>
                    <a href="#" class="nav-link car-selection-link">Автоподбор Винница</a>
                    <a href="#" class="nav-link">Продажа авто Винница</a>
                    <a href="#" class="nav-link">Выкуп авто Винница</a>
                    <a href="#" class="nav-link">Кредит Винница</a>
                </div>
                <div class="nav-column">
                    <div class="nav-heading">Автосалон Харьков</div>
                    <a href="#" class="nav-link">Trade-In Харьков</a>
                    <a href="#" class="nav-link">Автоподбор Харьков</a>
                    <a href="#" class="nav-link">Продажа авто Харьков</a>
                    <a href="#" class="nav-link">Выкуп авто Харьков</a>
                    <a href="#" class="nav-link">Кредит Харьков</a>
                </div>
                <div class="nav-column">
                    <div class="nav-heading">Автосалон Одесса</div>
                    <a href="#" class="nav-link">Trade-In Одесса</a>
                    <a href="#" class="nav-link">Автоподбор Одесса</a>
                    <a href="#" class="nav-link">Продажа авто Одесса</a>
                    <a href="#" class="nav-link">Выкуп авто Одесса</a>
                    <a href="#" class="nav-link">Кредит Одесса</a>
                </div>
                <div class="nav-column">
                    <div class="nav-heading">Автосалон Львов</div>
                    <a href="#" class="nav-link">Trade-In Львов</a>
                    <a href="#" class="nav-link">Автоподбор Львов</a>
                    <a href="#" class="nav-link">Продажа авто Львов</a>
                    <a href="#" class="nav-link">Выкуп авто Львов</a>
                    <a href="#" class="nav-link">Кредит Львов</a>
                </div>
                <div class="nav-column">
                    <div class="nav-heading">Автосалон Запорожье</div>
                    <a href="#" class="nav-link">Trade-In Запорожье</a>
                    <a href="#" class="nav-link">Автоподбор Запорожье</a>
                    <a href="#" class="nav-link">Продажа авто Запорожье</a>
                    <a href="#" class="nav-link">Выкуп авто Запорожье</a>
                    <a href="#" class="nav-link">Кредит Запорожье</a>
                </div>
            </nav>
        </div>
    </footer>
</template>

<style scoped>
.footer {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #ffffff;
    max-width: 1920px;
    margin: 0 auto;
    font-weight: 400;
    padding: 50px 60px;
}

@media (max-width: 991px) {
    .footer {
        padding: 0 20px;
    }
}

.footer-content {
    display: flex;
    gap: 20px;
    justify-content: space-between;
}

@media (max-width: 991px) {
    .footer-content {
        flex-wrap: wrap;
    }
}

.footer-logo {
    align-items: center;
    align-self: start;
    display: flex;
    flex-direction: column;
}

.logo- {
    aspect-ratio: 5.26;
    object-fit: auto;
    object-position: center;
    width: 162px;
}

.logo-text {
    justify-content: center;
    align-self: stretch;
    display: flex;
    margin-top: 16px;
    gap: 8px;
    font-size: 14px;
    color: var(--text-primary-100, var(--text, #161616));
    white-space: nowrap;
}

@media (max-width: 991px) {
    .logo-text {
        white-space: initial;
    }
}

.linktree-icon {
    aspect-ratio: 5;
    object-fit: auto;
    object-position: center;
    width: 79px;
    align-self: start;
}

.linktree-text {
    font-family: Inter, sans-serif;
}

.copyright {
    color: var(--Disabled, #bbb);
    margin-top: 16px;
    font: 10px/19px Proxima Nova, sans-serif;
}

.footer-nav {
    display: flex;
    gap: 20px;
}

.nav-column {
    display: flex;
    flex-direction: column;

}

.nav-link {
    font-size: 16px;
    color: var(--text-primary-100, var(--text, #161616));
    line-height: 30px;
    font-family: Proxima Nova, sans-serif;
    text-decoration: none;
}

.buy-link {
    color: var(--Primary-hover, #e54b50);
}

.car-selection-link {
    color: var(--Primary-hover, #e54b50);
}

.nav-heading {
    font-size: 16px;
    color: var(--text-primary-100, var(--text, #161616));
    line-height: 30px;
    font-family: Proxima Nova, sans-serif;
    font-weight: 700;
}
</style>