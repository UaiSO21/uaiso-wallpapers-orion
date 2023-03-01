# Maintainer: mauriciodelima.mol@gmail.com

pkgname=uaiso-wallpapers-orion
pkgver=$(date +%y.%m.%d)
pkgrel=$(date +%H%M)
pkgdesc="Package Wallpaper for UaiSO Evolve Orion"
arch=('any')
url="https://github.com/UaiSO21/$pkgname"
license=('GPL3')
depends=('git')
provides=("$pkgname")
# conflicts=('')
source=("git+${url}.git")
md5sums=('SKIP')

package() {
    cd ${pkgname}
    install -d ${pkgdir}/usr/share/wallpapers/orion
    cp -r orion/* ${pkgdir}/usr/share/wallpapers/orion
}