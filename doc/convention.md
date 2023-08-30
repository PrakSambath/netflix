# Convention Guide

## 1. Folder structure
```
css
└── All css file goes here.
doc
└── All documentation and related file goes here.
image
└── All image file goes here.
js
└── All javascript file goes here.
index.html
README.md
```

## 2. Git Management

### 2.1. Branch
- Use `develop` branch as base source code.
- Use `feature` branch for updating new feature.
- Use `bugfix` branch for resolving bug after updating new feature.
- Use `release` branch for updating `tag` (version) and push to QA test.
- Use `hotfix` branch for resolving issue according to QA test feedback.
- Use `main` branch for releasing to public.

### 2.2. Push/Pull
- Create specific issue before developing/resolving any new issue
- **Always** use `git pull` to fetch the latest version before making any change
- Create pull request after developing/solving issue


## 3. File Naming Rule

- Use `lowercase` for folder and file name.
- Use `dash` (-) to seperate word of folder or file.
- Name folder and file according to its purpose.
- Name should be meaningful

## 4. HTML

- Use semantic tag (`header, nav, main, sidebar, footer`)
- Use `<ul>` to create list
- Use `external` css
- Don't use `id` if not neccessary
```
<body>
    // header section
    <header></header>

    // navigation section
    <nav></nav>

    // main section
    <main></main>

    // footer section
    <footer></footer>
</body>

```

## 5. CSS / SCSS
- Use `lowercase` for naming
- Use `dash` (-) to seperate word
- Font size using `em` or `rem`     

**color**   
logo `color-primary`    
text `color-secondary`  
background `color-dark-1`   

**Font**    
font-family `"Roboto", "sans-serif"`    
**Font size**   
font-size large: `3rem`  
font-size medium: `1.5rem`   
font-size small: `1rem`   


## 6. Javascript
- Use `Camel case` for naming variable and function.
- Use `let` to declare variable.

## 7. Grid System
- Use bootstrap framework to organize grid column.
- Use `12 columns` as blueprint