FROM        haskell:8.0.2
MAINTAINER  Ting-Gian LUA <banacorn@gmail.com>

RUN cabal update
RUN cabal install alex happy cpphs-1.20.2
RUN cabal install Agda-2.5.2

CMD agda --interaction
