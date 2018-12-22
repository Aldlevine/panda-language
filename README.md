# VSCode Panda Language

This extension provides language features for the [Panda BT](http://www.pandabehaviour.com/). Currently it only provides basic syntax highlighting. If there is interest, features may be added to include, for example, IntelliSense for task autocompletion.

## Installation

### From Source

1. Clone the repo
2. cd into the repo dir
3. `$ npm install`
4. `$ npm run build`
5. This should create a file in the repo root named `panda-language-#.#.#.vsix`. _Note #.#.# will be replaced with the actual version number._
6. In VSCode open the extensions sidebar and click the "3 dots" menu in the top right of the extensions menu.
7. Select "_Install from VSIX..._" and select the file that was built.
8. Restart VSCode and enjoy!

### From Prebuilt VSIX

1. Download the latest VISX file from the repo's _Releases_ tab on Github.
2. Follow steps 6-8 in the "From Source" instructions.

## Notes

Since Panda scripts must be TextAssets and Unity only supports specific file-extensions as TextAssets (Panda uses `.txt`). This has been designed to expect a pseudo-file-extension `.BT.txt`. If this doesn't fit your workflow/current project, VSCode allows you to set up [custom file associations](https://stackoverflow.com/a/36789145).

## Contributing

Issues are more than welcome, but PRs are preferred as I won't always have the time to address issues quickly.