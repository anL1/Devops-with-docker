FROM ubuntu:16.04

WORKDIR mydir/
COPY curler.sh .
RUN chmod 755 curler.sh
RUN apt-get update && apt-get install -y curl
CMD ["./curler.sh"]
