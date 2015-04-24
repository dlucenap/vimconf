vimconf
=======

Vim configuration

Incluye:
* jedi-vim: autocompletion para python
* nerdtree: Gestor de archivos (pulsar F7)
* pytest.vim: Corre tus tests desde vim. <ESC><SPACE>f por ejemplo
* tagbar: Listado de funciones (pulsar F8)
* vim-git: Mejora del formato de mensajes de commit git
* vim-javascript: syntax higlight e indentaci�n para JS
* vim-py-encoding: Codificaci�n de archivos vim seg�n pep263
* vim-python-pep8-indent: Indentaci�n python seg�n pep8

Para usarlo:
git clone https://github.com/srlobo/vimconf.git
ln -s vimconf/vim .vim
ln -s vimconf/vimrc .vimrc
cd vimconf
git submodule init
git submodule update
cd jedi-vim
git submodule init
git submodule update



