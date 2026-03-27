pkgname='view-metadata'
pkgdesc='View Metadata (VMD) is a CLI tool used for inspecting, parsing, and serializing metadata of files.'

pkgrel=1
pkgver=0.1

arch=('any')
depends=('python' 'python-magic')

source=('https://github.com/dotkarma78/view-metadata.git')
sha256sums=('0f32634acadd5a729e8f4dff7d7f3fbea01eb8a10f49d6af2202ae449e822ffb')

package() {
    install -Dm755 "$srcdir/view-metadata/vmd" "$pkgdir/usr/bin/vmd"
}
