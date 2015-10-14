##FogCloud
	This is the js for FogCloud, and js's name is fgjs, you can try var fg = require("fgjs");

watchify micoac.js -o mico-ac-0.1.min.js
browserify micoac.js -t | uglifyjs -cm >  mico-ac-0.1.min.js