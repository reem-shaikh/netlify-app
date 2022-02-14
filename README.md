## Deploying an app with netlify 
### I. Drag & Drop method 
1. create a netlify account, sign in and import the build folder from your react app 
> https://festive-shirley-719cd5.netlify.app/

### II. Using Github 
1. Create a git repo and add these commands to your git bash 
```bash 
git init 
git remote add origin https://github.com/reem-shaikh/netlify-app.git
git add . 
git pull
git push -u origin master 
```
> copy the name of the repo "netlify-app", navigate to netlify, connect to git and add netlify-app for deploymnet, and woosh, your site is deployed.
> https://jovial-almeida-6e5b8c.netlify.app/
