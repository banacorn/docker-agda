FROM        fpco/stack-build:lts-13.21
MAINTAINER  Ting-Gian LUA <banacorn@gmail.com>

RUN stack --resolver=lts-13.21 install Agda-2.6.0.1 EdisonCore-1.3.2.1 data-hash-0.2.0.1 equivalence-0.3.4 geniplate-mirror-0.7.6 EdisonAPI-1.3.1 STMonadTrans-0.4.3

CMD agda --interaction
