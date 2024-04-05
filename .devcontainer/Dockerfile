FROM ruby:3.3.0-bullseye

RUN apt update && apt install -y build-essential git libsqlite3-dev redis ruby-dev tzdata libnss3-dev libgdk-pixbuf2.0-dev libgtk-3-dev libxss-dev libasound2
RUN gem install rails -v 7.1.3.2 --no-document
