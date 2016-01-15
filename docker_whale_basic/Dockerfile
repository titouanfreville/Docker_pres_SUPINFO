FROM docker/whalesay

RUN apt-get -y update && apt-get install -y fortunes figlet

CMD figlet "Hy SUPINFO" | cowsay -n && /usr/games/fortune -a | cowsay
