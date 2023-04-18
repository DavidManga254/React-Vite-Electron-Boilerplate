## Introduction
A simpler boilerplate for working with Electron, Vite and React

Remember to change the ```name and author``` in the package.json after cloning

## 🛫 Quick start
Clone the repo with the following command

```sh
git clone https://github.com/DavidManga254/React-Vite-Electron-Boilerplate
```

Navigate to the root folder then run
```
npm install
```

when installation is done while in the root folder run:
```
npm run dev
```

remember to change credentials such as author name and project name in the package.json


## 📂 Directory structure

Familiar React application structure, just with `electron` folder on the top:  
*Files in this folder will be separated from your React application and built into `dist-electron`*  

```tree
├── electron                                 Electron-related code
│   ├── main                                 Main-process source code
│   └── preload                              Preload-scripts source code
│
├── release                                  Generated after production build, contains executables
│   └── {version}
│       ├── {os}-{os_arch}                   Contains unpacked application executable
│       └── {app_name}_{version}.{ext}       Installer for the application
│
└── src                                      Renderer source code, your React application
```
