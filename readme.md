# VirusTotal Desktop Client


This is a desktop client for virustotal
being that virustotal is cloud based, this will not work wihout internet connection

command to use:

```bash
# Clone this repository
git clone https://github.com/MXP2095onetechguy/VirusTotal-Desktop-Client.git
# Go into the repository
cd browser-demo
# Install dependencies
npm install
# Run the app
# with the npmstart.bat by running it
# or if you dont have the scripts, run:
npm start
# build app
# this step is needed if you don't have electron packager:
# For use in npm scripts (recommended)
npm install electron-packager --save-dev

# For use from the CLI
npm install electron-packager -g
# if you have electron packager or you installed it, run build.bat or this:
electron-packager . --overwrite --prune=true
```
