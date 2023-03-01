# Maintainer: mauriciodelima.mol@gmail.com

pkgname=uaiso-wallpapers-orion
pkgver=$(date +%y.%m.%d)
pkgrel=$(date +%H%M)
pkgdesc="Package Base for UaiSO21"
arch=('any')
url="https://github.com/UaiSO21/$pkgname"
license=('GPL3')
depends=('git')
provides=("$pkgname")
# conflicts=('')
source=("git+${url}.git")

package() {
    cd ${pkgname}
    install -d ${pkgdir}/usr/share/wallpapers/orion
    cp -r orion/* ${pkgdir}/usr/share/wallpapers/orion
}