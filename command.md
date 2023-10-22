# Dependencias

1 = sudo apt install powerline fonts-powerline

# Commands

1 = sudo mkdir /usr/local/bin/powerline

2 = sudo git clone https://github.com/powerline/powerline.git /usr/local/bin/powerline/

3 = sudo wget https://github.com/powerline/powerline/raw/develop/font/PowerlineSymbols.otf -O /usr/share/fonts/PowerlineSymbols.otf

4 = sudo wget https://github.com/powerline/powerline/raw/develop/font/10-powerline-symbols.conf -O /etc/fonts/conf.d/10-powerline-symbols.conf

5 = sudo echo '. /usr/local/bin/powerline/powerline/bindings/bash/powerline.sh' >> ~/.bashrc


# estalation script

1 = sh -c "$(wget [https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh] https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

