FROM ubuntu:18.04

WORKDIR /usr/src/app

COPY curl-script.sh .

# Let's just run chmod here so that we don't have to remember it
RUN chmod +x curl-script.sh

# Install dependencies
RUN apt update && apt install -y curl

CMD ./curl-script.sh

