# vim-cpp
Vim setup as C/C++ IDE 

1. install vim-plug (you can find instructions on the internet) - i.e. using this command:

curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    
2. copy .vimrc to your home directory:

cp .vimrc ~/

3. create directory for vim:

mkdir ~/.vim

4. copy coc-settings.json to this directory:

cp coc-settings.json ~/.vim/

Now you need to run vim and wait until vim downloads all necessary files, you can check progress by typing:

:PlugInstall

After vim finish, close it and run again. 

Some useful tips how to use vim you can find in file tips_and_tricks.txt. 
