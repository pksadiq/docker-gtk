FROM fedora:34

RUN dnf -y install gcc ccache make meson uncrustify desktop-file-utils \
    gtk3-devel gtk4-devel docbook-style-xsl libappstream-glib libxslt \
    vulkan-headers gtk-doc gcovr xorg-x11-server-Xvfb && rm -rf /var/cache
