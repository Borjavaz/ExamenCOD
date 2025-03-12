# Release v1.0 - ExamenCOD

## Descripción

Este repositorio contiene el proyecto **ExamenCOD**. La versión **v1.0** es la primera release estable del proyecto. A continuación, se describen los pasos tomados para llegar a esta release, así como las decisiones y justificaciones realizadas durante el proceso.

## Pasos para la release

### 1. Fork del proyecto
El primer paso fue hacer un **fork** del repositorio original para trabajar en una copia independiente. Esto permite realizar cambios sin afectar al repositorio principal.

- **Enlace original**: [ExamenCOD en GitHub](https://github.com/damiancastelao/ExamenCOD)
- **Fork realizado** en mi cuenta de GitHub.

### 2. Clonación del repositorio
Una vez hecho el fork, cloné el repositorio en mi máquina local para comenzar a trabajar en los cambios y la integración de las diferentes ramas.

```bash
git clone https://github.com/TU-USUARIO/ExamenCOD.git
cd ExamenCOD
```
### 3. Creación de la rama `readme`
Para documentar todo el proceso, se creó una nueva rama llamada `readme`, donde se generó el archivo `README.md` para detallar todos los pasos y decisiones tomadas en el proyecto.

```bash
git checkout -b readme
```

4. **Fusión de ramas para la versión v1.0**
    - Se planea fusionar las ramas `datos`, `interface` y `main` para preparar la release final.
