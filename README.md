# Proyecto Final DevOps

Aplicación web desarrollada con FastAPI y ejecutada en un contenedor Docker. La imagen se publica automáticamente en Docker Hub mediante GitHub Actions, utilizando Git y GitFlow para el control de versiones.

## Grupo 4

- Giovanni Xavier Baño Jaya
- César Paúl Jara Pauta

## Tecnologías

- Python y FastAPI
- Git y GitFlow
- Docker
- GitHub Actions
- Docker Hub

## Repositorios

- GitHub: `https://github.com/Giovanni26101982/proyecto-final-devops`
- Docker Hub: `https://hub.docker.com/repository/docker/giovanni26101982/devops-final-project/general`
- Imagen: `giovanni26101982/devops-final-project:v1`

## Ejecución

```bash
docker run -d \
  --name devops-final-project \
  -p 8004:8000 \
  -e GROUP_NAME="Grupo 4" \
  -e GROUP_MEMBERS="Giovanni Bano, Paul Jara" \
  -e COURSE_NAME="Curso de Profesionalización en DevOps" \
  giovanni26101982/devops-final-project:v1
```

Abrir en el navegador:

```text
http://localhost:8004
```
