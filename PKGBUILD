# Contributor: Luis Pablo Gasparotto <lpgasparotto(at)gmail(dot)com>

pkgname=lib32-distrho-tal
pkgver=20120518
pkgrel=1
pkgdesc="This is a plugin pack Togu Audio Line. Includes TAL Dub 3, Filter 1 & 2, NoiseMaker, Reverb 1, 2 & 3 and Vocoder 2. Ported to LV2. A Special thanks goes to Patrick Kunz for making these awesome plugins!"
url="http://distrho.sourceforge.net/"
arch=('i686')
license=('GPL')
depends=('lv2' 'p7zip')
source=(http://sourceforge.net/projects/distrho/files/Ports/TAL-Plugins/tal-plugins_linux32_20120518.7z)
md5sums=('5805d79946253f223ffd03a8cbcba8ba')
build() {
  cd $startdir/src/tal-plugins_linux32
  install -m 755 -d $startdir/pkg/usr/lib/lv2/{TAL-Dub-III.lv2,TAL-Filter-II.lv2,TAL-Filter.lv2,TAL-NoiseMaker.lv2,TAL-Reverb-II.lv2,TAL-Reverb-III.lv2,TAL-Reverb.lv2,TAL-Vocoder-II.lv2}
  install -m 644 -D lv2/TAL-Dub-III.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Dub-III.lv2/
  install -m 644 -D lv2/TAL-Filter-II.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Filter-II.lv2/
  install -m 644 -D lv2/TAL-Filter.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Filter.lv2/
  install -m 644 -D lv2/TAL-NoiseMaker.lv2/* $startdir/pkg/usr/lib/lv2/TAL-NoiseMaker.lv2/
  install -m 644 -D lv2/TAL-Reverb-II.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Reverb-II.lv2/
  install -m 644 -D lv2/TAL-Reverb-III.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Reverb-III.lv2/
  install -m 644 -D lv2/TAL-Reverb.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Reverb.lv2/
  install -m 644 -D lv2/TAL-Vocoder-II.lv2/* $startdir/pkg/usr/lib/lv2/TAL-Vocoder-II.lv2/
}
