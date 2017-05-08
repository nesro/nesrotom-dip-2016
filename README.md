# install packages
    sudo apt install latexmk texlive texmaker texlive-lang-czechslovak texlive-generic-extra myspell-cs

In Texmaker, go to: Options -> Configure Texmaker-> Editor and set the dictionary.

# install vlna
    # http://petr.olsak.net/ftp/olsak/vlna/vlna-1.5.tar.gz
    ./configure
    make
    sudo make install

# create pdf
    make

# clean unnecessary files
    make clean

# books
Learning the bash Shell, 3rd Edition
https://github.com/Ricky-Wilson/Programming-books/blob/master/PDF/Learning%20the%20bash%20Shell,%203rd%20Edition.pdf

# svg to pdf
    sudo apt install librsvg2-bin
    rsvg-convert -f pdf -o FILE.{pdf,svg}

