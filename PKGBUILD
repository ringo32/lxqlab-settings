# Maintainer: joekamprad <joekamprad at endeavouros.com>

pkgname=lxlab-settings
pkgver=0.2
pkgrel=1
pkgdesc="LXQT lab settings for EndeavourOS/iso"
arch=('any')
license=('GPL')
depends=('lxqt-session')
source=('panel.conf'
        'session.conf'
        'settings.conf')
sha256sums=('SKIP'
            'SKIP'
            'SKIP')

package() {
    install -Dm755  "${srcdir}/panel.conf" "${pkgdir}/etc/skel/.config/lxqt/panel.conf"
    install -Dm755  "${srcdir}/session.conf" "${pkgdir}/etc/skel/.config/lxqt/panel.conf"
    install -Dm755  "${srcdir}/settings.conf" "${pkgdir}/etc/skel/.config/pcmanfm-qt/lxqt/settings.conf"
}
