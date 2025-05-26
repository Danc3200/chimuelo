# 🤖 Chimuelo - ROS 2 Dev Container

Chimuelo es un entorno de desarrollo basado en DevContainer para trabajar con ROS 2 Humble de manera portátil y reproducible. Este proyecto permite configurar un workspace de ROS 2 con todas las dependencias necesarias en segundos.

## 📦 Tecnologías usadas

- [ROS 2 Humble](https://docs.ros.org/en/humble/)
- [VSCode Dev Containers](https://code.visualstudio.com/docs/devcontainers/containers)
- [Docker](https://www.docker.com/)
- [colcon](https://colcon.readthedocs.io/en/released/)

## 🚀 Objetivo del proyecto

Facilitar el desarrollo y la prueba de paquetes ROS 2 dentro de un entorno aislado, replicable y listo para CI/CD en el futuro. Ideal para desarrolladores que trabajan con ROS 2 en distintas máquinas.

## 📁 Estructura del proyecto
chimuelo/
├── .devcontainer/
│ ├── devcontainer.json
│ └── Dockerfile
├── chimuelo_ws/

## ⚙️ Cómo usar

### 1. Requisitos previos

- Docker
- Visual Studio Code
- Extensión: Dev Containers

### 2. Clonar el repositorio

```bash
git clone https://github.com/tu_usuario/chimuelo.git
cd chimuelo
```

### 3. Entrar al Dev Container

### 4. Instalar colcon y hacer source del proyecto
```bash
apt update && apt install -y python3-colcon-common-extensions
source /opt/ros/humble/setup.bash
colcon build
```

## NOTA
La idea es que todo el desarrolla relacionado al ambiente de ros2 se haga dentro del dev container
