# logcat.tmLanguage

Colorize log to let you focus on the important things.  
Above all, colors make me happy.

See the `.YAML-tmLanguage` files for documentation.  
They should be self-explanatory.

It's recommended to use [MattDMo/Neon-color-scheme](https://github.com/MattDMo/Neon-color-scheme) for the best result ([PR pending](https://github.com/MattDMo/Neon-color-scheme/pull/20)). It is a great color scheme BTW.

## Usage

1. Copy the `.tmLanguage` files to your `Packages/User`
2. <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
3. `ss logcat`
4. Select the logcat format
5. Enjoy

## Screenshots

* `brief` (default)  
![breif](https://raw.github.com/leesei/logcat.tmLanguage/master/screenshots/brief.png)
* `time`  
![time](https://raw.github.com/leesei/logcat.tmLanguage/master/screenshots/time.png)
* `threadtime`  
![threadtime](https://raw.github.com/leesei/logcat.tmLanguage/master/screenshots/threadtime.png)

## Background

I would like to do highlight on logcat logs files I've captured. [ADBView](https://packagecontrol.io/packages/ADBView) was too much for me.  
I used to use its syntax file for some time but then I have some `-v threadtime` logs at hand (ADBView only supports `-v time`).

I've hence written syntax file for logcat from scratch with [AAAPackageDev](https://packagecontrol.io/packages/AAAPackageDev).

## TODO

* Add to Package Control. See :  
  - [JavaScriptNext - ES6 Syntax - Packages - Package Control](https://packagecontrol.io/packages/JavaScriptNext%20-%20ES6%20Syntax)
  - [Babel - Packages - Package Control](https://packagecontrol.io/packages/Babel)
* Add own color scheme. See :  
  https://github.com/SublimeText-Markdown/MarkdownEditing
* port to other editors:  
  - http://ace.c9.io/#nav=higlighter
  - http://highlightjs.readthedocs.org/en/latest/language-guide.html
  - http://codemirror.net/doc/manual.html#modeapi
  - https://github.com/codemirror/CodeMirror/blob/master/mode/gfm/gfm.js
  - https://github.com/espadrine/ace2cm

## License

MIT
