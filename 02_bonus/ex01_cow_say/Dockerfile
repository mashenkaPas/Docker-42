FROM ubuntu

RUN apt-get update && apt-get install cowsay -y

ENV PATH="$PATH:/usr/games"

ENTRYPOINT ["cowsay"]
#docker build -t ex01_cow_say .
#docker run ex01_cow_say  lol
#docker run test <some text>
