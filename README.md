SASS
Primero probar en una carpeta nueva.
Crear la carpera css con el archivo style.css
Despues crear la carpeta scss con el archivo style.scss
Abrimos una terminal (powershell).
Ejecutamos el comando npm init (por unica vez) y apretamos 10 veces enter para confirmar todo.
Luego necesitamos ejecutar el comando: npm install -g sass.
Al terminar la instalacion necesitamos ejecutar el comando:
    sass --watch scss:css
De esta manera, ahora pasamos a trabajar en nuestro codigo scss y al guardar, compila y se pega automaticamente el codigo en el archivo css.
Cuando apagamos al pc y volvemos a prenderla para trabajar solo hay que abrir la terminal (powershell) y ejecutar el comando: sass --watch scss:css.
Para cortar el proceso ejecutamos el comando:
    cntrl + c