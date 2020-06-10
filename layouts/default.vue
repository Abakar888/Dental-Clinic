<template>
  <div>
    <my-header />
    <my-info></my-info>

    <nuxt />
    <my-footer />
  </div>
</template>

<script>
import index from '@/pages/index'
import Header from '@/components/Header'
import Footer from '@/components/Footer'
import Info from '@/components/Info'
export default {
  components: {
    'my-header': Header,
    'my-footer': Footer,
    'my-info': Info,
  },
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>
