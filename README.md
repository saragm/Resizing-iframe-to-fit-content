# resizing-iframe-to-fit-content
<br>
<script><br>
  function resizeIframe(obj) {<br>
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';<br>
  }<br>
</script>

<br>
<br>

<iframe src="..." frameborder="0" scrolling="no" onload="resizeIframe(this)" />
