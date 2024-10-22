## Personalize seu editor VIM 

# 1. Crie ou edite o arquivo vimrc:
$ vim ~/.vimrc

# 2. Após adicionado todo o conteúdo ao seu vimrc, instale o vim-plug:
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

# 3. Depois, adicione a seguinte configuração ao seu .vimrc para usar plugins:
call plug#begin('~/.vim/plugged')

" Exemplo de plugin para melhor navegação
Plug 'scrooloose/nerdtree'

call plug#end()

# 4. Para instalar os plugins:
Abra o Vim e execute :PlugInstall
