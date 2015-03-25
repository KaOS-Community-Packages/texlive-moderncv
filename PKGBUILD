pkgname=texlive-moderncv
pkgver=1.5.1
pkgrel=1
pkgdesc="A modern curriculum vitae class."
arch=('x86_64')
url="http://www.launchpad.net/moderncv/"
license=('GPL')
depends=('texlive-core' 'texlive-latexextra' 'texlive-fontsextra')
source=(http://mirror.ctan.org/macros/latex/contrib/moderncv.zip)
md5sums=('cb7c15c6a88f7a056aca44bfc5d8329e')
install=texlive-moderncv.install

package() {
  cd "${srcdir}"
  install -dm755 "${pkgdir}/usr/share/texmf/tex/latex"
  cp -r moderncv "${pkgdir}/usr/share/texmf/tex/latex"
}
