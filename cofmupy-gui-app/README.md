# CoFmuPy-GUI-app

Here is the frontend application, develop with Angular framework, and using Bootstrap and GoJs libraries.


**Web App overview**

![Exemple de capture](src/assets/ScreenShot_App.png "Title")

---

## 🏗️ Local development

### Prerequisite

- Node.js ≥ 18
- Angular CLI

### Content :

```bash
cofmupy-gui-app/
├─ src/
│  ├─ app/
│  │  ├─ components/                # Source code for visual components 
│  │  ├─ main/                      # Main component for the whole page
│  │  ├─ services/                  # Folder with all services classes : http, websocket, fmu, project
│  │  ├─ app.config.ts              # Configuration the the whole Angular application
│  │  └─ app.routes.ts              # Routes definition. Select displayed component pending route
│  ├─ assets/                       # Application resources : additional css, images, scripts, ...
│  ├─ environments/                 # Configuration pending execution environment : production, dev, ...
│  ├─ favicon.ico
│  ├─ index.html                    # Entry point view of the application
│  ├─ main.ts                       # Angular Application initialisation
│  └─ styles.css                    # Main application styles file
├─ .gitignore
├─ angular.json                     # Angular configuration : build, test, serve, ...
├─ package-lock.json
├─ package.json                     # npm dependencies file
├─ README.md                        
├─ tsconfig.app.json
└─ tsconfig.json                    # Typescript configuration

```

### Installation and Start (development/debug mode)

```bash
# Installation
npm install

# Start application, development mode
ng serve
```

### Build

```bash

# Update libraries
npm install

# Run build command
ng build
```

This will compile your project and store the build artifacts in the `/cofmupy-gui-app/dist` directory. Folder content :

```bash
browser/
├─ assets/
│  ├─ css/
│  │  └─ vendors/
│  │     ├─ bootstrap_*/          # Bootstrap css files
│  │     └─ bootstrap-icons_*/    # Bootstrap icons files
│  ├─ angular.svg
│  ├─ api-compatibility.json      # json containing api compatibility with backend
│  ├─ location-pin.svg
│  ├─ logo.svg
│  ├─ ScreenShot_App.png
│  ├─ Start_CoFmuPy_Gui.bat       # Batch to start app as a standalone application (Windows)
│  └─ Start_CoFmuPy_Gui.sh        # Batch to start app as a standalone application (Linux)
├─ favicon.ico
├─ index.html                     # Entry point view of the application
├─ main-LR6WMCYY.js               # Application script
├─ polyfills-5CFQRCPP.js          
└─ styles-GSBFIRKP.css            # Application styles
```

