## Creating webpack project from the scratch

Initialize new npm project (create new package.json)
```
npm init
```

Install webpack 4
```
npm install webpack
npm install webpack-cli
```

Add dev and production webpack scripts to your package.json
```
 "scripts": {
    "dev": "webpack --mode development ./src/js/main.js --output ./dist/js/main.js",
    "production": "webpack --mode production ./src/js/main.js --output ./dist/js/main.js"
  },
```

Build scripts in development mode
```
npm run dev
```