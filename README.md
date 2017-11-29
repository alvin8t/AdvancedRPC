# AdvancedRPC
A Feature Rich Program for using Discord's Rich Presence

# Dependencies
Yarn and NodeJs 8.0.0 or later versions must be installed on your system.
**NOTE: YARN is HIGHLY reccomended over NPM. All steps will be shown for YARN**

# Installation
1. Download this Repo
2. Open Command Prompt and Navigate to the Project root (you should see a file called `main.js` and `package.json`)
3. Type `yarn`. This should have a few things popup on the command prompt.
4. Once the installation from Stop 3 is complete. Type `yarn global add electon`. This Repo will work with Electron versions 1.7.9 or higher
5. Before you can run the application, please see the 'Modifying Files' Section before going on!
6. Once Electron V1.7.9 is installed globally using Yarn, run the application by typing `electron .` in the project root.
7. A window should popup shortly after runnung the command.
8. Have Fun!

# Modifying Files
Before you can use this, but after installing necessary packages. Navigate to the project root in the File Explorer/Manager.

### File 1: WINTOOLS
Go to `<PROJECT_ROOT>/node_modules/wintools/lib/ps.js`. Modify LINE 11 to be `exec('wmic process list /format:csv', {maxBuffer: 2000*1024}, function (err, stdout, stderr) {`

### File 2: NODE-SPOTIFY-WEBHELPER
Go to `<PROJECT_ROOT>/mode_modules/node-spotify-webhelper/index.js`. Modify LINE 158 to be `return util.format("http://%s:%d%s", generateRandomLocalHostName(), localPort, url)`

# Requests
We are always looking for new features to add! If you have a feature request, please tell us on our Official Discord Server [Here](https://discord.gg/FUmdfB4)
