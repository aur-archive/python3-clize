# Contributor: Francois Boulogne <fboulogne at april dot org>
# Maintainer: Francois Boulogne <fboulogne at april dot org>

pkgname=python3-clize
pkgver=1.0b
pkgrel=1
pkgdesc="This decorator will turn your normal python functions into proper shell commands"
arch=('any')
url="https://code.launchpad.net/~epsy/+junk/clize"
license=('MIT')
depends=()
source=(http://pypi.python.org/packages/source/c/clize/clize-1.0b.tar.gz#md5=500ade485dd2d76f0754dae1896233e7)
md5sums=("500ade485dd2d76f0754dae1896233e7")

build() {
  cd "$srcdir/clize-$pkgver"

  python3 setup.py install --root="${pkgdir}"

}

# vim:ts=2:sw=2:et:
