React needs a bundler for optimizing before things go to the production.
Available bundlers includes vite and webpack and parcel etc.

We are using parcel in this project .
npm instal -D parcel, -D is a developer dependency.
whats the difference between package.json and package-lock.json?
**package.lock-json locks the version of the dependency the program built upon**
**NEVER PUT PACKAGE-LOCK.JSON IN GIT IGNORE**
**BUT MAKE SURE TO PUT NODE_MODULES INTO GIT INGNORE**

WE CAN GENERATE NODE MODULES USING PACKAGE-LOCK.JSON AND PACKAGE-JSON.




Tildee ~ and caret ^ in package.json?
~version “Approximately equivalent to version”, will update you to all future patch versions, without incrementing the minor version. ~1.2.3 will use releases from 1.2.3 to <1.3.0.

^version “Compatible with version”, will update you to all future minor/patch versions, without incrementing the major version. ^1.2.3 will use releases from 1.2.3 to <2.0.0.


**PARCEL SUPREMACY**
**//HMR ( HOT MODULE REplacement)
FILE WATCHER ALGORITHMS WRITTEN IN C++ //REFLECTS THE CHANGES AS SOON AS YOU MAKE THE CHANGES
caching
iMAGE LOADING
MINIFY
RENAME
COMPRESSION
COMPATIBLE TO OLDER VERSION OF BROWSERS
WE ENABLES US TO HTTPS IN LOCALHOST
**

**WE SHOULD PUT PARCEL CACHE IN GIT IGNORE
**

**EVERYTHING WE CAN GENERATE IN SERVER SHOULD BE PUT IN GIT IGNORE**
