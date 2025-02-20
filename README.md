# Beautiful shell

<h3 align="left">
Welcome to my shell config 
</h3>

## Dependencies

- [kitty](https://sw.kovidgoyal.net/kitty/) - The fast, feature-rich, GPU based terminal emulator/
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) -A maintained, feature-rich and performance oriented, neofetch like system information tool.
- [zsh](https://zsh.sourceforge.io/) - is a shell designed for interactive use, although it is also a powerful scripting language.
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Fish shell like syntax highlighting for Zsh.
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - Fish-like autosuggestions for zsh 

## Usage
Clone the repository

```sh
git clone https://github.com/IsNotAcceptable/beautiful-shell.git
```

Move ``.zshrc`` into ``$HOME``

```sh
cd beautiful-shell
mv home/.zshrc ~/
```
Move the files in the ``home/.config`` folder to ``~/.config``

```sh
mv home/.config/fastfetch ~/.config && mv home/.config/kitty ~/.config
```
