# Starting a REACT project from scratch

The first thing is to go to <https://vite.dev/guide/> to create a react project with Vite using a template.
The code to generate the react template is:

```java
npm create vite@latest my-vue-app -- --template react
```

Create a folder where the project will be hosted. Next, open that folder with Visual Studio Code.
In the VSC terminal, paste the above command and run it to create the react project scaffoldings. This command should be copied and the words _my-vue-app_ changed with the name of the project to work on.
Before running this command, the package **create-vite@6.3.0** should be installed. If not, the terminal will ask you to install itself for you.

Afterward, the react skeleton will be shown in the VSC explorer as shown below:

![React folder skeleton in VSC](resources/images/React_Skeleton.png)

Next, npm should be installed **but** within the project folder, so that it will be need to go with the terminal one more folder below as shown in the picture below:

![Installation of Vite and npm shown in the terminal](resources/images/Install%20Vite%20and%20npm%20within%20the%20project%20folder.png)

After the npm installation, the folder structure has changed with two new files: node-modules and package-lock.json whih have been created by npm.

![Node-modules and package-lock.json created](resources/images/Folder%20Structure%20after%20installing%20npm.png)

Finally, run the command npm run dev to check that the installation of the react app has been correct.

![React working](resources/images/React%20working.png)

By cliking in the link of the localhost:5173 the browser will show the icons of react and vite indicating that the installation process has been cone correctly.

Next, install the react-router-dom with the command **npm install react-router-dom** with the project folder as we are going to implement several tabs in a single page application (SPA).
