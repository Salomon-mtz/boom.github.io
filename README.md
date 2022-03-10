# Boom-Percussion


## Documentation to keep a record of used commands

### How this package was created

Clone github repository

```
git clone "github url"
```

Command to initialize the project.

```
npm init
```

Command to add lite-server

```
npm install lite-server --save-dev 
```

Add to package.json scripts

# Inside package.json...
  "scripts": {
    "dev": "lite-server"
  },

Add node_modules to .gitignore file

```
fsutil file createnew .gitignore 0 
```

Edit .gitignore file and add node_modules to it
```
gitignore 
```

Commands to add files to a commit.

```
# Show untracked files
git status
git add .
git commit -m "First commit"
```
 
Command to upload files.

```
git push origin main
```


## How to run the application

Start the webserver

```
npm run dev
```

## How to add bootstrap

```
npm install --save bootstrap
```

## How to add jquery

```
npm install --save jquery
```

## How to add popper.js

```
npm install --save popper.js
```

## How to clean repository files

```
git reset --hard
```

## How to erase not included files in the repository

```
git clean -df
```

## How to create a pull request

### Locate the branch

```
git branch
```

### Create new branch

```
git checkout -b "new branch name"
```

### Add files

```
git add . 
```

### Commit changes

```
git commit -m "" 
```

### Push changes to the new branch

```
git push origin "new branch name" 
```

### Open github url to create the pull request

```
Example:  Create a pull request for 'video' on GitHub by visiting: https://github.com/Salomon-mtz/fratellis-front/pull/new/video
```

## Animations

https://codepen.io/EvyatarDa/pen/waKXMd
