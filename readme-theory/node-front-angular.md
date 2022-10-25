# Descricion

# Instalacion
* tener ubuntu completamente actualizado.
```
    sudo apt update
    sudo apt upgrade
```
* instalar node
```
    curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
    apt install -y nodejs
    node -v
```
* Instalar npm # Manejador de packetes
```
    apt install npm
    npm -v
```
* Cliente de comandos Angular
```
    //instalacion global
    npm i -g @angular/cli
    
    // version de @angular/cli
    ng version
    
    //(dentro de la app generada): nos va listas las depencias que tenemos
    ng version
```

# crear proyecto example

* Auto crea un proyecto con dependencias 
```
    ng new app
```
* Levantar app (Dentro de la raiz del proyecto): app/
```
    //levantar un servidor de desarrollo
    ng serve
    
    //levantar un servidor de desarrollo, navegador por defecto
    ng serve -o
    
    //levantar un servidor de desarrollo, exponiendo al puerto 3500
    ng serve --port=3500
```

# 