# Basic-Tailwind-Playground

Basic Tailwind Playground, that save a few minutes of having to configure package.json, postcss.config.js, and tailwind.config.js files. Nothing special here.

## Installation

1. Run the following to clone repository locally.

   ```
   git clone https://github.com/skrantzman/Basic-Tailwind-Playground.git
   ```

2. Run the following to install all dependencies.

   ```
   npm install
   ```

3. Run the following to create style.css if not already created or if updating to newer version of tailwindcss

   ```
   npm run build
   ```

4. If you don't have Live Server installed either install it as a VS Code extension or add it to your dev environment globally. If you already have it installed skip this step.

   ```
   npm install -g live-server
   ```

5. If you have Live Server installed as a VS Code Extension, right click on index.html (in the public folder) and select "Open With Live Server". if you have Live Server installed globally in yourS dev environment, run the following command

   ```
   live-server public
   ```

   This should open a browser window for ip address 127.0.0.1 on port 8080.

6. Have fun playing around with TailwindCSS!
