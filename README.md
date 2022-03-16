# pi_fdgs_ipbx_raspberry
Servidor IPBX completo en Raspberry Pi

# Observaciones Importantes
Este paquete, aunque se haya diseñado originalmente para ser usado en Raspberry Pi, puede ser utilizado
en cualquier distribución Linux, siempre que los paquetes necesarios estén instalados y configurados.
Se detallará la lista completa de paquetes requeridos, en la sección "Requerimientos Mínimos", más abajo.

# Requerimientos Mínimos
  <b>Servicios necesarios:</b>
  <ul>
  <li>Servidor HTTP ("apache2");</li>
  <li>Servidor MYSQL ("mysql-server");</li>
  <li>Servidor DNS ("named/bind9");</li>
  <li>Servidor DHCP ("isc-dhcp-server");</li>
  <li>Servidor IPBX ("asterisk");</li>
  <li>Servidor SSH ("openssh/sshd/ssh");</li>
  </ul>

  <b>Sobre el Hardware:</b>
  <ul>
  <li>Pantalla:<p>Resolución Mínima: 565x533 (se recomienda el uso de pantallas con resolución mínima de 800x600)</p></li>
  <li>Memoria: <p>Mínimo: 1GB | Recomendado: 2GB o más</p></li>
  <li>Procesador: <p>Cualquier Intel / AMD x86_64</p></li>
  <li>Almacenamiento: <p>3MB (no se incluye el S.O, esto es un paquete de software independiente)</p></li>
  <li>Sistema Operativo: <p>Funcionamiento y desarrollo comprobado en Ubuntu Linux 20.04. Puede ser compatible con otras versiones.</p>
  </ul>
  
# Alpha (v0):
Comienza el proceso de creación del proyecto en sí.
Por ahora, las funciones incluidas son:
<li>Inicio de Sesión con PHP y MySQL (encriptado)</li>
<li>Dashboard (Inicio con información relevante sobre el servidor en sí)</li><br>
Las funciones faltantes:
<li>Añadir al dashboard el estado de los servicios</li>
<li>Administrar los servicios (Arranque (al inicio), Parada o Reinicio), desde el "Dashboard"</li>
<li>Administrar la configuración de los servicios desde páginas individuales, recogiendo la configuración de los mismos y sirviéndola al usuario.</li>
  
# Alpha (v0.1):
<li>Se añade soporte de Bootstrap para compatibilidad, portabilidad y diseño "responsive".</li>

# Alpha (v0.2):
Continúa la adaptación del "Dashboard":
<li>Se añaden nuevos contadores ("Porcentaje de Carga promedia del Servidor", "Carga de la CPU", "Carga total de Memoria Física", "Espacio consumido en Disco")</li>
<li>Se añaden botones para gestionar el estado de los servicios, aún sin función.</li>
<h3>Primera Versión de Pruebas del paquete publicada -- V0.2 (Alpha)</h3>
<a href="https://github.com/LightOracle67/pi_fdgs_ipbx_raspberry/releases/tag/v0.2">Versión 0.2 - Acceder a la Descarga</a>
