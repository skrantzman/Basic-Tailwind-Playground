![GitHub package.json version](https://img.shields.io/github/package-json/v/skrantzman/Basic-Tailwind-Playground?logo=github) &ensp;
![GitHub package.json dependency version (prod)](https://img.shields.io/github/package-json/dependency-version/skrantzman/Basic-Tailwind-Playground/tailwindcss?color=38B2AC&logo=tailwind-css) &ensp;
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/skrantzman/dnn_tailwind?logo=Snyk)

# Basic-Tailwind-Playground

Basic Tailwind Playground, that saves a few minutes of having to configure package.json, postcss.config.js, and tailwind.config.js files, so you can be up and running quickly. Nothing special here other than that.

## Installation

1. Run the following to clone this repository locally.

   ```
   git clone https://github.com/skrantzman/Basic-Tailwind-Playground.git
   ```
2. Change directory to the newly cloned reposityry.
   ```
   cd Basic-Tailwind-Playground
   ```
3. Open the projec in VS Code.
   ```
   code .
   ```
4. From VS Code Terminal run the following to install all dependencies.

   ```
   npm install
   ```

5. Run the following to create style.css if its not already created, or if updating to newer version of tailwindcss manually. You will also want to run this command every time you edit and save your tailwind.config.css file to rebuild your style.css file

   ```
   npm run build
   ```

6. If you don't have Live Server installed either install it as a VS Code extension or add it to your dev environment globally. If you already have it installed skip this step.

   ```
   npm install -g live-server
   ```

7. If you have Live Server installed as a VS Code Extension, right click on index.html (in the public folder) and select "Open With Live Server". if you have Live Server installed globally in your dev environment, run the following command

   ```
   live-server public
   ```

   This should open a browser window for ip address 127.0.0.1 on port 8080.

8.  Have fun playing around with TailwindCSS!

## VS Code Extras

There are two extension I recogmend for VS Code in order to greatly aid you in your TailwindCSS design:

1. Tailwind CSS IntelliSense, by Brad Cornes `bradlc.vscode-tailwindcss`. It provides great amount of intelliSense for tailwind including color thumbnails when selecting colors.
   
2. Headwind by Tyan Heybourn `heybourn.headwind`. Headwind re-sorts your tailwind classes every time you save, keeping a structured order to the classes.
` 

## Docs

I have no other documentaion for this repo.

If you need the TailwindCSS docs you can find them here [tailwindcss.com](https://tailwindcss.com).

If you want a quick and dirty tailwind cheat sheet, there is a relatively good one at [nerdcavecave.com](https://nerdcave.com/tailwind-cheat-sheet)
