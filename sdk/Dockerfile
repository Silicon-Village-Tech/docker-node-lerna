FROM node:16.16-alpine
# FROM node:slim
USER root

RUN npm install -g --quiet lerna serverless esbuild firebase-tools jest sonar-scanner
chmod +x /usr/local/lib/node_modules/sonar-scanner/bin/sonar-scanner
RUN npm install -g yarn --force
