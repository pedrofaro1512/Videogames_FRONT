# Usar una imagen base adecuada para tu proyecto
FROM node:latest

# Establecer el directorio de trabajo
WORKDIR /app

# Copiar los archivos de la aplicación
COPY . /app

# Instalar dependencias y construir la aplicación
RUN npm install
RUN npm run build

# Comando de inicio (si es necesario)
CMD npm start