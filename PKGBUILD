# Maintainer: Jacek Bienias (LinGruby) <sp7ezd@ymail.com>

pkgname=cachyos-spectrwm-config
pkgdesc='CachyOS Spectrwm config'
pkgver=1.0.0
pkgrel=1
arch=('any')
url="https://github.com/cachyos/$pkgname"
license=('GPL')
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/archive/$pkgver.tar.gz")
sha512sums=('skip')
depends=('cachyos-zsh-config'
         'cachyos-picom-config'
         'feh'
         'pavucontrol'
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
         'cachyos-nord-gtk-theme-git')
install=$pkgname.install
provides=('cachyos-desktop-settings')
conflicts=('cachyos-desktop-settings')

package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
}
