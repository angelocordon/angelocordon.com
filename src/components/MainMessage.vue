<template>
  <div class="message is-info">
    <div class="message-header">
      Hiring?
      <div class="buttons has-addons is-right">
        <a href="mailto:angelocordon@gmail.com"
           class="button is-small has-text-weight-semibold is-uppercase is-info">
          Email Me
        </a>
        <a href="angelo-cordon-resume.pdf"
          class="button is-small has-text-weight-semibold is-uppercase is-info">
          View Resume
        </a>
      </div>
    </div>
    <div class="message-body">
      <p>
        I'm open to new career opportunities in San Francisco, California.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'main-message'
}
</script>

<style lang="scss" scoped>
  .button { font-family: 'Source Sans Pro', sans-serif }

  .message-body { border: 1px solid }
</style>
