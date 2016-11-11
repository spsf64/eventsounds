# Maintainer: Sergio Schneider <ss@xxx.xxx>

pkgname=eventsounds
pkgver=1.0
pkgrel=1
depends=('libcanberra' 'libcanberra-gstreamer' 'libcanberra-pulse')
pkgdesc="Event sounds for XFCE and Mate"
arch=('any')
source=(https://github.com/spsf64/eventsounds/raw/master/eventsounds.zip)
#install=$pkgname.install
md5sums=('SKIP')
url="https://github.com/spsf64/eventsounds"
license=('unknown')

package() {
  mkdir -p $pkgdir/usr/share/sounds/freedesktop/stereo/
  #unzip pkgname
  cp -f $srcdir/*.og* $pkgdir/usr/share/sounds/freedesktop/stereo/
}

