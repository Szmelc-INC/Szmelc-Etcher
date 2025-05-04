# Maintainer: SilverX <serainox@gmail.com>
pkgname=setch
pkgver=1.0
pkgrel=1
pkgdesc="Szmelc Etcher: Simple ISO-to-USB flasher using dialog and dd"
arch=('any')
url="https://github.com/Szmelc-INC/Szmelc-Etcher"
license=('MIT')
depends=('bash' 'dialog' 'pv' 'coreutils' 'util-linux')
makedepends=('git')
source=("git+$url.git#branch=main")
md5sums=('SKIP')

package() {
  cd "$srcdir/Szmelc-Etcher"
  install -Dm755 setch "$pkgdir/usr/bin/setch"
}
