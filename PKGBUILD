pkgname=iec-symbol-fonts
pkgver=1.0
pkgrel=1
pkgdesc="IEC Power Symbol Fonts"
arch=(any)
depends=(fontconfig xorg-font-utils)
revision="805536fb6f93604da985d80e0c6b099f98f8b4d9"
source=("${pkgname}.zip::https://github.com/jloughry/Unicode/archive/$revision.zip")
install=$pkgname.install
family_name="IECSymbolsUnicode"
md5sums=('ee6b637a39f0509f15c84ab8ca8b0337')

package() {
	install -Dm644 "Unicode-$revision/Unicode_IEC_symbol_font.otf" "$pkgdir/usr/share/fonts/OTF/$family_name.otf"
}
