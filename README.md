# Desafio - Usando el objeto process

Las claves y credenciales se han movido a un archivo .env, usandolo mediante dotenv

en el archivo index.js del servidor, se encuentra la configuracion de minimist para que se indique por argumentos, el puerto de escucha del servidor, en caso de no mencionarse un puerto, el puerto de default sera de 8080

Se agreo una ruta test/info donde se menciona la informacion que solicita el desafio.
Se implemento dentro de /test , otra ruta /test/randoms, el cual genera numeros aleatorios del 1 al 1000, especificando la cantidad de numeros en una query de consulta, si no se menciona un numero de consulta, generara 1millon de numero aleatorios. 
