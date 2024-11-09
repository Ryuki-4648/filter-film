<script setup>
</script>

<template>
  <header class="l-header">
    <div class="l-header__inner">
      <div class="l-header__index">
        <img src="/img_logo01.png" :alt="`t('SITE_TITLE')`" class="l-header__logo" />
        <h1 class="l-header__title"></h1>
      </div>
      <ul class="l-header__lang">
        <li class="l-header__langItem">
          <NuxtLink to="/en" class="l-header__langLink">
            EN
          </NuxtLink>
        </li>
        <li class="l-header__langItem">
          <NuxtLink to="/" class="l-header__langLink">
            JP
          </NuxtLink>
        </li>
      </ul>
    </div>
  </header>
</template>