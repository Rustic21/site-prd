<template>
  <div class="layout1">
    
    <the-header></the-header>
    <div class="container-layout">
        <slot></slot>
    </div>
    <the-footer></the-footer>
  </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.layout1 {
  overflow-y: scroll ;
}

.container-layout {
    min-height: calc(100vh - 164px)
}
</style>