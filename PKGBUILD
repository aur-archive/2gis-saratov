# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>

pkgname=2gis-saratov
pkgver=1
pkgrel=1
pkgdesc="Map of Saratov for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Saratov-${pkgver}.orig.zip")
md5sums=('3a1eaa2264517d6d370563ecd00f2975')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Saratov.dgdat "${startdir}/pkg/opt/2gis/saratov.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Saratov.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Saratov.dglf" || return 1

}