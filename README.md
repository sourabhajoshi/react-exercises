Prerequisites :-
    Download Node.js and NPM

check wheather installed or not using commands
    node -v
    npm -v

Initialize a New React Project:
    To start, open your terminal and write the following command to create an new React app using Create React App.

    npx create-react-app my-react-app
    cd my-react-app

Exploring the Project Structure
    my-react-app/
        |- node_modules/
        |- public/
        |  |- index.html
        |  |- ...
        |
        |- src/
        |  |- App.css
        |  |- App.js
        |  |- index.css
        |  |- index.js
        |  |- logo.svg
        |
        |- package.json
        |- package-lock.json
        |- README.md
        |- .gitignore
        |- ...
        
    - The node_modules folder contains all the project's dependencies installed by npm.
    - The public folder holds the static assets, including the index.html file, which is the entry point of our app.
    - The src folder is where we'll do most of our work. It contains the main application files, including the App.js component, which is the root component of our app.



npm : node package module : we can install either local or global

//////////////////////////////
Step to install package.json
//////////////////////////////

1. install node.js
2. navigate to folder where you want to create
3. npm init
4. answer all question
5. type yes

///////////////////////////////
Step to install local packages
///////////////////////////////
A local package is installed in a specific project or directory, and is usually referenced only within that project. It is typically stored in a folder like node_modules (for Node.js) or a virtual environment (for Python).

1. navigate to folder
2. npm install <package_name> : npm install react / npm i react
Note : React is open source, one package is depends on another so we got so many folders or files when we install react.

///////////////////////////////
Step to install local packages
///////////////////////////////
A global package is installed on your system so that it can be accessed from anywhere on your machine, regardless of the project. It’s available for any project or task that requires it.

npm i -g create-react-app