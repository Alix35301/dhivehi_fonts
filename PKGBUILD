# Maintainer: Ali Hassan alix35301@gmail.com

pkgname=dhivehi_fonts
pkgver=1.0
pkgrel=1
pkgdesc="Dhivehi fonts for arch ttf, otf"
url="https://adobe-fonts.github.io/source-code-pro"
arch=(any)
license=(common)
_tarname=dhivehi_fonts
source=("$_tarname.tar.gz::https://github.com/adobe-fonts/source-code-pro/archive/$_relver.tar.gz")

package() {
  cd $_tarname
  install -d "$pkgdir/usr/share/fonts/${pkgname%-fonts}"
  install -t "$pkgdir/usr/share/fonts/${pkgname%-fonts}" -m644 OTF/*.otf
  install -Dm644 LICENSE.txt "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}

# vim:set ts=2 sw=2 et:
