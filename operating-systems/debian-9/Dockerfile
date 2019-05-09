FROM openjdk:8-stretch

COPY bundles /home/bundles

COPY entrypoint.sh /entrypoint.sh

RUN chmod +x entrypoint.sh

CMD [ "./entrypoint.sh" ]

EXPOSE 8080