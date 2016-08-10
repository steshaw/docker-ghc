FROM debian:jessie

RUN cat /etc/apt/sources.list
RUN echo 'deb http://httpredir.debian.org/debian jessie-backports main' >>/etc/apt/sources.list
RUN apt-get update
RUN apt-get -t jessie-backports install -y ghc cabal-install git
RUN ghc --version
RUN cabal --version
RUN git --version
