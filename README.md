# Add local project to github
Contains instructions on how to push a local project to github.com

### Steps:

1. on your pc
    - create your project
    - initialize git in your project with: `git init`
    - stage all the files or just the files you want `git add .`
    - commit the files `git commit -m 'initial commit`

2. on github.com
    - login to github
    - create a new repo with the same name as your project
    - copy the repo link
    
3. back on your pc in the project directory run
    - `git remote add origin URL_TO_REPO` (newly created repo)
    - `git remote -v` (should see your repo)
    - `git push origin master`
    
    
 ### commands:
- `git remote add origin URL_TO_REPO`
- `git remote -v`
- `git push origin master`
- `git branch --set-upstream-to=origin/master master`
