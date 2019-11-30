Fork of the twentytwenty image comparison script.

- [x] Modified to fix the image load bug
- [x] Allows comparison of up to 4 images

Not my work, just need a place to upload this.

Make sure to include the jquery files

```
<script src="js/jquery-3.2.1.min.js" type="text/javascript"></script>
<script src="js/jquery.event.move.js" type="text/javascript"></script>
```

Include the image compare specific files
```

<script src="js/imagecompare.js" type="text/javascript"></script>
<script src="js/imagecompare_load.js" type="text/javascript"></script>
<link rel="stylesheet" href="css/imagecompare.css" type="text/css" media="screen" />
```

Use it in html like:

```
<div class="twentytwenty-container">
  <img src="/some/path/image.png" alt="something"/>
  <img src="/some/path/image.png" alt="something"/>
  <img src="/some/path/image.png" alt="something"/>
  <img src="/some/path/image.png" alt="something"/>
</div>
```