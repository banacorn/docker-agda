FROM        haskell:7.10.1
MAINTAINER  Ting-Gian LUA <banacorn@gmail.com>

RUN cabal update
RUN cabal install Agda-2.4.2.4

CMD agda --interaction
