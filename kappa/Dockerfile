FROM dockerfile/nodejs
ADD . /src
RUN npm install -g kappa
WORKDIR /src
CMD kappa -c config.json
