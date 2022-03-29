<p align="center">
  <img src="images/screenshot.png" height="220" width"700">
 </p>
 <p align="center">
   <img  src="https://img.shields.io/badge/license-MIT-green">
 <img  src="https://img.shields.io/badge/build-passing-brightgreen">
   <img  src="https://img.shields.io/badge/version-1.0.0-orange">
   <img  src="https://img.shields.io/badge/npm-v6.14.8-blue">
  <img  src="https://img.shields.io/badge/node-v12.18.2-yellow">
 </p>
 <br>
<p align="center">A Sample CLI tool to translate language in the terminal.</p>
<br>

<p align="center">
<img src="images/mycli.gif" alt="demonstration" height="500" width="800" >  
</p>


---

## Usage

```
~$ mycli --help
  __  __            ____   _       ___ 
 |  \/  |  _   _   / ___| | |     |_ _|
 | |\/| | | | | | | |     | |      | | 
 | |  | | | |_| | | |___  | |___   | | 
 |_|  |_|  \__, |  \____| |_____| |___|
           |___/                       

Usage: mycli -l <language>  -s <sentence>
┌────────────────────────────────────────────────┐
│                                                │
│                                                │
│   Translates a sentence to specific language   │
│                                                │
│                                                │
└────────────────────────────────────────────────┘


Options:
      --version   Show version number                                  [boolean]
  -l, --language  Translate to language                                 [string]
  -s, --sentence  Sentence to be translated                             [string]
      --help      Show help                                            [boolean]

```

> :warning: **You can also use the ISO-639-1 code of the language instead of writing the full language name**

<br>

## Installation

1. Clone the repository and then navigate to it.
2. Run ```npm install``` to install the dependencies.
3. Run ```npm install -g .``` to install the CLI. <br>

> :warning: **This might cause an error** which can be resolved easily by using ```sudo``` with the command, **however**, using ```sudo``` with ```npm``` is **not recommended** because it might cause permission issues later. So instead put the code below in your .bashrc file and then run the above command again.
```
npm set prefix ~/.npm
PATH="$HOME/.npm/bin:$PATH"
PATH="./node_modules/.bin:$PATH"
```
4. Now you are good to go and can use the CLI globally!

Type ```mycli``` or ```mycli --help``` to get started.

<br>

## License

MIT © ***MyCLI***