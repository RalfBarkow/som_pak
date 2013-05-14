# Maintainer: Nicholas Helke <nhelke@gmail.com>
pkgname=som_pak
pkgver=3.1
pkgrel=1
pkgdesc="The Self-Organizing Map Program Package"
url="http://www.cis.hut.fi/research/som_pak/"
arch=('x86_64' 'i686')
license=('custom')
source=("http://www.cis.hut.fi/research/som_pak/som_pak-3.1.tar" "http://mike.eire.ca/wp-content/uploads/2012/02/som_pak.txt" "som_pak.txt.patch")
md5sums=('ec95d1d637e7cee648a1dca90926bfe1'
         '92530a1382398e52183d3164ad36a797'
         'd535ec9aa4400041df6399cb28f7957b')

build() {
	cd $srcdir;
	patch -bp0 < som_pak.txt;
	patch -bp0 < som_pak.txt;
	cd $srcdir/$pkgname-$pkgver;
	make -f makefile.unix;
}
