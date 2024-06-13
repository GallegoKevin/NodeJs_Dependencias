# NODEJS - NVM

![Imagen](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSd9-KQ7NFQJ5y62EJw8SMe-Ymn07hpdsSCvw&s)


## Instalacion de nvm - Windows

1. Descargar nvm en el siguiente enlace:   
- https://github.com/coreybutler/nvm-windows/releases/download/1.1.12/nvm-setup.exe
2. Instalar
3. Abrir el terminal PowerShell o el terminal cmd  como administrador
4. Verificar la version con:  `nvm --version`
5. Verificar la lista de nodejs con `nvm list`
5. Instalar nodejs 20.14.10 , 14, 16, 18 con :
    - nvm install 20.14.10
    - nvm install 14
    - nvm install 16
    - nvm install 18
6. Establecer el nodejs a usar con `nvm use 20.14.0 `

**`Para establecer como predeterminado usar:` `nvm alias default 20.14.0`**


## Importancia de **NVM (Node Version Manager):** 

Permite:

- Gestionar múltiples versiones de Node.js.
- Garantizar compatibilidad entre proyectos.
- Facilitar actualizaciones sin afectar proyectos existentes.

## ¿Por qué utilizar **NPM (Node Package Manager)**?

Porque:

- Maneja dependencias del proyecto.
- Accede a un vasto ecosistema de paquetes.
- Automatiza tareas comunes con scripts.
- Gestiona versiones de dependencias para estabilidad.

## ¿Por qué no usar solo Node.js (solo 1 version)?

- **Gestión de versione / flexibilidad**: Node.js por sí solo no facilita el uso de múltiples versiones simultáneamente, lo que puede ser un problema al trabajar en varios proyectos con diferentes requisitos.
- **Compatibilidad de proyectos**: Cambiar de versión de Node.js implica reinstalaciones manuales que pueden causar problemas de compatibilidad en proyectos existentes.


## Proyecto con Nodejs:


1. Inicializar proyecto
```
npm init
```
2. Instalación de dependencias:

- **Instalación de desarrollo:**

Solo va existir en el ambito de desarrollo

```
npm install -D axios
```

- **Instalación de producción**

Va irse a produccion

```
npm install react-dom
```

- **Instalación Global:**

Instalaciones en todo el sistema operativo (va de la mano de la version de NODEJS)

```
npm install --global nodemon
npm install -g http-server
```

**Comando para eliminar la 'carpeta node_modules':**

```
rm -rf node_modules
```

**Crear archivo .gitignore:**

```
touch .gitignore
```

**Editar archivo .gitignore y guardar:**

Añadir la siguiente línea al archivo:

```
node_modules/
```