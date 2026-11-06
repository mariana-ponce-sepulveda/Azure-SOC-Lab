# Instalación de Ansible

## 1. Objetivo

Instalar Ansible en Ubuntu 24.04.5 LTS para aprender a automatizar tareas de administración y configuración de sistemas.

## 2. Herramienta

Ansible es una herramienta de automatización que permite ejecutar comandos y configurar equipos mediante instrucciones organizadas en playbooks.

En este laboratorio se utilizará para practicar tareas de administración y automatización relacionadas con un entorno SOC.

## 3. Procedimiento

Primero se actualizó la lista de paquetes de Ubuntu:

```bash
sudo apt update
```

Posteriormente, se instaló Ansible:

```bash
sudo apt install ansible -y
```

## 4. Verificación

Se comprobó la instalación mediante:

```bash
ansible --version
```

Resultados obtenidos:

- Ansible: 9.2.0.
- Ansible Core: 2.16.3.
- Python: 3.12.3.

También se realizó una prueba local:

```bash
ansible localhost -m ping -c local
```

Resultado:

```text
localhost | SUCCESS
"changed": false,
"ping": "pong"
```

La prueba confirmó que Ansible puede ejecutar tareas correctamente en el equipo local.

## 5. Conclusión

Ansible se instaló correctamente y superó la prueba de ejecución local.

Esta herramienta permitirá aprender a automatizar tareas y administrar sistemas durante las siguientes etapas del laboratorio SOC.
