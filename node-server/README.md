# Node-server

Here is source code for the server that manage application, only useful for standalone application.



## 🏗️ Local development

### Prerequisite

- Node.js ≥ 18
- Angular CLI

### Content :


### Build 
```bash

# Update libraries
npm install

# Run build command
parcel build app.js

```
This will compile node server and store the build artifacts (app.js) in the `/node-server/dist` directory.


**3. Assemble to make a standalone package**

Concatene `/cofmupy-gui-app/dist/browser` with to obtain standalone application. The distribution should be composed of following files :
* Application :
  * **assets** directory : resources directory
  * **app.js** : node server entry point
  * **index.html** : User interface entry point
  * **main-*.js** : Application main scripts and views
  * **polyfills-*.js** : Application complement scripts and views
  * **style-*.css** : Application styles
* Starter scripts :
  * **Start_CoFmuPy_Gui.bat** : Script file to start application (Windows)
  * **Start_CoFmuPy_Gui.sh** : Script file to start application (Linux)

**4. Start application**

To start generated application, execute *Start_CoFmuPy-Gui* batch file and follow instructions.


