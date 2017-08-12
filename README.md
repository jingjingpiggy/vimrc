vimrc
=====

my vimrc config

Installation
============
    git clone https://github.com/pyKun/vimrc ~/.vim
    cp ~/.vim/.vimrc ~/
    cd ~/.vim/
    git submodule init
    git submodule update

    For Linux os:
    sudo apt-get install exuberant-ctags

    For mac os:
    brew install ctags-exuberant
    pip install pyflakes
    /usr/local/bin/ctags -R --exclude='.svn'

    For YouCompleteMe issue:
    sudo find / -name _io.so

    cd Desktop
    mkdir backup_python
    cp /usr/local/Cellar/python/2.7.13/Frameworks/Python.framework/Versions/2.7/lib/python2.7/lib-dynload/_io.so backup_python/2.7.13_io.so

    cp /System/Library/Frameworks/Python.framework/Versions/2.7/lib/python2.7/lib-dynload/_io.so /usr/local/Cellar/python/2.7.13/Frameworks/Python.framework/Versions/2.7/lib/python2.7/lib-dynload/_io.so
