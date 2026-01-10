FROM ubuntu:16.04@sha256:a4fc0c40360ff2224db3a483e5d80e9164fe3fdce2a8439d2686270643974632

ENV LC_ALL=C.UTF-8 LANG=C.UTF-8

RUN apt-get update -q && \
    apt-get install -qy \
        git \
        wget \
        make \
        autotools-dev \
        autoconf \
        libtool \
        xz-utils \
        libssl-dev \
        libssl1.0.0 \
        openssl \
        zlib1g-dev \
        libffi-dev \
        libncurses5-dev \
        libsqlite3-dev \
        libusb-1.0-0-dev \
        libudev-dev \
        gettext \
        libzbar0 \
        libdbus-1-3 \
        libxkbcommon-x11-0 \
        libc6-dev \
        automake \
        pkg-config \
        && \
    rm -rf /var/lib/apt/lists/* && \
    apt-get autoremove -y && \
    apt-get clean
