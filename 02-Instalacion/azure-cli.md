# Instalación de Azure CLI

## 1. Objetivo

Instalar Azure CLI en Ubuntu 24.04.5 LTS para interactuar y administrar servicios de Microsoft Azure mediante comandos.

## 2. Herramienta

Azure CLI es una interfaz de línea de comandos desarrollada por Microsoft que permite consultar y administrar recursos de Azure desde una terminal.

En este laboratorio se utilizará para aprender a interactuar con los servicios de Azure y explorar sus funcionalidades.

## 3. Procedimiento

Se instalaron los paquetes necesarios para administrar repositorios y certificados.

Posteriormente, se descargó la clave pública de Microsoft y se configuró su repositorio oficial para Ubuntu 24.04.

Se actualizó la lista de paquetes:

```bash
sudo apt update
```

Se instaló Azure CLI:

```bash
sudo apt install azure-cli -y
```

## 4. Verificación

Se comprobó la instalación mediante:

```bash
az --version
```

Resultado obtenido:

- Azure CLI: 2.92.0.
- Core: 2.92.0.
- Python: 3.14.9.
- Sistema: Linux.

## 5. Conclusión

Azure CLI se instaló correctamente en Ubuntu 24.04.5 LTS.

Esta herramienta permitirá interactuar con los servicios de Microsoft Azure durante las siguientes etapas del laboratorio SOC.
