# ZLIB-JS
##its a 100% Pure-JavaScript Implementation of The ZLIB INFLATE Method.##
###it is 100% compatible with PHP's zlib_encode Using The ZLIB_ENCODING_DEFLATE encoding###

```PHP
<html>
<body>

Server-Side Encoding:
--------------------------------
<?php   echo base64_encode(zlib_encode("##########################################################################", ZLIB_ENCODING_DEFLATE)); ?>
<!-- result: "eJxTVqYWAAB7vgof" -->

Client-Side Decoding:
--------------------------------
<script src="zlib_inflate.js"></script>
<script>
document.body.innerHTML += ZLIB.inflateInit().inflate(atob("eJxTVqYWAAB7vgof"));
/* result: "##########################################################################" */
</script>

</body>
</html>
```
