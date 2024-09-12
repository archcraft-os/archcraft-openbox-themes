# Maintainer: Aditya Shakya <adi1090x@gmail.com>

pkgname=archcraft-openbox-themes
pkgver=1.0
pkgrel=0
pkgdesc="Openbox themes for Archcraft"
arch=('any')
url="https://github.com/archcraft-os/archcraft-openbox-themes"
license=('GPL3')
options=(!strip !emptydirs)

prepare() {
	cp -af ../OB-* "$srcdir"
}

package() {
	local _themesdir="$pkgdir"/usr/share/themes
	mkdir -p "$_themesdir"
	cp -r "$srcdir"/* "$_themesdir"
}
