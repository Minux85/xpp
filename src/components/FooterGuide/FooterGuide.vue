<template>
  <div class="footer_guide">
    <span class="guide_item">1</span>
    <span class="guide_item">2</span>
    <span class="guide_item">3</span>
    <span class="guide_item">4</span>
  </div>
</template>

<style scoped>
  .footer_guide{
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #f8f6f6;
    width: 100%;
    height: 50px;
    display: flex;
  }
  .guide_item{
    -webkit-box-flex: 1;
    flex: 1;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    flex-direction: column;
    margin: 17px;
    color: #999;
  }
</style>
