FROM node:18.18.2
WORKDIR /angular-app
RUN npm install @angular-devkit/build-angular && \
    npm install -g @angular/cli
EXPOSE 4200
CMD ["ng", "serve", "--host", "0.0.0.0"]
