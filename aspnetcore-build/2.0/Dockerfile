FROM microsoft/aspnetcore-build:2.0.9-sdk-2.1.202

# remove node instance present in base image
RUN rm /usr/local/bin/node

RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -

RUN apt-get install -y build-essential
RUN apt-get install -y nodejs=8.11.4-1nodesource1