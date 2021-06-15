# Iniciar proyecto de git
git init

# Preparar archivos que se convertirán en commit
git add .
## El putno es para agregar todos los archivos modificados

# Crear el commit con su mensaje
git commit -m "Aqui va el mensaje"

# Agregar remoto "Sólo la primera vez"
 git remote add origin https://github.com/CristopherCano/santander-front-end.git

# Enviar commmits agregados
git push -u orign master