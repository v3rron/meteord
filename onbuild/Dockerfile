FROM verron/meteord:base
MAINTAINER Ronen Verdi <r0nv3r@gmail.com>

ONBUILD COPY ./ /app
ONBUILD RUN bash $METEORD_DIR/on_build.sh
