# resizing-iframe-to-fit-content

<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>

<iframe src="..." frameborder="0" scrolling="no" onload="resizeIframe(this)" />
