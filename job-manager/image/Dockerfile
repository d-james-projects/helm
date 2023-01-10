FROM debian:11.6-slim

RUN apt-get update && \
    apt-get upgrade -y

COPY wait-for-it/wait-for-it.sh .
RUN install wait-for-it.sh /usr/local/sbin
RUN rm wait-for-it.sh
CMD ["wait-for-it.sh"]