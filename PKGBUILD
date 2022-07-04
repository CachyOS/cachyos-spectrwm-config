# Maintainer: Jacek Bienias (LinGruby) <sp7ezd@ymail.com>

pkgname=cachyos-spectrwm-config
pkgdesc='CachyOS Spectrwm config'
pkgver=1.0.1
pkgrel=1
arch=('any')
url="https://github.com/cachyos/$pkgname"
license=('GPL')
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/archive/$pkgver.tar.gz")
sha512sums=('skip')
depends=('zsh'
         'picom'
         'qt5ct'
         'krusader-git'
         'lxqt-sudo'
         'feh'
         'pavucontrol'
         'octopi'
         'xlockmore'
         'polkit-gnome'
         'dunst'
         'rofi'
         'polybar'
         'scrot'
         'breeze'
         'papirus-icon-theme'
         'nerd-fonts-fantasque-sans-mono'
         'noto-fonts-emoji'
         'ttf-hack'
         'ttf-fira-sans'
         'pcmanfm-qt')
install=$pkgname.install
provides=('cachyos-desktop-settings')
conflicts=('cachyos-desktop-settings')

package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
}
