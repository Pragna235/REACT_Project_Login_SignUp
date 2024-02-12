# Login-Signup-Page-using-React

<h3>Project Files</h3> - https://github.com/Pragna235/REACT_Project_Login_SignUp/blob/master

<h3> Live Project </h3> 

<h3> Playbook</h3>

* Open your project folder in `Visual Studio Code`
* Open the `Integrated Terminal`
* Create React Project using `npx create-react-app folder_name` in the terminal
* Navigate to project directory `cd .\folder_name\`
* If you don't wnat to create another foler, then just `npx create-react-app .`
* And then start the react app using `npm start` command
<br>

* Go to `App.js` in `src` and remove the `header` tag and the `className` and save it to start the app from scratch
* To access `index.html`, go to `public` folder
<br>

* In the `src` folder, create your own `Components` folder and create a `.jsx` file and `.css` file
* Import the CSS file into the JSX file
* To mount the component created in the .jsx file just created, go to `App.js` and mount it
* Now design your component in the .jsx and .css files is the src `_(_rafc, rafce...)_`
<br>

<h3>React page deployment on Github</h3>

<h4> Run the following on the VSCode Integrated Terminal</h4>

* `npm install gh-pages --save-dev`
* Alternative : Just use `npm run build`

* Create a new repository for the project and copy it's `.git` url
* `git remote add origin _link_`
* Open the `package.json` file :
    - add `"homepage" : "http://_github_username_.github.io/_repository_name_",`
    - update scripts
        - `"predeploy" : "npm run build"`,
        - `"deploy" : "gh-pages -d build"`
    - Save the file
* `npm run deploy`
* App is published!!!
<br>

<h3>Uploading local project folder to github repository</h3>

* Create a new repository and copy it's `.git` url
* Install git on local system
* Open the local project folder using `git bash`
* `git init`
* `git status`
* `git add -A`
* `git status`
* `git commit -m "_Any_Comment_We_want"`
* `git remote add origin "_.git_url"`
* `git push origin master`

File will be uploaded successfully - master branch..
  

