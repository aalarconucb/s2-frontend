# Frontend base v2

Frontend base desarrollado con el framework quasar y vuejs 3

## 1. Requerimientos

| Nombre       | Versión | Descripción                                            | Instalación                                      |
|--------------|---------|--------------------------------------------------------|--------------------------------------------------|
| `NodeJS`     | ^18     | Entorno de programación de JavaScript.                 | `nvm install 18` https://github.com/nvm-sh/nvm   |                       |
`quasar/cli`     | ^2.3    | Cliente de quasar.                 | `npm i -g @quasar/cli` https://quasar.dev/start/quasar-cli   |
## 2. Instalación
### Clonación del proyecto e instalación de dependencias

```bash
# Clonación del proyecto
git clone ruta_del_proyecto

# Ingresamos dentro de la carpeta del proyecto
cd frontend-base-v2
```

### Archivos de configuración.

Copiar archivos `.sample` y modificar los valores que sean necesarios (para más detalles revisa la sección **Variables
de entorno**).

```bash
# parámetros requeridos
cp config/dev.env.js.sample config/dev.env.js
cp config/prod.env.js.sample config/prod.env.js
```

### Despliegue de la aplicación

```bash
# Ejecución en modo desarrollo
quasar dev -m spa

# Ejecución en modo produccion
quasar build -m spa
```

### USUARIO ADMINISTRADOR

```bash
# Usuario Demo
admin

# Contraseña Demo
Developer
```