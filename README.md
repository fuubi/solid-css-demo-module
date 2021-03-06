# Community Solid Server (CSS) Demo Module

This repository can be used as a reference to get started with your own
custom CSS module.

To get started in seconds, run [this](https://github.com/FUUbi/solid-css-demo-module/blob/main/bin/init-css-module) script with the following command.
The script assumes to be executed in an empty directory and using the directory name as a project name.
```
mkdir project-name
cd project-name 
wget -O - https://raw.githubusercontent.com/FUUbi/solid-css-demo-module/main/bin/init-css-module | bash
```

Or set the project_name variable manually if your project name contains special characters which interfere with the file system or sed. 
Make sure to escape special regex characters which could interfere with the sed command (as an example  / is replaced by \/).  
```bash
cd somedir
wget -O - https://raw.githubusercontent.com/FUUbi/solid-css-demo-module/main/bin/init-css-module | project_name="@org\/css-cool-module"  bash
```

*The scripts depends on: Bash, Git, Sed*

Of course, you can also just run the commands manually or clone the repo.

TODO: add links to CSS and Components.js documentation

