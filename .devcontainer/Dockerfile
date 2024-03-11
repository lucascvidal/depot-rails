FROM mcr.microsoft.com/devcontainers/ruby:1-3.3-bullseye

RUN curl -fsSL https://deb.nodesource.com/setup_21.x | bash - && apt-get install -y nodejs

RUN curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
RUN echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
RUN apt-get update && sudo apt install yarn

RUN npx @puppeteer/browsers install chrome@122.0.6261.111
RUN npx @puppeteer/browsers install chromedriver@122.0.6261.111
