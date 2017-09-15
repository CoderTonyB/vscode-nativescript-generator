![](images/icon.png)

# VS Code Angular Native Add Files

This extension allows you to add **Angular Native (NativeScript + Angular 2) typescript files including snippets** to your VS Code project.

> Forked from[Sebastian Baar](https://github.com/sebastianbaar/vscode-add-angular2-files) VS Code Add Angular2 Files

## Changelog

## 0.0.5

## Features

Right click on a file or a folder in your current project. There are two options added to the context menu `Add Angular2 Files` and `Add Angular2 Files (Extended)`:

### Add Angular2 Files

This command adds the following files to your new folder (let's assume you typed in `home`):
```
home/home.component.ts
home/home.component.html
home/home.component.css
home/home.component.spec.ts
```

![alt text](https://cloud.githubusercontent.com/assets/7135276/16797373/83bd9ffc-48e7-11e6-9ac0-9874a4387a3a.gif "Add Angular2 Files")

### Add Angular2 Files (Extended)

This command adds the following extended files to your new folder (let's assume you typed in `home`):
```
home/home.component.ts
home/home.component.html
home/home.component.css
home/home.component.spec.ts
home/shared/home.service.ts
home/shared/home.ts
```

![alt text](https://cloud.githubusercontent.com/assets/7135276/16797375/861bd246-48e7-11e6-8cc8-2fc688197388.gif "Add Angular2 Files (Extended)")

**The naming of the files as well as the (boilerplate) snippets are based on the [official Angular2 Style Guide](https://angular.io/docs/ts/latest/guide/style-guide.html)**

## Installation

1. Install Visual Studio Code 1.3.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Type `add angular2 files` and press enter
6. Reload Visual Studio Code

# Disclaimer

**Important:** This extension due to the nature of it's purpose will create
files on your hard drive and if necessary create the respective folder structure.
While it should not override any files during this process, I'm not giving any guarantees
or take any responsibility in case of lost data.

# License

MIT
"# vscode-nativescript-generator" 
