
# RStudio from docker 
http://localhost:8787/

# Up!
docker compose up -d

# Ingresar a internet por consola
scurl localhost:8787

########################################################

remove.packages("Rscience")
# Libreria
library(remotes)

# Instalar la librería desde GitHub
remotes::install_github("deliaspanigo/Rscience", force = T)

###################################################################
