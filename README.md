Create a desktop application using Electronjs
---
1. Create a new GitHub repo and clone it to your computer.
2. Open VSCode and make a new folder for your app.
3. Inside the folder, create two files: `index.html` and `index.js`.
4. Open the terminal in that folder.
5. Run `npm init` to start a new Node project.
6. Run `npm install --save-dev electron` to install Electron.
7. In `package.json`, add `"start": "electron ."` to the scripts section.
8. Write your Electron window setup code in `index.js`.
9. Create `preload.js` and write your preload script.
10. Run `git init` to start Git.
11. Link to your GitHub repo with `git remote add origin <repo-url>`.
12. Create a `.gitignore` file and add `node_modules/` inside it.
13. Run `git lfs install` to enable Git Large File Storage.
14. Track big files like images and videos with `git lfs track "*.png"` and similar commands.
15. Add and commit your files with `git add .` and `git commit -m "initial commit"`.
16. Push your code with `git push -u origin master`.
17. Run your app with `npm start`.
18. To package your app, install Electron Forge CLI and run the necessary commands:

    * `npm install --save-dev @electron-forge/cli`
    * `npm exec --package=@electron-forge/cli -c "electron-forge import"`
    * `npm run make`
---
Have fun building your app!
