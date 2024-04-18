<script setup>
/* eslint-disable */
</script>
<template>
  <header class="header">
    <nav class="navigation">
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/d812136135e739308e79f16d5072dbde0fb2d9a0e7702649df411a1a4d5d0fb4?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="NI1"
        class="navigation-item" 
      />
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/eaf5db68b685eb014a95f526ca91b434fa903cf415ff8e887a28370698b6619a?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="Navigation item 2" class="navigation-item"/>
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/e8b1e369f9d85241006d854ebe07bd97ad4804afc863b2f3d04d2c46a0aa6d17?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="Navigation item 3" class="navigation-item"/>
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/2178ace877bd00153ace3a3cdf682799da8c182e0e5187cfe2299ff6744b2928?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="Navigation item 4" class="navigation-item"/>
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/5fdbd7421cbc04188cb486b89ed4e1293ca8c2005c21764fda651e08cdb5e5a8?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="Navigation item 5" class="navigation-item"/>
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac24babec4bd9371443e42fa78a6d76eb60ad6bc5737cf2c54a01497e3787d75?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="Navigation item 6" class="navigation-icon"/>
    </nav>
    <div class="contact-info">
      <div class="phone-number">
        <div class="phone-icon-container">
          <img
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/178a67b769187910090ca018e20cb1e3a5dcf4b4f2d62cf0775f7307e140e07f?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
            alt="Phone icon" class="phone-icon" />
        </div>
        <div class="phone-number-text">067-322-16-63</div>
      </div>
      <div class="language-switcher">
        <div class="language-item active">RU</div>
        <div class="language-item">
          <img
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/453f6a562aab1248dd9440e607cdd7ee3f775e034ecc891f2965879be38fb7a9?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
            alt="Ukraine flag" class="language-flag" />
          <div class="language-text">UA</div>
        </div>
      </div>
      <img
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/edc32f6dd59719b7ee757c42415f31603df0ec600864ca5c78685b239ef45424?apiKey=941722781dcd4bc79a2c09d8279b9fb0&"
        alt="Profile icon" class="profile-icon" />
    </div>
  </header>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

@media (max-width: 991px) {
  .header {
    flex-wrap: wrap;
  }
}

.navigation {
  display: flex;
  gap: 20px;
  margin: auto 0;
  padding: 0 20px;
}

.navigation-item {
  width: 100%;
  flex: 1;
  aspect-ratio: 1;
  object-fit: auto;
  object-position: center;
}

.navigation-icon {
  width: 24px;
  aspect-ratio: 1;
  object-fit: auto;
  object-position: center;
}

.contact-info {
  display: flex;
  gap: 20px;
  padding: 5px 20px;
}

.phone-number {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 4px 20px 4px 4px;
  border-radius: 28px;
  box-shadow: 0px 4px 5px 0px rgba(176, 176, 176, 0.25);
  background-color: var(--Text-secondary, #fff);
}

.phone-icon-container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 32px;
  height: 32px;
  padding: 0 16px;
  border-radius: 32px;
  background-color: var(--Secondary-active, #40a600);
}

.phone-icon {
  width: 24px;
  aspect-ratio: 1;
  object-fit: auto;
  object-position: center;
}

.phone-number-text {
  margin: auto 0;
  color: var(--text-primary-100, var(--text, #161616));
  font: 400 16px Proxima Nova, sans-serif;
}

.language-switcher {
  display: flex;
  gap: 10px;
  padding-left: 10px;
  font-size: 16px;
  font-weight: 400;
  white-space: nowrap;
}

@media (max-width: 991px) {
  .language-switcher {
    white-space: initial;
  }
}

.language-item {
  margin: auto 0;
  color: var(--text-primary-100, var(--text, #161616));
  font-family: Proxima Nova, sans-serif;
}

.language-item.active {
  color: var(--text-primary-100, var(--text, #161616));
}

.language-item:not(.active) {
  display: flex;
  gap: 4px;
  padding: 10px;
  color: var(--Disabled, #bbb);
  border-left: 1px solid rgba(187, 187, 187, 1);
}

@media (max-width: 991px) {
  .language-item:not(.active) {
    white-space: initial;
  }
}

.language-flag {
  width: 24px;
  aspect-ratio: 1;
  object-fit: auto;
  object-position: center;
}

.language-text {
  margin: auto 0;
  font-family: Proxima Nova, sans-serif;
}

.profile-icon {
  width: 40px;
  aspect-ratio: 1;
  object-fit: auto;
  object-position: center;
}
</style>