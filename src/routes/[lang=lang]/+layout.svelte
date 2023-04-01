<script>
  // use this if you want to offset header
  /** @param { HTMLElement } node */
  const setPaddingTop = (node) => {
    const headerHeight = document.getElementsByTagName('header')[0].getBoundingClientRect().height;
    node.style.paddingTop = `${headerHeight}px`;
  };
</script>

<div class="min-h-screen flex items-center justify-center p-4">
  <slot />
</div>
