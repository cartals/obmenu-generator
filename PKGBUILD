# Maintainer: Trizen <echo dHJpemVueEBnbWFpbC5jb20K | base64 -d>

pkgname=obmenu-generator
pkgver=0.58
pkgrel=1
pkgdesc="A fast pipe/static menu generator for the Openbox Window Manager (with icons support)."
url="http://trizenx.blogspot.ro/2012/02/obmenu-generator.html"
arch=('any')
license=('GPLv3')
depends=('openbox' 'perl>=5.14.0' 'perl-data-dump' 'perl-linux-desktopfiles>=0.08')
source="http://trizen.googlecode.com/files/$pkgname-$pkgver.tar.gz"
md5sums=('8a9369c3e64f8f153af3840f58f1239f')

package() {
  install -Dm 755 "$pkgname" "$pkgdir/usr/bin/$pkgname"
}
