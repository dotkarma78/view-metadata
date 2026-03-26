pkgname=view-metadata
pkgver=0.0.0.1
pkgrel=1
pkgdesc="This tool allows you to see metadata for any file, partition, and drive, as well as the specific block device, character device, FIFO, junction, mount point, socket, and symbolic link."
arch=('any')
source=('https://github.com/dotkarma78/view-metadata.git')
url='https://github.com/dotkarma78/view-metadata.git'
depends=('python' 'python-magic')
sha256sums=('73c5df16bc527bd76fedfeced68b6fe0926229bf4bb28575fed57900b6eecee1')

package() {
    install -Dm755 "$srcdir/view-metadata/vmd.py" "$pkgdir/usr/bin/vmd"
}

