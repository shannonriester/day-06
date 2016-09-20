# Sass Responsive Web Design Project

- learned how to create scss files, nesting, running sass --watch, partials, and all about sass syntax uses.

- This is the Day-06 project from The Iron Yard

- The page is condensable from 840+ px, which condenses down to a middle size, and then is resized again for a mobile view at 510px and less



## Notes

1. .gitignore (no file extension)
    =========
***gitignore.io search***
  a. sass-cache
    - cashes in memory so not to recompile every time
  b. map file
    - just for editing purposes in browser
    - 1 and 2 can be ignored
    - create .gitignore
      ================
    - files that we don't want git to track (save in styles folder)
       1. styles/.sass-cache
       2. main.css.map

2. .surgeignore
    ===========
  - same with uploading to surge (only need to upload html files and css)
  - save in command file that you're working on
  a. .gitignore
  b. styles/ or styles/*.scss **
  c. main.css.map


### Nesting
    - keep nesting less than 4 levels deep
    - the 4th level is usually reserved for state such as pseudo selectors/classes

### DRY
  - Don't Repeat Yourself
