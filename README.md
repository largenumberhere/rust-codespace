# Rust-codespace
A beginner-friendly codespace template for writing writing rust programs adapted from [here](https://github.com/devcontainers/templates/tree/main/src/rust).

# Setup
1. Make sure you have a github account and you are signed in.
2. On the [main page](/), click the green button that says `Use this template`.
3. In the drop-down menu click `open in codespace`.
Note: It may take several minuites to be ready. 
You can if you like, click on the `show more` on the first page to get a hint about how fast it is progressing.

# Usage guide
It will take some time to start up. Once it is ready you should see a terminal window down the bottom of the screen.
To go to the example program:
1. type `cd /workspaces/rust-codespace/hello-world` and hit enter to change to this directory. 
2.  Use `cargo run` inside this project folder to run the example program.

### To make a new project use 
1. `cd /workspaces/rust-codespace/`
2. `cargo new myProjectName` where myProjectName is the name of the project you want to create.
3. `cd myProjectName` to go into the project folder
4. `code -r .` to **r**eopen vs**code** inside the project folder. This will make it easier to use. The dot is important don't forget it.
Note: If vscode is not opened in a project folder, you will get no tooltips and an awful debugging experience. 

### To edit a project's program
1. On the top left in visual studio is a file button. Click on it show all the folders and files
2. Click on the arrow next to `src`, inside this folder is `main.rs` double click on it, and it will open for you to edit.   

### When you are done working on a project use 
1. `cd /workspaces/rust-codespace/` to go back to our main folder 
2. `code -r .` to reopen vscode in this folder, so you can see all your projects when you click on the file icon in the top left.

# Cheatsheet - For convienient reference after reading
`cd /workspaces/rust-codespace` </br>
`cargo new myProjectName`</br>
`cd myProjectName`</br>
`cargo run`</br>
`code -r .`
