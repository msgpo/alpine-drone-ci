FROM arm32v7/alpine:3.9

COPY overlay/ /

RUN ["setup.sh", "v3.9" ]

USER buildozer

ENTRYPOINT [ "/bin/sh" ]

