FROM umiqlo/jdk-armhf

WORKDIR /opt/paper-mc

ENV BUILD_VERSION="1.12.2"
ENV MIN_RAM="384"
ENV MAX_RAM="512"

ADD init .

RUN chmod +x init

CMD ["./init"]