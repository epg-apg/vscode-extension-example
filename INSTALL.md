# Building this extension
This extension must be packed with the [Visual Studio Extension](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) tool `vsce`. First of all, make sure you have [Node.js](https://nodejs.org/) installed.

Then install `vsce`:

```
npm install -g vsce
```

To build this extension, run `vsce package` from the command line.

```
vsce package
```