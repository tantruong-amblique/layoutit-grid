<template>
  <div class="version">
    <span><a target="_blank" rel="noopener" href="https://leniolabs.com">Hire us!</a></span>
    <span class="version-text">v1.3.4</span>
  </div>
</template>

<style scoped lang="scss">
.version {
  align-items: flex-end;
  color: #ccc;
  display: flex;
  justify-content: space-between;
  font-weight: 700;
  font-family: monospace;
  padding: 6px 14px;
  text-align: center;
  a {
    text-decoration: none;
    color: #ccc;
    font-size: 0.9rem;
    &:hover {
      color: #fff;
    }
  }
  .version-text {
    font-size: 0.7rem;
    &:hover {
      color: #fff;
    }
  }
}
</style>
