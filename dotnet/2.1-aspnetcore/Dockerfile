FROM microsoft/dotnet:2.1.2-aspnetcore-runtime

RUN apt-get update
RUN apt-get install -y wget gnupg2

RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -

RUN apt-get install -y build-essential
RUN apt-get install -y nodejs=8.11.4-1nodesource1