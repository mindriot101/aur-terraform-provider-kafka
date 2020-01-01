# Maintainer: Simon Walker <s.r.walker101@googlemail.com>
pkgname=terraform-provider-kafka-bin
pkgrel=1
pkgver=0.2.3
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
provides=("terraform-provider-kafka")
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("https://github.com/Mongey/terraform-provider-kafka/releases/download/v0.2.3/terraform-provider-kafka_0.2.3_linux_amd64.tar.gz")
noextract=()
md5sums=()
validpgpkeys=()
sha256sums=("e992f11490166e88b9aadbb9c4153ebc54ca115476564539731914c3f77250a0")

package() {
    install -Dm755 ./terraform-provider-kafka_v0.2.3 "${pkgdir}/usr/bin/terraform-provider-kafka"
    install -Dm644 ./LICENSE "${pkgdir}/usr/share/licenses/terraform-provider-kafka/LICENSE"
}
