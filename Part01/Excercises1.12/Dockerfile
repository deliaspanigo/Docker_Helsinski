# Utiliza una imagen base de Ubuntu
FROM ubuntu:latest


COPY . /app

EXPOSE 5000

# Actualiza el sistema y luego instala Node.js y npm
RUN apt-get update 

WORKDIR /app
RUN apt-get install xsel -y

RUN apt-get install curl -y

RUN curl -sL https://deb.nodesource.com/setup_16.x | bash -

RUN apt install -y nodejs

RUN npm install
# RUN npm audit fix --force
RUN npm run build


RUN npm install -g serve
CMD ["serve", "-s", "-l", "5000", "build"]



