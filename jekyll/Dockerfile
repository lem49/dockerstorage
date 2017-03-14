FROM ruby:2.4.0
MAINTAINER test <test@mail.net>

EXPOSE 4000
WORKDIR /srv/jekyll
ENV BUNDLE_PATH /box
ENTRYPOINT bundler install && jekyll serve -H 0.0.0.0 --watch --force_polling --drafts
