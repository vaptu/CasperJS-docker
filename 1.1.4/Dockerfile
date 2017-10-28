#Casperjs Docker Container
FROM node

#Install phantomjs
COPY phantomjs-2.1.1-linux-x86_64 /usr/local/phantomjs
COPY sources.list.jessie /etc/apt/sources.list

#Install Chinese font
RUN apt-get update && apt-get -y  install xfonts-wqy fonts-wqy-zenhei && npm config set registry http://registry.npm.taobao.org/ && npm install -g casperjs && apt-get clean
ENV PATH $PATH:/usr/local/phantomjs/bin 

CMD casperjs
