# Maintainer: Federico Damián <federicodamians@gmail.com>
#
# PKGBUILD for Emerald KDE Icon Theme
#

pkgname=emerald-icon-theme-kde
pkgdesc="Clean and fresh icons theme. Based on Flattr (Nitrux OS) and Breeze (Plasma 5) icon themes. More KDE integrated version."
pkgver=2.0
pkgrel=3
arch=('any')
url="http://kde-look.org/content/show.php/Emerald+KDE?content=169001"
license=('CC BY-NC-SA 4.0')
makedepends=('p7zip')
optdepends=()
source=('http://kde-look.org/CONTENT/content-files/169001-Emerald-kde.7z')
md5sums=('SKIP')

package() {

  install -d -m 755 "$pkgdir"/usr/share/icons/Emerald
  install -d -m 755 "$pkgdir"/usr/share/icons/Emerald-Dark

  cd $srcdir/Emerald
  cp -r . "$pkgdir"/usr/share/icons/Emerald/
  cd $srcdir/Emerald-Dark
  cp -r . "$pkgdir"/usr/share/icons/Emerald-Dark/
}
