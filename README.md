# Electron React Template

_Easy-to-understand-and-use boilerplate code for creating an Electron desktop app simply using Reactjs. Includes React Router._
<br>
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), [Electron](https://electronjs.org/), and [electron-builder](https://github.com/electron-userland/electron-builder).

## Build Electron App With React - Video Tutorial

[Video Tutorial at YouTube](https://www.youtube.com/playlist?list=PLASldBPN_pkCXhDdahLI2RIRy1tmGTeit)

## Usage

1. Clone this repository.

```
git clone https://github.com/TarunKumar29/electron-react.git <your-project-name>
```

2. If you havent already, install Yarn globally.

```
npm install -g yarn
```

3. Navigate into project root and install dependencies.

```
cd <your-project-name> && npm install
```

4. Run dev server.

```
npm run start
```

## Deploy to Desktop

1. Run the build process

```
npm run build
```

2. Go into your project folder using your file explorer. Navigate to the `dist` folder and open it. Then double-click `<your-project-name>` Setup 0.1.0. Your app should open and there should now be an icon on your desktop for this app.

**Use a Custom Icon**

Add a 256 x 256 .png or .ico image in your public folder. It should be either `icon.ico` or `icon.png`. Update the `icon` property in your `package.json` if necessary. Currently, it uses an image called `icon.png`, which is a graphic of a coffee cup. You'll only see this in production. For more info, see the [electron-builder documentation](https://www.electron.build/icons)

## Errors to ingnore while using the template -

1. Errors showing the modules are deprecated. You can safely use the template even after those warnings or errors (though it is advisable to update it).

Example -

```
...
npm WARN deprecated @hapi/hoek@8.5.1: This version has been deprecated and is no longer supported or maintained
npm WARN deprecated...
```

(**Note: However these types of messages are not expected as all the modules are updated frequently. :)** )

2. Errors related to fsevents can be ignored if it is use in computer which is **not** a _mac_. (If any error related to _fsevents_ happens on mac, please file a issue !)

#### Credits to (for making the initial commits of the repo) -

@willjw3 | https://github.com/willjw3
