# ymonad

SymLinks to default config folder
```sh
ln -s stack.yaml ~/.config/xmonad/stack.yaml
ln -s app/xmonad.hs ~/.config/xmonad/stack.yaml
``` 

build & bootstrap
```sh
stack install
```

test recopilation is ok
```sh
xmonad --recompile
```
