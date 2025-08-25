# vsix-downloader-webui

A Simple WebUI Created with Tailwind for Fetching VSCode Extensions VSIX files from the Marketplace.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square)](https://www.javascript.com)

## !! Notice

You CAN Enable VSIX Download on Marketplace with a simple ublock origin rule:

```adblock
marketplace.visualstudio.com##+js(rpnt, script, /"(DisableVSCodeDownloadButtonEnabled|Microsoft\.VisualStudio\.Services\.Gallery\.DisableVSCodeDownloadButton)":true/, "$1":false)
```

Thanks to [ysfcn](https://gist.github.com/wanglf/7acc591890dc0d8ceff1e7ec9af32a55?permalink_comment_id=5626972#gistcomment-5626972)

## How to use

1. Visit the github pages website:

    [![Visit VSIX Downloader Page 🔌](https://img.shields.io/badge/VSIX%20Downloader%20🔌-8A2BE2)](https://cypherpunksamurai.github.io/vsix-downloader-webui//)


3. Search for your extension 🔍 or paste your extension url from vscode marketplace.

4. Click the download button! 👇

## Development

### GitHub Pages Deployment

This project includes a GitHub Actions workflow that automatically deploys the website to GitHub Pages whenever changes are pushed to the main branch. The workflow:

1. Checks out the repository code
2. Copies the files to the gh-pages branch
3. Deploys the content to GitHub Pages

To manually trigger a deployment, you can run the workflow from the "Actions" tab in your GitHub repository.

## Credits
- These Two StackOverflow Questions [\[1\]](https://stackoverflow.com/questions/37071388/how-can-i-install-visual-studio-code-extensions-offline/68078721#68078721) [\[2\]](https://stackoverflow.com/questions/79359919/how-can-i-manually-download-vsix-files-now-that-the-vs-code-marketplace-no-long)
