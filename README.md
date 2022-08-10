# resizing-iframe-to-fit-content
<br>
<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>

<br>
<br>

<iframe src="..." frameborder="0" scrolling="no" onload="resizeIframe(this)" />
