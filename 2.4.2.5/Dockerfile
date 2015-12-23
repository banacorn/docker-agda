# ought to be based on haskell:7.10.3, but there's no such images yet
FROM        haskell:7.10.2
MAINTAINER  Ting-Yan Lai <banacorn@gmail.com>

RUN cabal update
RUN cabal install Agda-2.4.2.5

CMD agda --interaction
