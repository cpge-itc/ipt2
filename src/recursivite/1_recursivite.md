<script type="text/javascript" src="../utils.js"></script>

<iframe id="pdf-js-viewer" title="webviewer" frameborder="0" width="100%" height="800"></iframe>

<script>
    window.onload = () => document.getElementById("pdf-js-viewer").src = url("recursivite/recursivite.pdf") + "#zoom=page-fit";
</script>