fernsvim

========

my vim configuration

git clone https://github.com/fernsfan/fernsvim.git

You should upgrade your vim to 7.3+ for this vimrc

***Install Vim 7.3***
tar xvjf vim-7.3.tar.bz2 
cd vim-7.3
./configure --with-features=huge --enable-pythoninterp --enable-rubyinterp --enable-perlinterp
--enable-tclinterp   --enable-multibyte --enable-cscope --disable-gui
(export LD_LIBRARY_PATH=/usr/local/lib/:$LD_LIBRARY_PATH)
	make
	make install

***Install Ctags&Cscope***
yum list ctags cscope
yum install ctags cscope

**Install [[astyle**]]
yum install gcc-c++
tar xvzf astyle_2.03_linux.tar.gz
cd astyle/build/gcc
make
make [[install]]

after git clone this repo, you should do several steps for use vim normally:
1)   git clone http://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
2)   go into vim: BundleUpdate

