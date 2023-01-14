<template>
  <CFooter :fixed="false">
    <div>
      <span class="ml-1">&copy; {{new Date().getFullYear()}} creativeLabs.</span>
    </div>
    <div class="ml-auto">
      <span class="mr-1">Powered by</span>
      <a href="https://github.com/jackrobert916" target="_blank">jackrobert</a>
    </div>
  </CFooter>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>
