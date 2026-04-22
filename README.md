# Launcher

## Inicialización de Submodulos

Para comenzar a trabajar con el proyecto, primero debes inicializar los submodulos:

```bash
git submodule update --init --recursive
```

## Configuración de Variables de Entorno

Cada microservicio requiere su propio archivo de variables de entorno (.env). Debes configurar los archivos `.env` en cada proyecto antes de ejecutar los contenedores.

## Actualización de Submodulos

Para actualizar los submodulos a la última versión disponible:

```bash
git pull
git submodule update --init --recursive
git submodule update --remote .
```

## Construcción de Contenedores

Para construir y levantar los contenedores:

```bash
docker-compose up --build
```
