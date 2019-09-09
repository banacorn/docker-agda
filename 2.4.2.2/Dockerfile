FROM        haskell:7.8.4
MAINTAINER  Ting-Gian LUA <banacorn@gmail.com>

RUN cabal update
RUN cabal install cpphs-1.18.6
RUN cabal install Agda-2.4.2.2

CMD agda --interaction
