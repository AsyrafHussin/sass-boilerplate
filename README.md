# sass-boilerplate
This is the sass boilerplate using 7-1 architecture pattern that I used in my project. <br>
For more information about this architecture pattern, you can read [Guidelines](http://sass-guidelin.es/#architecture)

## How to use
* Clone this repo to your project
```bash
$ git clone https://github.com/AsyrafHussin/sass-boilerplate.git
```

* Update folder name from sass-boilerplate to sass
```bash
$ mv sass-boilerplate/sass sass && rm -rf sass-boilerplate
```

* Remove .git and README.md file
```bash
$ rm -f sass/.git && rm -rf sass/README.md
```

## Folder Structure

    sass/
    ├── abstracts/     
    │   ├── _abstracts.scss      # Main abstracts file
    │   ├── _functions.scss      # Sass Functions
    │   ├── _mixins.scss         # Sass Mixins
    │   ├── _placeholders.scss   # Sass Pleholders
    │   └── _variables.scss      # Sass Variables  
    ├── base/          
    │   ├── _base.scss           # Main base file
    │   ├── _reset.scss          # Reset/normalize
    │   └── _typography.scss     # Typography rules          
    ├── components/              
    │   ├── _components.scss     # Main components file   
    │   ├── _navbar.scss         # Navbar   
    │   └── _buttons.scss        # Buttons 
    ├── layout/        
    │   ├── _layout.scss         # Main layout file         
    │   ├── _footer.scss         # Footer
    │   ├── _forms.scss          # Forms               
    │   └── _grid.scss           # Grid   
    ├── pages/     
    │   ├── _pages.scss          # Main pagesfile     
    │   └── _home.scss           # Home specific styles            
    ├── themes/
    │   ├── _default.scss        # Default theme 
    │   └──_themes.scss         # Main themes file     
    ├── vendors/
    │   ├── _normalize.scss      # Normalize
    │   └── _vendors.scss        # Main vendors file   
    ├── _settings.scss           # Sass Settings  
    └── app.scss                 # Main Sass file

## Compile SASS to CSS

1. Using command line. [How to intall?](http://sass-lang.com/install)

* Compile <br> 
```bash
$ sass sass/:css/
```

> sass [sass-path]/:[css-path]/ <br>
> For compile specific file you can use this command <br>
> sass sass/app.scss:css/app.css

* Compile with livereload <br>
```bash
$ sass --watch sass/:css/
```  
  
* Compile with livereload and minify
```bash
$ sass --watch sass/:css/ --style compressed
```  

2. Using [Laravel Mix](https://github.com/JeffreyWay/laravel-mix/blob/master/docs/installation.md)
> [Frontend-Boilerplate](https://github.com/AsyrafHussin/frontend-boilerplate) for sass boilerplate + Laravel-mix 

3. Using [Gulp-Sass](https://github.com/dlmanning/gulp-sass)

4. Using [Grunt-Sass](https://github.com/sindresorhus/grunt-sass)

## Contributing
If you spot any errors, typos or missing information, please submit a pull request.



