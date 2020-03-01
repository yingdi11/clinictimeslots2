Below is the step to reproduce the issue
1) Need to populate files in environments folder 
2) ng build and replace below with www/index.html

'''

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


3) cordova run android/ios

