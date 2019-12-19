Placeholder for misc linux config files

- for vim configs please install vundle and some themes
- for tmux memory usage please install
- tmux-ressurect:
```
  git clone https://github.com/tmux-plugins/tmux-resurrect ~/.tmux/tmux-resurrect
```
- tmux-mem-cpu:
```
  git clone https://github.com/thewtex/tmux-mem-cpu-load.git ~/.tmux/tmux-mem-cpu
  cd ~/.tmux/tmux-mem-cpu
  cmake .
  make
  su -
  make install
  logout
```
- have powerline fonts installed: https://github.com/powerline/fonts#installation
```
  git clone https://github.com/powerline/fonts.git --depth=1
  cd fonts
  ./install.sh
  cd ..
  rm -rf fonts
```

Feel free to use these configs as you please
