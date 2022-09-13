FROM alpine

COPY http-echo /bin/http-echo
EXPOSE 5678
ENTRYPOINT [ "/bin/http-echo", "-text=foo" ]