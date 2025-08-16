# Maintainer: @zstg <zestig@duck.com>
pkgname=stratos-grub
pkgver=1.0
pkgrel=1
pkgdesc="GRUB configuration for StratOS"
arch=('any')
license=('GPL3')
depends=('grub')
source=()
install=stratos-grub.install
prepare() {
    cp -r "$startdir/usr/" "$srcdir"
    echo $srcdir
}
package() {
    install -d "$pkgdir/usr/share/grub/themes/"
    cp -r "$srcdir/usr/share/grub/themes/StratOS/" "$pkgdir/usr/share/grub/themes/"
}