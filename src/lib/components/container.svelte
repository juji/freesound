<script>
  let className = ''
  export { className as class }
</script>

<div class={`container px-8 mx-auto ${className}`}>
  <slot />
</div>