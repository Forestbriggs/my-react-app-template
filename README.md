# My React Vite Template

This repo exists to give a solid base template to start a React app using Vite.

## Features

* Ready to go light / dark mode based on system preferences (Only configured for background and text color, will likely need additional CSS added for other elements)

* ESLint runs on build

* Browser auto opens project on ```npm run dev``` for convenience (To disable comment out / delete ```server: { open: true }``` from vite.config.js)

* ESLint configured to not require prop-types (If using TypeScript delete ```'react/prop-types': 'off'``` from .eslintrc.cjs)

## How to clone

```
npx tiged Forestbriggs/my-react-app-template#main <new-project-name>
```

Make sure to replace ```<new-project-name>```
with your own project name.

## How to set up / install

```
cd <new-project-name>
npm install
npm run dev
```

## How to use

Change this README, the title in index.html, and the "name" in package.json to your respective needs.

Once you have added files to the 'public' directory go ahead and delete the .keep file.

Now you have a blank ready-to-use Vite React template! Happy coding!
