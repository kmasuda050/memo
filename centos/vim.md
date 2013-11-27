```bash
sudo yum install ctags
ssh-keygen -t rsa
cat .ssh/id_rsa.pub 
git clone git@github.com:matsuko/config.git
ln -s config/.screenrc 
ln -s config/.vimrc 
mkdir -p ~/.vim/bundle
mkdir -p ~/.vim/swap
mkdir -p ~/.vim/ftplugin

echo -n -e \
"set expandtab\n"\
"set tabstop=2 shiftwidth=2 softtabstop=2\n"\
"set autoindent" >  ~/.vim/ftplugin/ruby.vim

git clone git://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim
```
