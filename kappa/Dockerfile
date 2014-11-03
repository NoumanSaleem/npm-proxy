FROM dockerfile/nodejs
ADD . /src
RUN npm install -g kappa
CMD kappa -c /src/config.json
