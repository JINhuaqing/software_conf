### Windows system

In the windows system, you put the `.vimrc`

- under the `$HOME`  folder as `_vimrc`.

- or under the `$HOME/vimfiles`  folder as `vimrc`.

- or under the `$VIM` folder as `_vimrc`

  

### Linux system

In the linux system,  you put the `.vimrc`

- under the `$HOME` folder as `.vimrc`

- or under the `$HOME/.vim` folder as `.vimrc.`






To use the vimrc_advance file, you shall intall vim plugins manager: **vim-plug** first.

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

```

When using the config file, copy the file in the home directory, i.e., 

```bash
mv vim_xxx ~/.vimrc

```
