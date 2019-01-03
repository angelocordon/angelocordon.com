<template>
  <nav class="menu">
    <p class="menu-label">Elsewhere</p>
    <ul class="menu-list">
      <li><a href="https://twitter.com/angelocordon">Twitter</a></li>
      <li>
        <a href="https://linkedin.com/in/angelocordon/">LinkedIn</a>
      </li>
      <li>
        <a href="https://github.com/angelocordon">GitHub</a>
      </li>
      <li><a href="https://medium.com/@angelocordon">Medium</a></li>
      <li>
        <a href="https://dribbble.com/angelocordon">Dribbble</a>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'main-navigation'
}
</script>

<style lang="scss" scoped>
.menu-label {
  font-family: 'Source Sans Pro';
  font-weight: 600;
  letter-spacing: 2px;
}

.menu-list {
  > li { height: 2rem }
  a { color: #3f58cb }
}
</style>
