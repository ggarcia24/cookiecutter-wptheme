# cookiecutter-wptheme
Cookiecutter template for Wordpress Theme

All the code contained here comes from the Twenty themes in 
Wordpress, I've added compass default styles with bootstrap 
support

The generated theme uses grunt to:
- compile the sass into css
- minify the js
- create a zipfile for distributing

Gruntjs Tasks
-------------
Availabe tasks in grunt file are:
- watch: Watch js and sass files for modifications
- compass: execute compass compile
- dist: compile the sass, minify the js, create a zip file
