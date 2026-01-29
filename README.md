<div align="center">

# 🚀 Darnix Manager Pro  
### Script de Automatización para Servidores VPN & Túneles

![Version](https://img.shields.io/badge/Version-v2.0-blueviolet?style=for-the-badge)
![Linux](https://img.shields.io/badge/Platform-Linux-orange?style=for-the-badge&logo=linux)
![Python](https://img.shields.io/badge/Core-Python_3-blue?style=for-the-badge&logo=python)
![Bash](https://img.shields.io/badge/Language-Bash-green?style=for-the-badge&logo=gnu-bash)

</div>

---

## 📋 Tabla de Contenidos
- [🚀 Instalación](#-instalación)
- [✨ Características Principales](#-características-principales)
- [🔌 Protocolos Soportados](#-protocolos-soportados)
- [👤 Gestión de Usuarios](#-gestión-de-usuarios)
- [⚙️ Utilidades del Sistema](#️-utilidades-del-sistema)
- [🖥️ Requisitos](#️-requisitos)
- [🆘 Soporte](#-soporte)

---

## 🚀 Instalación

### Paso 1: Ejecutar el instalador

> ⚠️ **Recomendado usar `screen` para evitar cortes durante la instalación**

Ejecuta como **root**:

```bash
apt-get update && apt-get upgrade -y && \
apt-get install -y wget screen curl && \
screen -S setup wget -q https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/main/installer.sh && \
chmod +x installer.sh && ./installer.sh
📌 Notas Importantes
Si se corta la conexión, NO vuelvas a ejecutar el comando
Recupera la sesión con:
Copiar código
Bash
screen -r setup
El script detecta automáticamente SO y arquitectura
Recomendado en instalaciones limpias de Ubuntu o Debian
✨ Características Principales
⚡ Interfaz Zero-Lag
Menú en Python que lee directamente del Kernel (/proc), mostrando RAM y CPU sin latencia.
🛡️ Auto-Kill Inteligente
Sistema anti multi-login que distingue procesos padre/hijo sin afectar usuarios legítimos.
🤖 Notificaciones Telegram
Alertas en tiempo real: logins, bloqueos, estado del servidor.
🌐 Nginx Gateway
Gestión avanzada de puertos 80 / 443 para coexistencia de túneles y servicios web.
🚀 Optimización de Red
Instalación automática de BBR + ajustes sysctl para máximo rendimiento TCP/UDP.
📦 Backup & Restore
Copias de seguridad completas de usuarios y configuraciones.
🔌 Protocolos Soportados
Darnix Manager Pro automatiza los protocolos más estables del mercado:
🔐 SSH Directo / Dropbear
⚡ Hysteria v1 (UDP)
Puerto 36712 con ofuscación (ideal redes inestables)
🚀 Xray Core
VMess
VLESS
Trojan
Transportes WS / gRPC
🎮 BadVPN (UDPGW)
Puerto 7300 (juegos y videollamadas)
🌐 DNSTT (SlowDNS)
Buffers optimizados:
Ext: 512
Int: 1800
🔁 WebSocket Proxy
Proxy ligero en Python / Go para inyecciones HTTP
👤 Gestión de Usuarios
Administra clientes sin memorizar comandos:
➕ Crear Usuarios
SSH o Xray con límite de conexiones y expiración
❌ Eliminar Usuarios
🔄 Renovar Cuentas
⛔ Bloquear / Desbloquear
📊 Monitor en Tiempo Real
🔍 Detalles de Cuenta
Contraseñas
UUID
Días restantes
⚙️ Utilidades del Sistema
Herramientas integradas para mantenimiento:
🔁 Auto-Reboot (diario / semanal)
🧹 Limpiador de Expirados
🖼️ Gestor de Banner SSH (HTML soportado)
📶 Speedtest Integrado
🖥️ Requisitos
Sistemas Operativos
🟢 Ubuntu 22.04 LTS (Recomendado)
🟢 Ubuntu 24.04 LTS
🟢 Ubuntu 25.04 LTS
🟢 Debian 10 / 11
Hardware Mínimo
CPU: 1 Core
RAM: 512 MB
1 GB recomendado para uso intensivo de Xray
Red: IP pública estática
🆘 Soporte
📲 Telegram Bot:
👉 @botgenmx_bot
👤 Usuario:
👉 https://t.me/darnix0
📢 Canal Oficial:
https://t.me/botlatmx
�

© 2026 Darnix Manager Pro
Todos los derechos reservados.
�

