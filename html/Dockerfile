#From  
#FROM para llamar a las imagenes de docker hub

#WORKDIR /app 
#Para crear uan carpeta de trabajo dentro de docker

#COPY . /app
#Para copiar los archivos de la carpeta actual a la carpeta de trabajo dentro de docker

#RUN 
#para crear dependencias dentro de docker

#ENTRYPOINT ["python", "scrtipt.py"]
#ParA EJECUTAR EL SCRIPT DENTRO DE DOCKER

#CMD python scriot.py
#Para ejecutar el script dentro de docker, se puede usar ENTRYPOINT o CMD,pero no ambos, si se usan ambos,CMD se ejecutara despues de ENTRYPOINT, si se usan ambos, CMD se ejecutara como argumento de ENTRYPOINT


# Usar la imagen oficial de Nginx
FROM nginx:alpine

# Copiar todos los archivos de la carpeta html al directorio de Nginx
COPY ./html /usr/share/nginx/html

#para no hacerlo archvo por archivo