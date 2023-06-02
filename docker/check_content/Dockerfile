FROM alpine
COPY ./file.sh /
RUN chmod +x /file.sh \
    && apk add --no-cache bash
ENTRYPOINT ["/file.sh"]
CMD ["/etc/hosts"]dock