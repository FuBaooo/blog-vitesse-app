<script setup lang="ts">
const { t } = useI18n()
</script>

<template>
  <div class="prose m-auto">
    <h2>FuBao</h2>
    <h4>{{ t('me.about') }}</h4>
    <p>
      {{ t('me.article') }}
      <a href="https://nodejs.org/zh-cn/" title="Node.js">Node.js</a>
      &
      <a href="https://www.rust-lang.org/" title="Rust.js">Rust</a>
    </p>
    <h4>{{ t('me.about_front') }}</h4>
    <p>
      {{ t('me.article_front') }}
      <ul>
        <li>
          <a href="https://v3.vuejs.org/" title="Vue.js">Vue.js</a>
          {{ t('me.article_about_vue') }}
        </li>
        <li>
          <a href="https://nuxtjs.org/" title="nuxt.js">Nuxt.js</a>
          &
          <a href="https://v3.nuxtjs.org/" title="nuxt3.js">Nuxt3.js</a>
          {{ t('me.article_about_nuxt') }}
        </li>
        <li>
          <a href="https://www.electronjs.org/" title="electron">Electron</a>
          {{ t('me.article_about_electron') }}
          <a href="https://github.com/FuBaooo/dst-cloud-manage" title="DSTCloudManage">DSTCloudManage</a>
          {{ t('me.article_about_electron1') }}
        </li>
        <li>
          <a href="https://react.docschina.org/" title="react">React</a>
          {{ t('me.article_about_react') }}
        </li>
        <li>
          {{ t('me.article_about_more') }}
        </li>
      </ul>
    </p>
    <h4>{{ t('me.about_future') }}</h4>
    <p>{{ t('me.article_about_future') }}</p>
  </div>
</template>
