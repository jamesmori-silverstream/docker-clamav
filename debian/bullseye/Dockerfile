FROM debian:bullseye

RUN apt-get update && \
    apt-get install -y clamav clamav-freshclam && \
    freshclam

CMD ["clamd"]
