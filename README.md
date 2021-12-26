<h1 style="color:#FFD100;text-shadow: -2px 2px #000028;font-size:40px", align="center">Setup2Go</h1>

<h3 align="center">My script to easily install all the programs of my environment in other environment</h4>

---
### I have not tested this script yet, so use it wisely and knowing what you're doing please! 
---

## <a name="why"></a>Why? 🛸
I thought that to make transitions to other machines easier, could be a good idea to make a script to install all the things that I need.

## <a name="how"></a>How? 🧪
This script will install brew and, after that, the following stuff:
- `git`
- `wget`
- `watch`
- `gh`
- `bottom`
- `kalker`
- `dust`
- `pyenv`
- `vlang`
- `deno`
- `httpie`
- `dtool`
- `vim`
- `iterm2` **`Cask`**
- `visual-studio-code` **`Cask`**
- `tunnelblick` **`Cask`**

It will also copy a custom `.zshrc`, `.zprofile`, `.zshenv`, `.p10k.zsh` files and create a `.hushlogin` file in the home directory

However **for more detailed information** [check out the script's source code!](https://github.com/ItsTheGuy/Setup2Go/tree/main/main.abs)


## <a name="run"></a>Run! 🚀
In order to run this script, make sure you have `abs-lang` installed. After that run `abs main.abs` and the script should be running!