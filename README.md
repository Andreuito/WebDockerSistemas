# WebDockerSistemas

## Primero procedemos a instalar nginx dentro de docker con este comando 'sudo docker pull nginx'
![image](https://user-images.githubusercontent.com/91564971/168854556-17e855a8-32fd-4abb-b8c5-3222572e36c6.png)

## Luego con un comando procedemos a abrir y alojar una web nginx 'sudo docker run --rm -d -p 8080:80 --name web nginx'
![image](https://user-images.githubusercontent.com/91564971/168855226-293eeab7-6fe8-4637-8312-e548dd11317b.png)

## Comprobamos que todo ha funcionado correctamente y nos vamos al navegador y ponemos 'localhost:8080' y nos deberia salir nginx
![image](https://user-images.githubusercontent.com/91564971/168855762-72b0c73d-9e2e-4616-a998-0afba5004064.png)

## Luego pasamos a la parte de instalar nuestro propio html con nuestro nombre y con este comando lo que hacemos es cambiar la ruta de busqueda del nginx ya que hemos creado nosotros una ruta propia.
![image](https://user-images.githubusercontent.com/91564971/168856453-4b2d970a-127d-438e-9c13-3e75710e7bec.png)

## Por ultimo si nos dirigimos a nuestro navegador y ponemos el puerto en el que esta alojado deberia salir mi html pero por razones que desconozco y que no he podido solucionar me sale este resultado.
![image](https://user-images.githubusercontent.com/91564971/168856809-bc58ad93-9021-40eb-b2ef-ce031100e05e.png)
