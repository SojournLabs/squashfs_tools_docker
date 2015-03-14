# Root certificate authority container.
FROM debian
MAINTAINER jonathan lung <vapr@sojournlabs.com>
RUN apt-get update
RUN apt-get install -y \
    squashfs-tools \
    cpio
RUN mkdir -p vapr
WORKDIR /vapr