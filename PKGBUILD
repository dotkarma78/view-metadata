pkgname='view-metadata'
pkgdesc='View Metadata (VMD) is a CLI tool used for inspecting, parsing, and serializing metadata of files.'

pkgrel=1
pkgver=0.1

arch=('any')
depends=('python' 'python-magic')

source=('https://github.com/dotkarma78/view-metadata.git')
sha256sums=('cc02b2bdeb8ca788dfd45f910db9ee4ebb468985af89e5886e68148c8e2832a3')

package() {
    install -Dm755 "$srcdir/view-metadata/vmd" "$pkgdir/usr/bin/vmd"
}
