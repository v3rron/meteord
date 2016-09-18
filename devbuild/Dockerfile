FROM verron/meteord:base
MAINTAINER Ronen Verdi <r0nv3r@gmail.com>

ONBUILD RUN bash $METEORD_DIR/lib/install_meteor.sh
ONBUILD COPY ./ /app
ONBUILD RUN bash $METEORD_DIR/lib/build_app.sh
