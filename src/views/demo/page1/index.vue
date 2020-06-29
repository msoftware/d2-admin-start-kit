<template>
  <d2-container>
    <template slot="header">Page 1 header</template>
    <h3>Hello World</h3>
    <p>{{ $t('message') }}</p>
	<p v-html="$t('message')"></p>
  </d2-container>
</template>

<script>
export default {
  name: 'page1'
}
</script>
