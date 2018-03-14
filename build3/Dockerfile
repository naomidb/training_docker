FROM ubuntu

RUN apt-get update && apt-get install -y \
  curl \
  pv

RUN echo "Hello, World"
CMD curl -s http://artscene.textfiles.com/vt100/movglobe.vt | pv -q -L 9600
