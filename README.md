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
   npm install or npm i
   ```

5. Fix any vulnerabilities

   ```
   npm audit fix --force
   ```

6. Run the following to create/update style.css if:
      <ol type="a">
      <li> its not already created</li>
      <li> you want to purge unused tailwind classes from style.css</li>
      <li> updating to newer version of tailwindcss manually</li>
      </ol>
      <br />

   ```
   npm run build
   ```

7. This starter comes with it's own live-server package. Running the command below sets up a local live-server instance at port `8080` while also watching for markup or style changes applied to any `.html` files in root, and changes made in the `assets/css` directory.

   ```
   npm run serve
   ```

   If you have a preferred, or are using your own, local live server tool simply run your server and use `npm run watch` to just watch for changes in any `.html` file and changes made in the `assets/css` directory.

8. Start editing the `index.html` inside the `public` directory, by adding content and tailwind classes. The page in your browser should update automatically every time you save your changes.

9. Have fun playing around with TailwindCSS!

## VS Code Extras

There are two extension I recogmend for VS Code in order to greatly aid you in your TailwindCSS design:

1. Tailwind CSS IntelliSense, by Brad Cornes `bradlc.vscode-tailwindcss`. It provides great amount of intelliSense for tailwind including color thumbnails when selecting colors.
2. Headwind by Tyan Heybourn `heybourn.headwind`. Headwind re-sorts your tailwind classes every time you save, keeping a structured order to the classes.
   `

## Docs

I have no other documentaion for this repo.

If you need the TailwindCSS docs you can find them here [tailwindcss.com](https://tailwindcss.com).

If you want a quick and dirty tailwind cheat sheet, there is a relatively good one at [nerdcavecave.com](https://nerdcave.com/tailwind-cheat-sheet)
