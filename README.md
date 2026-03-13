# RHEL9-Security-Hardening
Implementación de medidas de robustecimiento de seguridad (SELinux, SSH, IPTables) en Red Hat Enterprise Linux 9.
Hardening y Aseguramiento de Infraestructura RHEL 9

🛡️ Descripción del Proyecto

Este proyecto documenta la implementación de medidas de robustecimiento (Hardening) sobre un entorno Red Hat Enterprise Linux 9. El objetivo principal es reducir la superficie de ataque del servidor aplicando políticas de control de acceso mandatorio, aseguramiento de servicios críticos y gestión perimetral.

🚀 Pilares Técnicos

Control de Acceso Mandatorio (MAC): Configuración de SELinux en modo Enforcing.

Aseguramiento de SSH: Cambio de puerto estándar, banners legales y límites de autenticación.

Seguridad de Red: Implementación de políticas IPTables con enfoque de "Denegar por defecto".

Monitoreo SOC: Análisis de logs de seguridad en /var/log/secure.

📁 Estructura del Repositorio

/docs: Contiene el informe técnico detallado en PDF.

/img: Capturas de pantalla de la terminal y configuraciones.

README.md: Resumen ejecutivo del proyecto.

🛠️ Herramientas Utilizadas

Red Hat Enterprise Linux 9

Wireshark (Análisis de tráfico FTP/SSH)

img/imagenes III/RHEL_10.png

Nmap (Escaneo de vulnerabilidades)

Oracle VirtualBox

Autor: Christian Alberto Quispe Alarcón

Rol: Analista SOC en formación

Certificaciones Relacionadas: Cisco CyberOps, Red Hat System Admin.
