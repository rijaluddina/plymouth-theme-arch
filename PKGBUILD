pkgname=plymouth-theme-arch
pkgver=1.0
pkgrel=1
pkgdesc="Minimal Arch Linux Plymouth theme"
arch=('any')
url="https://github.com/rijaluddina/plymouth-theme-arch"
depends=('plymouth')

source=(
  "arch.plymouth"
  "arch.script"
  "arch.png"
)

sha256sums=('875a33cd96e729d80828bfb4afd055b21ff3ae9a03fed48fce895223945e32ca'
  '514e05a22ac814b7f1dc0b32638b6b7f0a397ef1368d8f3d0a1f275556e2c3c8'
  '2bbc3255007f4333430d8fdcc52919c0802698bea92401c53c89f5b71fa10c35')

package() {
  install -d "$pkgdir/usr/share/plymouth/themes/arch"

  install -m644 arch.plymouth \
    "$pkgdir/usr/share/plymouth/themes/arch/"

  install -m644 arch.script \
    "$pkgdir/usr/share/plymouth/themes/arch/"

  install -m644 arch.png \
    "$pkgdir/usr/share/plymouth/themes/arch/"
}
