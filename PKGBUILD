# Maintainer: VHSgunzo <vhsgunzo.github.io>
pkgname='template'
pkgver='0.0.1'
pkgrel='1'
pkgdesc='Rust nightly template x86_64-unknown-linux-musl'
arch=("x86_64")
url='https://github.com/VHSgunzo/template'
provides=("${pkgname}")
conflicts=("${pkgname}")
source=("${pkgname}::https://github.com/VHSgunzo/${pkgname}/releases/download/v${pkgver}/${pkgname}")
sha256sums=('SKIP')

package() { install -Dm755 ${pkgname} "$pkgdir/usr/bin/${pkgname}" ; }
