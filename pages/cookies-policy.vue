<template>
  <div class="container">
    <h1 class="mt-5 mb-4">{{ $t('cookie.title') }}</h1>
    <!-- eslint-disable-next-line vue/no-v-html -->
    <div v-html="$t('cookie.text')"></div>
  </div>
</template>

<script>
export default {
  name: 'CookiePolicy',
}
</script>
