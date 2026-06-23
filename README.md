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

## Prácticas realizadas

### Reconocimiento de red

- Verificación de conectividad mediante ping.
- Escaneo de puertos y servicios con Nmap.
- Identificación de versiones vulnerables.

### Análisis de protocolos

- FTP
  - Captura de credenciales en texto plano.
  - Análisis de tráfico con Wireshark.

- HTTP
  - Inspección de solicitudes GET.
  - Observación de tráfico sin cifrar.

- SSH
  - Acceso remoto seguro mediante cifrado.
  - Compatibilidad con algoritmos legacy.

### Enumeración SMB

- Descubrimiento de recursos compartidos.
- Acceso anónimo a shares expuestos.
- Identificación de permisos y restricciones.

### Explotación controlada

- Identificación de vulnerabilidades mediante Metasploit.
- Uso de módulos específicos para servicios vulnerables.
- Obtención de acceso remoto en entorno de laboratorio.

## Documentación

La documentación detallada del laboratorio se encuentra en:

- `docs/homelab.md`

## Lecciones aprendidas

- La enumeración es una de las fases más importantes de un análisis de seguridad.
- No todos los servicios expuestos son necesariamente explotables.
- Protocolos como FTP y HTTP transmiten información sin cifrar.
- SSH proporciona confidencialidad e integridad en las comunicaciones.
- Una mala configuración puede ser tan peligrosa como una vulnerabilidad software.
- La documentación es una parte fundamental del trabajo técnico.

## Aviso

Este laboratorio se ha realizado exclusivamente con fines educativos sobre máquinas vulnerables diseñadas para entrenamiento en un entorno aislado y controlado.
