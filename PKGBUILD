# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=wallpapers-kibojoe
pkgver=1709
pkgrel=2
pkgdesc="Wallpapers for Kibojoe Linux"
arch=('any')
license=('GPL3')
url="https://github.com/kibojoe/wallpapers-kibojoe"
source=("git+$url.git")
sha256sums=('SKIP')

package() {
	cd $srcdir/$pkgname
	install -dm755 $pkgdir/usr/share
	cp -r backgrounds $pkgdir/usr/share
}