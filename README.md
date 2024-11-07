Repositório oficial do programa "Xarchiver"

https://github.com/ib/xarchiver/

https://github.com/ib/xarchiver/blob/master/po/pt_BR.po

- - - - -

Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/Xarchiver_pt_BR/blob/main/xarchiver_pt_BR.po

https://github.com/marcelocripe/Xarchiver_pt_BR/blob/main/xarchiver.desktop


Para utilizar o arquivo "xarchiver_pt_BR.po" e o "xarchiver.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"xarchiver_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt xarchiver_pt_BR.po -o xarchiver.mo

Comando para renomear o arquivo antigo da tradução com a extensão ".mo" que está na pasta do idioma "pt_BR".

$ sudo mv /usr/share/locale/pt_BR/LC_MESSAGES/xarchiver.mo /usr/share/locale/pt_BR/LC_MESSAGES/xarchiver_antigo.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp xarchiver.mo /usr/share/locale/pt_BR/LC_MESSAGES


"xarchiver.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp xarchiver.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
