#Leaflet Maps Demo
History and steps for tutorial are in seperate git commits.

##Setup for the Project:
You need to have node.js and npm (node package manager) installed.
You need to have `bower` installed (`npm install -g bower`) to pull in the project's dependencies. After bower is installed run `bower install`.
You need to have BrowserSync installed for the live-reloading and web server (`npm install -g browser-sync`).

##BrowserSync:
Run `browser-sync start --server --files "assets/scripts/*.js,assets/styles/*.css,index.html"` to get BrowserSync started.
