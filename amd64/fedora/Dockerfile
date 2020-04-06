FROM fedora:33

RUN dnf -y install gcc ccache make meson uncrustify desktop-file-utils \
    gtk3-devel gtk4-devel docbook-style-xsl libappstream-glib libxslt \
    gcovr && rm -rf /var/cache
