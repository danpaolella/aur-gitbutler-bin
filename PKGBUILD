# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
# Contributor: Daniele Paolella <danpaolella@gmail.com>
pkgname=gitbutler-bin
pkgver=0.14.31
pkgrel=1
_pkgvernum=2048
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk-4.1' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/GitButler_${pkgver}_amd64.deb")
sha256sums=('e2929377cbf70e77161016cfba1b6ef9f3bda72b5df7ac1178ac3a4d94cc9a30')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}
