FROM        haskell:7.10.3
MAINTAINER  Ting-Yan Lai <banacorn@gmail.com>

RUN cabal update
RUN cabal install Agda-2.5.1

CMD agda --interaction
