# npm-workspaces
Test npm 7.0 workspaces with typescript.

### Before you use this repo

Check that your npm version is at least 7.0:

```
npm -v
```

if not upgrade it.

### Installation

Run `npm install` at root level and in all packages folders.

### Check workspace implem

```
cd ./packages/app
npm run build
npm run start
```

In the console you should see: "This is a print from the shared folder".
