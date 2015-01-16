## Introducing

This is simple template for work on Cordova application with [bower](https://github.com/bower/bower) and [grunt](https://github.com/gruntjs/grunt).
With this you can made your work more comfortable in few minutes. Try it! 

### How to work with this template:

1. You must to create cordova application and remove 'www' folder.

	$ `cordova create test org.test.app Test`

2. Then clone this repositorie to your cordova app folder.

	$ `cd path/to/cordova_app`
	$ `git clone https://github.com/ar0ne/cordova_template.git`

3. If you don't have bower or grunt then you must to install it on your OS.

	For more details about bower see: http://bower.io/
	And for grunt: 	http://gruntjs.com/getting-started

4. With bower you don't need more searching latest version of popular libraries for your application. In one command you can easy download all you need.

	In this template i added jquery and [FastClick](https://github.com/ftlabs/fastclick), because it's most popular libraries what i used in cordova development.

	$ `bower install`

	If you don't need some libraries you can remove it: $ `bower uninstall jquery --save`

5. For run Gruntfile you must to install grunt and few components as uglify etc.

	$ `npm install grunt grunt-contrib-concat grunt-contrib-uglify grunt-contrib-watch grunt-contrib-cssmin --save-dev`

6. Then if you want to try work with it you must once run $ `grunt` and open `www/index.html` in your browser. 

	Your develop js and css files must to be in `develop/` folders. When you edited some files and save him grunt process it and you'll have production files in `www/` folder.

That's all. Have a fun;)
