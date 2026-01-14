# CoFmuPy-GUI

User interface for **CoFmuPy** library.

This repository contains only user interface code. It produces versionned artifacts consumed by Python backend (CoFmuPy library).


**Web App overview**

![Exemple de capture](cofmupy-gui-app/src/assets/ScreenShot_App.png "Title")


## 🎯 User interface role

- Provide web user interface
- Communicate with backend using http and WebSocket API

👉 This user interface can be served by backend flask, see [CoFmuPy library](https://github.com/IRT-Saint-Exupery/CoFmuPy) documentation.



## 🧩 API consistency

Compatibility with backend is made by file *api-compatibility.json*, here is an example :

```json
{
  "min": "1.0",
  "max": "2.x"
}
```

---

## 🏗️ Local development

### Prerequisite

- Node.js ≥ 18
- Angular CLI

### Content :

Composed of 2 sub-directories. See embedded readme files for develop and use :

* **cofmupy-gui-app**, for the application itself
* **node-server**, for the server that manage application, only useful for standalone application.


## 📦 Releases and artifacts

Releases and artifacts are automatically generated via GitHub Actions.

Artifacts content, generated for each push on main branch :
- `cofmupy-gui_standalone.zip` : zip file containing standalone application with launcher batch file, node server and CoFmuPy-gui application.

Releases content, generated for each added tag with containing text `v*` :
- `CoFmuPy-gui-dist.zip` : zip file with generated application, can be download by CoFmuPy library to serve it in production mode.
- `metadata-dist.json` : metadata with application caracteristics, including compatibility version with backend API

## ✒️ Contributing

Feel free to propose your ideas or come and contribute with us on the CoFmuPy library!

## 📄 Licence

The package is released under the [2-Clause BSD License](https://opensource.org/license/bsd-2-clause).
