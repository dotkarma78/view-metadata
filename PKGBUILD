pkgname='view-metadata'
pkgdesc='View Metadata (VMD) is a CLI tool used for inspecting, parsing, and serializing metadata of files.'

pkgrel=1
pkgver=0.1

arch=('any')
depends=('python' 'python-magic')

source=('https://github.com/dotkarma78/view-metadata.git')
sha256sums=('902d4c982e08fb4cea2872e6716b1cdad1b00caa09d2f0e37f4103d8754820ad')

package() {
    install -Dm755 "$srcdir/view-metadata/vmd" "$pkgdir/usr/bin/vmd"
}
