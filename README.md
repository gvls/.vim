## 2 overview
configuration for vim

### 3  install
1. configure
edit `/etc/vim/vimrc` : add `source <path of your home>/.vim/vimConfig.vim` 


2. download
```shell
cd ~
git clone https://github.com/keysquivered/.vim
```

3. install
open one text and execute `:PlugUpgrade` and `:PlugInstall` 

## 2 bug
1. `yy` can't copy `$XXX` 
2. `yy` may add `$` to end of line
