FROM debian:latest
LABEL maintainer="Ashpak Mulani"
RUN apt update && \
    apt install -y traceroute && \
    apt install -y curl && \
    apt clean
ENTRYPOINT ["curl"]
CMD ["www.google.com"]