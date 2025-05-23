# git commands
```sh
# from laptop to github
git init
git add .
git commit -m 'commit message'
git push

#from github to laptop
git pull

#**Short code**
cd your-project-folder
npm start
npm run dev 



```
# React Commands 
```sh
Run react code in server
1. Create a New React Project

npx create-react-app my-react-app
cd my-react-app

2. Open Project in VS Code
code .

3. Install Recommended Extensions (in VS Code)

Open Extensions view (Ctrl+Shift+X or ⌘⇧X)
Search for and install:
"ES7+ React/Redux/React-Native snippets"
"Prettier - Code formatter"
"ESLint"

4. Configure the Terminal

Open the integrated terminal (Ctrl+ or ⌃)
The terminal will automatically use your project directory

npm start

8. (Optional) Customize Output Settings
Create a jsconfig.json in your project root for custom settings:
{
  "compilerOptions": {
    "baseUrl": "src",
    "jsx": "react-jsx"
  },
  "include": ["src"]
}

Tips for First-Time Users

Save files frequently (Ctrl+S or ⌘S)
Check the terminal for errors if something isn't working
The main files you'll edit are in the src/ folder
src/App.js is the main component that gets rendered


