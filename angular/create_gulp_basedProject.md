* Step 1: Ensure Node.js installed in your system or else install Node.js.

* Step 2: Ensure npm installed in your system if not install npm.

* Step 3: Create Base folder for your project and from command prompt go to the same directory.
    
    ``` mkdir <Project Base Folder Name> && cd <Project Base Folder Name> ```
    
* Step 4: Create an empty package.json  file.

* Step 5: from command prompt type following command for creating your project’s base configuration.

    ``` npm init ```
    
  >After entering above command this will prompt you to enter some default configuration details likes
  Name of the project , Project Version version , git repository path etc.
  After providing all the the details package.json will be updated with default configurations.
  
* Step 6: install gulp and bower global dependency

    ``` npm install –g gulp bower ``` 
  
  > To check if gulp and bower installed or not use following command this will display complete list of installed global dependencies.
 
    ``` npm list -g --depth=0 ```
    
* Step 7: Install other gulp plugins which we will be using while performing Angular Build.

   ``` npm install gulp-clean gulp-jshint gulp-uglify gulp-minify-css gulp-connect --save ``` 
   
* Step 8: Craete Angular Project structure and place correponding files in respective folders.

* Step 9: Create a empty gulpfile.js file and place in Project Base folder.

* Step 10: Edit gulpfile.js file and define tasks for Angular Project build.
  

  


