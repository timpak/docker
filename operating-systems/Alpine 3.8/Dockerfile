FROM alpine:3.8

COPY bundles /home/bundles

COPY entrypoint.sh /entrypoint.sh

RUN chmod +x entrypoint.sh && \
	apk update && \
	apk add openjdk8

CMD [ "./entrypoint.sh" ]

EXPOSE 8080