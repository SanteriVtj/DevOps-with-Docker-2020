FROM node

WORKDIR /usr/src/app
COPY frontend-example-docker/ . 
RUN npm install --silent && \
npm install -g serve --silent
EXPOSE 5000
CMD ["npm", "start"]