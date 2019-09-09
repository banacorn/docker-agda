FROM        haskell:8.0.1
MAINTAINER  Ting-Gian LUA <banacorn@gmail.com>

RUN cabal update
RUN cabal install Agda-2.5.1.2

CMD agda --interaction
