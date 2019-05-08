# ZSH Profile for WSL (and Ubuntu?)

1. Install and configure the [Deja Vu Sans Mono Powerline Font](https://github.com/Lokaltog/powerline-fonts)
2. Run the following commands

```sh
sudo apt-get install zsh
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

3. Insert the following at the beginning of `.bashrc`


```bash
# Launch Zsh
if [ -t 1 ]; then
    exec zsh
fi
```
