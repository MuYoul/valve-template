# Dockerfile

FROM node:10-alpine
RUN apk add --no-cache bash curl
EXPOSE 3000
WORKDIR /data
ADD . /data
CMD ["npm", "run", "start"]
