## Dev

Use `browser-sync start --server --files "./**/*"` to run browser-sync to watch and reload your code.

### Notes

#### Lineheight

To calculate line-height, take the line-height value and divide it by the font size. Ex: 50 / 32 -> 1.5625. Make sure to not add any value after that number like rem or em.

### script for html above closing body tag

<script id="__bs_script__">//<![CDATA[
        document.write("<script async src='http://HOST:3000/browser-sync/browser-sync-client.2.13.0.js'><\/script>".replace("HOST", location.hostname));
      //]]></script>
