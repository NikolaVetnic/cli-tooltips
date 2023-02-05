# CLI Tooltips

A set of tips and advices for the CLI tools I often use.

To access CLI tools regardles of the current working directory remember to use **aliases** in `.zshrc`.

## General Settings

### Aliases

Some of the aliases I find useful:
```
	alias ls='ls -la --color=auto'
	alias mc='/opt/homebrew/Cellar/midnight-commander/4.8.29_1/bin/mc'
	alias brew='/opt/homebrew/bin/brew'
	alias nf='/opt/homebrew/Cellar/neofetch/7.1.0/bin/neofetch'
	alias echo_path='echo $PATH | sed '\''s/:/\n/g'\'' | sort | uniq -c'	
```

### Other `.zshrc` Settings

More useful settings:
```
	# setting the ls colors
	export LSCOLORS="GxfxcxdxDxegedabagacad"
```

## Tooltips

Splitting a ZIP archive into `50M` sized parts:
```
	zip existing.zip --out new.zip -s 50m

```

## CLI Tools 

### bat

Link: [https://github.com/sharkdp/bat](https://github.com/sharkdp/bat)

### cmatrix

Link: [https://formulae.brew.sh/formula/cmatrix](https://formulae.brew.sh/formula/cmatrix)

### cmus

Instructions: [cmus.md](cmus.md)  
Link: [https://formulae.brew.sh/formula/cmus](https://formulae.brew.sh/formula/cmus)  

### gtop

Link: [https://www.cyberciti.biz/howto/gtop-awesome-system-monitoring-dashboard-for-terminal/](https://www.cyberciti.biz/howto/gtop-awesome-system-monitoring-dashboard-for-terminal/)

### nvim

Instructions: [neovim.md](neovim.md)  
Link: [https://neovim.io/](https://neovim.io/)  
Setup video: [https://www.youtube.com/watch?v=JWReY93Vl6g](https://www.youtube.com/watch?v=JWReY93Vl6g)  
`init.vim` as shown in the setup video: [config/init.vim](config/init.vim)  
Comparison - vim and nvim: [https://www.youtube.com/watch?v=R8tI4gpzkE4](https://www.youtube.com/watch?v=R8tI4gpzkE4)  

### Midnight Commander

Instructions: [mc.md](mc.md)  
Link: [https://midnight-commander.org/](https://midnight-commander.org/)

### neofetch

Link: [https://www.cyberciti.biz/howto/neofetch-awesome-system-info-bash-script-for-linux-unix-macos/](https://www.cyberciti.biz/howto/neofetch-awesome-system-info-bash-script-for-linux-unix-macos/)

## Non-CLI Tools

### Stats

Link: [https://github.com/exelban/stats](https://github.com/exelban/stats)
