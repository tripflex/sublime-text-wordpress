##Sublime Text 2 WordPress Package

Sublime Text 2/3 WordPress Package is a collection of WordPress snippets and autocompletions for Sublime Text 2

### Features

Autocomplete for:

    WP version : 3.7.0

    Functions          : 1734
    Hooks              : 1434
    Constants/Classes  :  191

### Notes

Deprecated functions (219) have been removed

The first "tab" deletes all parameters instead of having to tab through each one:

- First Tab-->Select all parameters
- Each Tab Thereafter-->Selects each individual parameter or block

### Snippets

Some updated snippets use the same name as the function, the autocomplete will show an "ALL Options" selection. For example to
register a custom post type you would write `register_post...`. Please review the snippets `<tabTrigger>` to see how to call the rest.


### Special thanks

Original TextMate author : [Gipetto](https://github.com/Gipetto/wordpress.tmbundle)  
Original scraper : [@ericandrewlewis](https://github.com/purplefish32/sublime-text-2-wordpress-scraper )  
Latest scraper :[@wycks](https://github.com/wycks/SublimeText-WordPress-Autocomplete)  

### Tip

Sublime won't autocomplete PHP files when there is no closing `?>` tags , so in "Preferences-->Settings-User" add this snippet:

    "auto_complete_selector": "source, text",

###  Install instructions

Just install via package control (WordPress) or clone into your sublime-text-2 package directory.

