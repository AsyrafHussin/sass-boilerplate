# sass-boilerplate
Boilerplate for sass using 7-1 architecture pattern

## How to use
* Clone this repo to your project
```bash
$ git clone https://github.com/AsyrafHussin/sass-boilerplate.git <project-path>
```

* Remove .git file and README.md
```bash
$ rm -f .git && rm -rf README.md
```

## Folder Structure

    sass/
    ├── abstracts/     
    │   ├── _abstracts.scss      # Main file
    │   ├── _functions.scss      # Sass Functions
    │   ├── _mixins.scss         # Sass Mixins
    │   ├── _placeholders.scss   # Sass Pleholders
    │   └── _variables.scss      # Sass Variables  
    ├── base/          
    │   ├── _base.scss           # Main file
    │   ├── _reset.scss          # Reset/normalize
    │   └── _typography.scss     # Typography rules          
    ├── components/              
    │   ├── _components.scss     # Main file   
    │   └── _buttons.scss        # Buttons 
    ├── layout/        
    │   ├── _layout.scss         # Layout         
    │   ├── _footer.scss         # Footer
    │   ├── _forms.scss          # Forms               
    │   ├── _grid.scss           # Grid
    │   ├── _header.scss         # Header
    │   ├── _navigation.scss     # Navigation
    │   └── _sidebar.scss        # Sidebar   
    ├── pages/     
    │   ├── _pages.scss          # Main file     
    │   └── _home.scss           # Home specific styles            
    ├── themes/
    │   └── _default.scss        # Default theme 
    │   ├── _themes.scss         # Main file     
    ├── vendors/
    │   └── _vendors.scss        # Main file     
    └── app.scss                 # Main Sass file




