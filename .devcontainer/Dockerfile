FROM mcr.microsoft.com/devcontainers/ruby:1-3.3-bullseye

RUN curl -fsSL https://deb.nodesource.com/setup_21.x | bash - && apt-get install -y nodejs

RUN npx @puppeteer/browsers install chrome@122.0.6261.111
RUN npx @puppeteer/browsers install chromedriver@122.0.6261.111
