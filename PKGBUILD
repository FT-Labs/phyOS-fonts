# Maintainer: Arda Atci <phystecharda@gmail.com>

pkgname=fonts-phyOS
pkgver=1
pkgrel=1
pkgdesc="PhyOS system fonts"
arch=(any)
depends=(fontconfig xorg-font-util)
provides=("fonts-phyOS")
conflicts=("consolas-font")
source=("git+https://github.com/PhyTech-R0/fonts-phyOS")
md5sums=('SKIP')


package() {
  cd "$pkgname"
  install -dm 755 "${pkgdir}"/usr/share/fonts/TTF
  install -Dm644 *.ttf "$pkgdir"/usr/share/fonts/TTF
  install -Dm644 *.otf "$pkgdir"/usr/share/fonts/TTF
}
