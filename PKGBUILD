# Maintainer: Tang Yuming <felinae225@qq.com>
pkgname=clashup
pkgver=0.2.4
pkgrel=2
pkgdesc="auto update clash's config file"
license=('GPL')
arch=('any')
url="https://github.com/felinae98/clashup"
depends=(python
         clash
         python-requests)
source=(clashup clashup.conf)
package() {
    install -Dm755 clashup ${pkgdir}/usr/bin/clashup
    install -Dm644 clashup.conf ${pkgdir}/etc/systemd/user/clash.service.d/clashup.conf
}
md5sums=('e1a19cb6d725946a94aac9134b33b584'
         '177338346005e11d33e27edc1f8ab780')
