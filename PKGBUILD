# Maintainer: Stefan Zipproth <s.zipproth@ditana.org>

pkgname=ditana-print-system-load
pkgver=1.09
pkgrel=1
pkgdesc="Ditana system load printer used in XFCE panel"
arch=(any)
url="https://ditana.org"
license=('AGPL-3.0-or-later AND BSD-2-Clause AND BSD-3-Clause AND BSD-4-Clause-UC AND GPL-2.0-only AND GPL-2.0-or-later AND GPL-3.0-or-later AND ISC  LGPL-2.1-or-later AND LicenseRef-PublicDomain')
conflicts=()
depends=(util-linux)
makedepends=()
source=("file://${PWD}/print-system-load.sh")
sha256sums=('SKIP')

package() {
	install -D -m755 $srcdir/print-system-load.sh $pkgdir/usr/share/ditana/print-system-load.sh
}
