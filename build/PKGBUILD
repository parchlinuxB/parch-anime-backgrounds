# Maintainer: Parch Linux Distribution Team <feedback@parchlinux.ir>

pkgname=parch-anime-backgrounds
pkgver=1.0
pkgrel=1
pkgdesc='Parch Linux anime Wallpapers'
arch=('any')
url="https://github.com/parchlinuxb/anime-backgrounds"
license=('GPL')
source=("build.zip")
sha256sums=('SKIP')

package() {
    install -d "${pkgdir}/usr/share/wallpapers/parch-anime/"
    install -Dm 644 *.jpg "${pkgdir}/usr/share/wallpapers/parch-anime/"
    install -Dm 644 parch-anime.xml "${pkgdir}/usr/share/gnome-background-properties/parch-anime.xml"
}
