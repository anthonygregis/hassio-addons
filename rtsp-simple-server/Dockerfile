FROM aler9/rtsp-simple-server AS rtsp

COPY --from=rtsp /rtsp-simple-server /
COPY rtsp-simple-server.yml /

ENTRYPOINT [ "sh", "-c", "/rtsp-simple-server" ]