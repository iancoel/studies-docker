FROM node

WORKDIR /src

COPY package*.json .
# Poderia também ser COPY package*.json .

RUN npm install

COPY . .
# Copia todos os arquivos para dentro do container

EXPOSE 3000

CMD ["node", "app.js"]
# Usar o CMD ao invés de run pois ele aceita parâmetros em lista


# Cada linha deste arquivo é uma camada
# Entre cada linha é criado um cache
# Se, por exemplo, executamos a imagem e alteramos a porta na #13, a imagem completa não será re-executada, apenas a #13 em diante