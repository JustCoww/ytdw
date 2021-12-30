# Maintainer: justcow <9pujswh2w@mozmail.com>
pkgname=ytdw
pkgver=1.0
pkgrel=1
pkgdesc="A simple python script to download mp3/mp4 files from the web using youtube-dl."
arch=('any')
url="https://raw.githubusercontent.com/JustCoww/ytdw/main/ytdw"
license=('MIT')
provides=(ytdw)
conflicts=(ytdw)
depends=(python youtube-dl)
makedepends=('git')
source=("git+$url+build")
md5sums=('SKIP')

package() {
	mkdir build
	cd build
	chmod +x ytdw
	sudo cp ytdw /usr/bin/
}
