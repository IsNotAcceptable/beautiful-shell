# Beautiful shell

<h3 align="left">
Welcome to my shell config =^_^=
</h3>

## Dependencies

- [kitty](https://sw.kovidgoyal.net/kitty/) - The fast, feature-rich, GPU based terminal emulator/
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) -A maintained, feature-rich and performance oriented, neofetch like system information tool.
- [zsh](https://zsh.sourceforge.io/) - is a shell designed for interactive use, although it is also a powerful scripting language.
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Fish shell like syntax highlighting for Zsh.
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - Fish-like autosuggestions for zsh 

##
Don't forget to use zsh as the default shell.
##

## Usage
Clone the repository ``Beautiful-shell``

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

## For complete beauty
Clone the repository ``powerlevel10k``

```sh
git clone https://github.com/romkatv/powerlevel10k.git
```
Install everything according to the [instructions](https://github.com/romkatv/powerlevel10k)

Type ``p10k configure`` if the configuration wizard doesn't start automatically

```sh
p10k configure
```

List of responses for configuration wizard

| Question                                               | answer           | 
|--------------------------------------------------------|:----------------:|
| `Does this look like a diamond (rotated square)?`      | `Yes`            | 
| `Does this look like a lock?`                          | `Yes`            |
| `Does this look like an upwards arrow?`                | `Yes`            |
| `What digit is the downwards arrow pointing at?`       | `1`              | 
| `Do all these icons fit between the crosses?`   | `Yes`  |
| `Prompt Style`   | `1`   |
| `Character Set`   | `1`  |
| `Prompt Colors`   | `1`  
| `Show current time?`   |  `2`
| `Prompt Height`   | `2`
| `Prompt Connection`   | `2`
| `Prompt Frame`   | `4`
| `Connection & Frame Color`   | `4`
| `Prompt Spacing`   | `2`
| `Icons`  | `2`
| `Prompt Flow`   | `2`
| `Enable Transient Prompt?`   | `No`
| `Instant Prompt Mode`   | `1`
| `Powerlevel10k config file already exists.`   | `Yes`
| `Apply changes to ~/.zshrc?`   | `Yes`







<h6 align="right">
  IsNotAcceptable
</h6>










