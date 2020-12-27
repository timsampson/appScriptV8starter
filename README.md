# Basic Web App [![clasp](https://img.shields.io/badge/built%20with-clasp-4285f4.svg)](https://github.com/google/clasp)

[Example Site URL](https://script.google.com/a/macros/dishs.tp.edu.tw/s/AKfycbxVF3ohFTl_Y6KkQ8R8Vyv5O9jxvjPWvRTltdiERLA4NU-UFPoI/exec)

This is a starter project for web app which uses clasp to deploy modern Javascript to Google's Apps Script (GAS) projects V8 engine. I was finding it difficult to keep up with teh best right default settings for tsconfig and eslint.  I will use this repository to keep track of the most up to date options for getting started with modern Javascript features in the V8 engine, the web and use Typescript in development for Google Apps Script Projects. If you find this helpful, that's great.

Clone the repo, run `npm install`, install Clasp globally `npm install @google/clasp -g` and if prompted for a dependency, inquirer@^6.0.0,  run `npm install inquirer@^6.0.0 -g`.  If you use a codespace, this is configured already, but you will still need to login once the codespace is created.

If you are using Codespaces, Log in to clasp `clasp login --no-localhost`, othewise you can use clasp login at the terminal. Clasp will be installed when the Codespace is initially setup.

Delete the existing .clasp.json file and then create your starter web app: `clasp create --type webapp --title "Your Title" --rootDir ./appsscript`

It includes the starter template for [Bootstrap 5](https://v5.getbootstrap.com/) with the sticky footer and the .devcontainer for Node and Javascript Projects for [Github Codespaces](https://docs.github.com/en/github/developing-online-with-codespaces).

# References and Related Links
If you want to dive deeper and encorporate Google Sheets, you should  watch this Youtube tutorial on Google Sheets being used as a backend for an Apps Script Web App by [Learn Google Spreadsheets on Youtube](https://www.youtube.com/playlist?list=PLv9Pf9aNgemt82hBENyneRyHnD-zORB3l).

[Command Line Interface using clasp](https://developers.google.com/apps-script/guides/clasp)

[Clasp's GitHub TypeScript guide](https://github.com/google/clasp/blob/master/docs/typescript.md)

[Stack Overflow post about compiler options](https://stackoverflow.com/questions/42093758/need-clarification-of-the-target-and-lib-compiler-options)
