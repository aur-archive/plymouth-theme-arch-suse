# Maintainer:  Wessel Dirksen "p-we" <wdirksen at gmail dot com>
# Contributor: Guillermo Garcia <ahioros@NO-SPAM.gmail.com>

pkgname=plymouth-theme-arch-suse
pkgver=2
pkgrel=1
pkgdesc="ArchLinux rebranded version of OpenSUSE 12.2 plymouth theme"
url="http://www.opensuse.org/en/"
arch=('any')
license=('GPL')
depends=('plymouth')
install='plymouth-arch-suse.install'

source=('plymouth-arch-suse.tar.gz' \
        'plymouth-arch-suse.install')

md5sums=('f62de0aa42fb910b88610abf35b436b9'
	 '9ed56f4633ad5f51726d53efcd0f13d0')

package() {

  cd $srcdir
  find . -type f -exec install -D -m644 {} ${pkgdir}/usr/share/plymouth/themes/openSUSE/{} \;
}
