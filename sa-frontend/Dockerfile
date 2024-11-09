FROM node
COPY . /
WORKDIR /sa-frontend
RUN npm install
EXPOSE 3000
ENV REACT_APP_WEBAPP_URL http://sa-web-app.svc.cluster.local
CMD ["npm", "start"]