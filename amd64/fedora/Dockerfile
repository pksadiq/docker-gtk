FROM fedora:29

RUN dnf -y install gcc ccache make meson uncrustify desktop-file-utils \
    gtk3-devel gtk4-devel docbook-style-xsl msitools mingw32-gtk3 \
    libappstream-glib libxslt lcov && rm -rf /var/cache
