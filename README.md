# vim_setup
Repo containing vim setup information

Steps(old):

* Clone the vundle source code, check the [link](https://github.com/VundleVim/Vundle.vim#quick-start)
* Copy the content of `.vimrc_`(repo) in `~/.vimrc_` (local)
* Do `vim` and in command mode apply this command `:PluginInstall`

Steps(new):

* Install vim-plug.
* Copy the content of `vimrc_new` in `~/.vimrc` 
* Open vim and do PlugInstall
* `CocInstall coc-rust-analyzer coc-json coc-python`
* Check for other language supports.

