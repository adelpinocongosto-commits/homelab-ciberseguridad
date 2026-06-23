# homelab-ciberseguridad

Laboratorio personal de ciberseguridad desarrollado con VirtualBox para aprender conceptos de redes, análisis de tráfico, enumeración de servicios y explotación controlada de vulnerabilidades en un entorno aislado.

## Entorno

- Kali Linux -> Atacante
- Metasploitable 2 -> Víctima Vulnerable
- Red interna VirtualBox

## Objetivos

- Aprender administración básica de sistemas Linux.
- Comprender el funcionamiento de redes TCP/IP.
- Practicar enumeración de servicios y reconocimiento.
- Analizar tráfico de red con Wireshark.
- Utilizar herramientas habituales en ciberseguridad.
- Documentar el proceso de aprendizaje de forma estructurada

 ## Alcance del proyecto
 
Este laboratorio simula un entorno de pentesting básico en el que se realiza:

- Reconocimiento de red
- Enumeración de servicios expuestos
- Análisis de protocolos inseguros
- Acceso remoto a sistemas
- Explotación controlada de vulnerabilidades conocidas

## Red

- Plataforma: VirtualBox
- Tipo de red: Internal Network
- Nombre: `intnet`
- Comunicación exclusiva entre máquinas virtuales
- Sin exposición a Internet

## Herramientas utilizadas

- Nmap
- Wireshark
- SMBClient
- OpenSSH
- Metasploit Framework
- VirtualBox

## Resumen de prácticas

Las prácticas realizadas incluyen:

- Reconocimiento de red con Nmap
- Análisis de tráfico FTP, HTTP y SMB
- Enumeración de recursos compartidos
- Acceso remoto mediante SSH
- Explotación controlada con Metasploit

## Documentación

La documentación técnica completa se encuentra en:

 `docs/homelab.md`

## Lecciones aprendidas

- La enumeración es clave en cualquier test de intrusión
- Servicios mal configurados pueden exponer información sensible
- Protocolos sin cifrar (FTP, HTTP) son inseguros por diseño
- SSH proporciona comunicación cifrada y segura
- La documentación es parte fundamental del proceso técnico

## Aviso

Este proyecto se ha realizado exclusivamente con fines educativos en un entorno controlado utilizando máquinas vulnerables diseñadas para prácticas de ciberseguridad.
