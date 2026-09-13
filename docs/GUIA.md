# Guía de trabajo colaborativo con Git y GitHub

Esta guía explica cómo realizar una tarea básica de trabajo colaborativo utilizando Git y GitHub.

## Requisitos

Antes de comenzar necesitas tener instalado:

- Git
- Visual Studio Code
- Una cuenta de GitHub

### Verificar Git

Abre la terminal de Visual Studio Code y ejecuta:

```bash
git --version
```

Si aparece la versión de Git, la instalación está correcta.

## Crear y trabajar con el repositorio

### Clonar el proyecto

1. Ingresa al repositorio de GitHub.
2. Presiona el botón **Code**.
3. Copia la dirección del repositorio.
4. Abre la terminal en Visual Studio Code.
5. Ejecuta el comando:

```bash
git clone URL_DEL_REPOSITORIO
```

Después ingresa a la carpeta:

```bash
cd mi-portafolio
```

### Realizar cambios

1. Abre el proyecto en Visual Studio Code.
2. Modifica o crea los archivos necesarios.
3. Guarda los cambios.
4. Revisa los archivos modificados con:

```bash
git status
```

## Checklist de trabajo

- [x] Crear el repositorio en GitHub
- [x] Crear y modificar el archivo README.md
- [ ] Realizar una nueva modificación al proyecto

## Comandos principales

| Comando | Función | Ejemplo |
|---|---|---|
| `git add .` | Agrega los cambios | `git add .` |
| `git commit` | Guarda los cambios en Git | `git commit -m "Actualiza README"` |
| `git push` | Sube los cambios a GitHub | `git push origin main` |

## Publicar los cambios

Para publicar los cambios realizados en GitHub, primero agrega los archivos:

```bash
git add .
```

Después crea un commit:

```bash
git commit -m "Actualiza la guia del proyecto"
```

Finalmente sube los cambios:

```bash
git push origin main
```

## Recursos

Puedes consultar la [Guía oficial de Markdown](https://www.markdownguide.org/) para conocer más sobre la sintaxis utilizada.

## Imagen del proyecto

![Captura del proyecto](../img/captura.png)