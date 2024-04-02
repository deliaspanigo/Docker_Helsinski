# Utiliza una imagen base de Ubuntu
FROM rocker/rstudio:4.3.1

# Exponer el puerto 8787 para acceder a RStudio Server
EXPOSE 8787

# Configurar el usuario y la contraseña para RStudio Server
ENV DISABLE_AUTH true

# Ejecutar RStudio Server
CMD ["/init"]

