# Instalación de Terraform

## 1. Objetivo

Instalar Terraform en Ubuntu 24.04.5 LTS para utilizarlo en la administración de infraestructura mediante código (IaC).

## 2. Herramienta

Terraform es una herramienta desarrollada por HashiCorp que permite definir, crear y administrar infraestructura mediante archivos de configuración.

En este laboratorio se utilizará para aprender sobre infraestructura como código y comprender cómo se pueden automatizar recursos de un entorno SOC.

## 3. Procedimiento

Se actualizó la lista de paquetes:

```bash
sudo apt update
```

Se instalaron las herramientas necesarias:

```bash
sudo apt install -y gnupg software-properties-common curl
```

Se descargó la clave pública de HashiCorp y se agregó su repositorio oficial a Ubuntu.

Posteriormente, se actualizó la lista de paquetes y se instaló Terraform:

```bash
sudo apt install terraform -y
```

## 4. Verificación

Se comprobó la instalación mediante:

```bash
terraform --version
```

Resultado obtenido:

- Versión: Terraform v1.17.1.
- Sistema: linux_amd64.

## 5. Conclusión

Terraform se instaló correctamente en Ubuntu 24.04.5 LTS. Esta herramienta permitirá comenzar a trabajar con infraestructura como código en las siguientes etapas del laboratorio SOC.
