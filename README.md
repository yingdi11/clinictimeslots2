Below is the step to reproduce the issue
1) Need to populate files in environments folder 
2) ng build and replace below with www/index.html

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Angularfirebaseloginserver</title>
  <base href="./">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" type="image/x-icon" href="favicon.ico">
  <script src="cordova.js" ></script>
</head>
<body>
<app-root></app-root>
<script src="runtime-es2015.js" type="text/javascript"></script>
<script src="runtime-es5.js" type="text/javascript" defer></script>
<script src="polyfills-es5.js" type="text/javascript" defer></script>
<script src="polyfills-es2015.js" type="text/javascript"></script>
<script src="styles-es2015.js" type="text/javascript"></script>
<script src="styles-es5.js" type="text/javascript" defer></script>
<script src="vendor-es2015.js" type="text/javascript"></script>
<script src="vendor-es5.js" type="text/javascript" defer></script>
<script src="main-es2015.js" type="text/javascript"></script>
<script src="main-es5.js" type="text/javascript" defer></script>
</body>
</html>


3) cordova run android/ios

