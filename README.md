# Customize Boostrap v4 with Sass, Gulp and NPM
Streamline your ```bootstrap/sass``` web development environment by using this template.  

In addition, this template is configured with a ```custom.scss``` outside of ```npm_modules```.

Consequently, now you can safely [create your own bootstrap theme](https://getbootstrap.com/docs/4.0/getting-started/theming/).

Ready or not...lets begin...:musical_note:

## Install Your Local Environment
1. Install [gulp.js](https://gulpjs.com/) globally onto your machine
  
```npm install gulp -g```


2. Move into your project directory

```cd into the project directory```



3. Create a [package.json](https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm/) file

```npm init```
        

4. Install gulp.js into the project

```npm install gulp --save-dev```
        

## Install Bootstrap v4 Dependencies

Here are all of the bootstrap dependencies if you want to *install them all at once*:

```npm install bootstrap jquery popper.js --save-dev```

Or you can *install them individually*:

1. Install [bootstrap](https://www.npmjs.com/package/bootstrap)

```npm install bootstrap --save-dev```
        
        
2. Install [jQuery](https://www.npmjs.com/package/jquery)

```npm install jquery --save-dev```
        
        
3. Install [popper.js](https://github.com/FezVrasta/popper.js)

```npm install popper.js --save-dev```
        
        
## Install Your Gulpfile.js Dependecies

Here are all of the ```gulp.js``` dependencies if you want to *install them all at once*:

```npm install autoprefixer browser-sync cssnano del gulp-cache gulp-if gulp-imagemin gulp-postcss gulp-sass gulp-sourcemaps gulp-uglify gulp-useref run-sequence --save--dev```

Or you can *install them individually*:

1.  Install [autoprefixer](https://www.npmjs.com/package/autoprefixer)

```npm install autoprefixer --save-dev```
        
2. Install [browser-sync](https://www.npmjs.com/package/browser-sync)

```npm install browser-sync --save-dev```
        
3. Install [cssnano](https://www.npmjs.com/package/cssnano)

```npm install cssnano --save-dev```
        
4. Install [del](https://www.npmjs.com/package/del)

```npm install del --save-dev```
        
5. Install [gulp-cache](https://www.npmjs.com/package/gulp-cache)

```npm install gulp-cache --save-dev```
        
6. Install [gulp-if](https://www.npmjs.com/package/gulp-if)

```npm install gulp-if --save-dev```
        
7. Install [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)

```npm install gulp-imagemin --save-dev```
        
8. Install [gulp-postcss](https://www.npmjs.com/package/gulp-postcss)

```npm install gulp-postcss --save-dev```
        
9. Install [gulp-sass](https://www.npmjs.com/package/gulp-sass)

```npm install gulp-sass --save-dev```
        
10. Install [gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)

```npm install gulp-sourcemaps --save-dev```
        
11. Install [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)

```npm install gulp-uglify --save-dev```
        
12. Install [gulp-useref](https://www.npmjs.com/package/gulp-useref)

```npm install gulp-useref --save-dev```

13. Install [run-sequence](https://www.npmjs.com/package/run-sequence)

```npm install run-sequence --save-dev


## Start Your Web Development Environment

1. Exit out of your code editor

2. Re-open your code editor

3. Inside of your project type:

        gulp 
        
Many things should have just happened including ```browser-sync``` opening up your browser to a blue Hello World! on a pink background.
This is how we know it worked...if this did not happen make sure all of the dependencies were installed and the package.json has them listed under dependencies.

The biggest thing you should recognize is under the css directory.
Sass has compiled the ```bootstrap``` framework into a new file called ```custom.css```. 


## Contributing
Contributions are welcome! 🤘 

🥂 Thanks for using this project! I hope it's helpful. If you see ways to improve it, PRs are welcome.
        
        
        
        

     
       
 



