# HINT: Remember that you can find `ubuntu` images in the Docker Hub!
FROM ubuntu:resolute-20260108

COPY /app.sh /
RUN chmod +x /app.sh

ENTRYPOINT [ "/app.sh" ]
