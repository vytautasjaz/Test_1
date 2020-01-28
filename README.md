@@ -0,0 +1,43 @@
Download this file;
Answer all questions;
Create new repository, push this file with answers and send me a like;

### 1. How to init NPM to new project?
    Create package.json file - run npm init in your root directory of the package and folow the instructions
### 2. How to install and save npm packages?
    Run command npm install (name of the pacakage) --save -dev
### 3. How to install webpack to your project and where to wright configurations?
    Add folowing lines to package.json file: "build":"webpack"
    Run build command "npm run build"
    Write webpack configurations in webpack.config.js file
### 4. How and where need to add webpack build and watch command?
    Write folowing lines in package.json file:
    "build": "webpack",
    "watch": "webpack --watch"
### 5. How to specify entry point in webpack configuration?
    Add folowing lines with corect paths in webpack.config.js:
    module.exports = {
     entry: './path/to/your/file.js'
    };
### 6. How to specify entry file output in webpack configuration?
    Add folowing lines with corect paths in webpack.config.js, under module.exports:
    output: {
    filename: 'filename.js',
    }
### 7. How to specify entry file output path in webpack configuration?
    Add folowing lines with corect paths in webpack.config.js, under module.exports:
    output: {
    filename: 'filename.js',
    path: path.resolve(__dirname, 'directory_name'),
    }
### 8. How to create new repository in Github?
    Create account in github.com, login and Add New Repository in Repositories section. 
### 9. How to init GIT in project?
    Go to your project directory and type "git init"
### 10. How to add all changes/files to git index?
    git add .
### 11. How to commit message for new changes?
    git commit -m "Message of changes" 
### 12. How to add remote URL to GIT project?
    git remote add origin https://github.com/username/repository.git
### 13. How to push changes to master?
    git push -u origin master
