# Maintainer: Jesse Jaara	<gmail.com: jesse.jaara; mail.ru: jesse.jaara>

pkgname=ttf-myanmar3
pkgver=20110120
pkgrel=1
pkgdesc="Font for Myanmar/Burmese script."
arch=('any')
url="http://www.myanmarnlp.net.mm/"
license=('free')
depends=('fontconfig' 'xorg-font-utils')
source=(http://myanmar3source.googlecode.com/files/mm3_20-Jan-2011.ttf)
install=$pkgname.install

package()
{
  mkdir -p "${pkgdir}/usr/share/fonts/TTF"
  cp "${srcdir}/mm3_20-Jan-2011.ttf" "${pkgdir}/usr/share/fonts/TTF/mm3.ttf"
}
md5sums=('5187cd65099bfa0f281036f420bddc06')
