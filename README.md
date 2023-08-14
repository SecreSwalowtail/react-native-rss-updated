# react-native-rss-parser

Fix for xmldom critical vulnerability.

## Installation
1. If you have the old react-native-rss-parser package, remove it
```sh
npm remove react-native-rss-parser
```
2. Find your package.json file and add this to the list of dependecies
```js
"dependencies": {
 // Other packages...
  "react-native-rss-parser": "github:SecreSwalowtail/react-native-rss-updated",
},
```
3. Update the packages
```sh
npm install
```
4. You may need to build the types for this package, run this if react can't find the pacakge.
```sh
npm i --save-dev @types/react-native-rss-parser
```

## Usage example
See the original package for instructions: https://github.com/jameslawler/react-native-rss-parser
