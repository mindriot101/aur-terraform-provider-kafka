# Maintainer: Simon Walker <s.r.walker101@googlemail.com>
pkgname=terraform-provider-kafka
pkgrel=1
pkgver=0.2.2
epoch=
pkgdesc="Provision kafka topics and ACLs with terraform"
arch=("x86_64")
url="https://github.com/Mongey/terraform-provider-kafka"
license=("MIT")
groups=()
depends=()
makedepends=("go")
checkdepends=()
optdepends=()
provides=("${pkgname}")
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("https://github.com/Mongey/terraform-provider-kafka/releases/download/v0.2.2/terraform-provider-kafka_0.2.2_linux_amd64.tar.gz")
noextract=()
md5sums=()
validpgpkeys=()
sha256sums=("6c88e922fb807622a3fa4de7b67f63abf64bae99a719ce6ff7d21d6417ac4d41")

package() {
    install -Dm755 ./${pkgname} "${pkgdir}/usr/bin/${pkgname}"
    install -Dm644 ./LICENSE "${pkgdir}/usr/share/licenses/$pkgname/LICENSE"
}
