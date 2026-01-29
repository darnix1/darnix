<div align="center">

<h1>🚀 Darnix Manager Pro</h1>
<h3>Script de Automatización para Servidores VPN & Túneles</h3>

<p>
  <img src="https://img.shields.io/badge/Version-v2.0-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Linux-orange?style=for-the-badge&logo=linux">
  <img src="https://img.shields.io/badge/Core-Python_3-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Language-Bash-green?style=for-the-badge&logo=gnu-bash">
</p>

</div>

<hr>

<h2>📋 Tabla de Contenidos</h2>
<ul>
  <li><a href="#instalacion">🚀 Instalación</a></li>
  <li><a href="#caracteristicas">✨ Características Principales</a></li>
  <li><a href="#protocolos">🔌 Protocolos Soportados</a></li>
  <li><a href="#usuarios">👤 Gestión de Usuarios</a></li>
  <li><a href="#utilidades">⚙️ Utilidades del Sistema</a></li>
  <li><a href="#requisitos">🖥️ Requisitos</a></li>
  <li><a href="#soporte">🆘 Soporte</a></li>
</ul>

<hr>

<h2 id="instalacion">🚀 Instalación</h2>

<p><strong>Recomendado usar <code>screen</code> para evitar interrupciones.</strong></p>

<pre><code>apt-get update && apt-get upgrade -y && \
apt-get install -y wget screen curl && \
screen -S setup wget -q https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/main/installer.sh && \
chmod +x installer.sh && ./installer.sh
</code></pre>

<h4>📌 Notas Importantes</h4>
<ul>
  <li>Si la conexión se corta, <strong>NO ejecutes nuevamente el comando</strong></li>
  <li>Recupera la sesión con: <code>screen -r setup</code></li>
  <li>Detección automática de sistema y arquitectura</li>
  <li>Recomendado en instalaciones limpias de Ubuntu o Debian</li>
</ul>

<hr>

<h2 id="caracteristicas">✨ Características Principales</h2>

<ul>
  <li>⚡ <strong>Interfaz Zero-Lag:</strong> Lectura directa del Kernel (<code>/proc</code>)</li>
  <li>🛡️ <strong>Auto-Kill Inteligente:</strong> Anti multi-login con detección padre/hijo</li>
  <li>🤖 <strong>Notificaciones Telegram:</strong> Logins, bloqueos y estado del sistema</li>
  <li>🌐 <strong>Nginx Gateway:</strong> Gestión avanzada de puertos 80 y 443</li>
  <li>🚀 <strong>Optimización de Red:</strong> BBR + Sysctl automático</li>
  <li>📦 <strong>Backup & Restore:</strong> Usuarios y configuraciones</li>
</ul>

<hr>

<h2 id="protocolos">🔌 Protocolos Soportados</h2>

<ul>
  <li>🔐 SSH Directo / Dropbear /OpenSSH</li>
  <li>⚡ Hysteria v1 (UDP) – Puerto 36712 con ofuscación</li>
  <li>🚀 Xray Core
    <ul>
      <li>VMess</li>
      <li>VLESS</li>
      <li>Trojan</li>
      <li>Transportes WS / gRPC</li>
    </ul>
  </li>
  <li>🎮 BadVPN (UDPGW) – Puerto 7300</li>
  <li>🌐 DNSTT (SlowDNS)
    <ul>
      <li>Buffer Ext: 512</li>
      <li>Buffer Int: 1800</li>
    </ul>
  </li>
  <li>🔁 WebSocket Proxy (Python / Go)</li>
</ul>

<hr>

<h2 id="usuarios">👤 Gestión de Usuarios</h2>

<ul>
  <li>➕ Crear usuarios SSH o Xray con expiración</li>
  <li>❌ Eliminar usuarios limpiamente</li>
  <li>🔄 Renovar cuentas</li>
  <li>⛔ Bloquear / Desbloquear usuarios</li>
  <li>📊 Monitor en tiempo real</li>
  <li>🔍 Ver contraseñas, UUID y días restantes</li>
</ul>

<hr>

<h2 id="utilidades">⚙️ Utilidades del Sistema</h2>

<ul>
  <li>🔁 Auto-Reboot (diario / semanal)</li>
  <li>🧹 Limpiador de cuentas expiradas</li>
  <li>🖼️ Gestor de Banner SSH (HTML soportado)</li>
  <li>📶 Speedtest integrado</li>
</ul>

<hr>

<h2 id="requisitos">🖥️ Requisitos</h2>

<h4>Sistemas Operativos</h4>
<ul>
  <li>🟢 Ubuntu 22.04 LTS (Recomendado)</li>
  <li>🟢 Ubuntu 24.04 LTS</li>
  <li>🟢 Ubuntu 25 / Deb 10 y 11</li>
</ul>

<h4>Hardware Mínimo</h4>
<ul>
  <li>CPU: 1 Core</li>
  <li>RAM: 512 MB (1 GB recomendado para Xray)</li>
  <li>IP Pública estática</li>
</ul>

<hr>

<h2 id="soporte">🆘 Soporte</h2>

<ul>
  <li>🤖 Grupo Telegram: <a href="https://t.me/botlatmx" target="_blank">https://t.me/botlatmx</a></li>
  <li>👤 Usuario: <a href="https://t.me/darnix0" target="_blank">@darnix0</a></li>
</ul>

<hr>

<div align="center">
  <p>© 2026 <strong>Darnix Manager Pro</strong></p>
  <p>Todos los derechos reservados.</p>
</div>
