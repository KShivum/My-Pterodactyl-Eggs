FROM 18-alpine3.15

RUN apk add --no-cache --update curl ca-certificates openssl git tar bash sqlite fontconfig \
    && adduser --disabled-password --home /home/container container

WORKDIR /home/container


CMD [ "/bin/bash", "node", "FoundryVTTFiles/resources/app/main.js", "--datapath=FoundryVTTData" ]