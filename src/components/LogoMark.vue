<template>
  <div class="mark">
    a
  </div>
</template>

<script>
export default {
  name: 'logo-mark'
}
</script>

<style lang="scss" scoped>
@keyframes rotateOutline {
  100% { transform: rotate(360deg) }
}

.mark {
  position: relative;
  left: 0.1em;
  margin-top: 0.1em;
  margin-bottom: 4rem;
  height: 1.5em;
  width: 1.5em;
  background-color: #3f58cb;
  border-radius: 10px;
  box-shadow: 0 2px 4px 0 #758AE6;
  font-size: 4rem;
  color: #fff;
  text-align: center;
  line-height: 1.5em;
  &:before,
  &:after {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    display: block;
    border: 1px solid #3f58cb;
    border-radius: 10px;
    content: '';
  }

  &:before { animation: rotateOutline 12s linear infinite }

  &:after { animation: rotateOutline 16s linear infinite }
}
</style>
