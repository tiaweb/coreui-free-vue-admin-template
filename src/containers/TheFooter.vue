<template>
  <CFooter :fixed="false">
    <div>
      <a href="https://tiaweb.github.io" target="_blank">Tiaweb</a>
      <span class="ml-1">&copy; {{new Date().getFullYear()}}Surabaya.</span>
    </div>
    
  </CFooter>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>
