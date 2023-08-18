# Convention Guide

## 1. Git Management

### 1.1. Branch
- Use `develop` branch as base source code.
- Use `feature` branch for updating new feature.
- Use `bugfix` branch for resolving bug after updating new feature.
- Use `release` branch for updating `tag` (version) and push to QA test.
- Use `hotfix` branch for resolving issue according to QA test feedback.
- Use `main` branch for releasing to public.

### 1.2. Push/Pull
- Create specific issue before developing/resolving any new issue
- **Always** use `git pull` to fetch the latest version before making any change
- Create pull request after developing/solving issue


## 2. Naming Rule / Property

### 2.1. General Naming Rule
- Use `lowercase` for folder and file name.
- Use `underscore` (_) to seperate word of folder or file.
- Name folder and file according to its purpose.
- Name should be meaningful

### 2.2. HTML

- Use semantic tag (`header, nav, main, sidebar, footer`)
- Use `<ul>` to create list
- Use `.container` class for all upper parent tag
- Use `class` to style the element
- **Don't** use `inline` css
- Only use `external` css
- Don't use `id` if not neccessary

### 2.3. CSS / SCSS
- Use `lowercase` for naming
- Use `dash` (-) to seperate word
- Font family ...
- Font size using `em` or `rem`
    - Title
    - Paragraph

### 2.4. Javascript
- Use `Camel case` for naming variable and function.
- Use `let` to declare variable.
- Use `variable` to store value.