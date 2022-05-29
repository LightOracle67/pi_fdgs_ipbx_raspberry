# pi_fdgs_ipbx_raspberry
Servidor IPBX completo en Raspberry Pi

# Observaciones Importantes
Este paquete, aunque se haya diseñado originalmente para ser usado en Raspberry Pi, puede ser utilizado
en cualquier distribución Linux, siempre que los paquetes necesarios estén instalados y configurados.
Se detallará la lista completa de paquetes requeridos, en la sección "Requerimientos Mínimos", más abajo.

# Requerimientos Mínimos
  <b>Servicios necesarios:</b>
  <ul>
  <li>Servidor HTTP ("apache2; PHP 7.2 / 7.4.3 +");</li>
  <li>Servidor MYSQL ("mysql-server; phpmyadmin");</li>
  <li>Servidor DNS ("named/bind9");</li>
  <li>Servidor DHCP ("isc-dhcp-server");</li>
  <li>Servidor IPBX ("asterisk");</li>
  <li>Servidor SSH ("openssh/sshd/ssh");</li>
  </ul>

  <b>Sobre el Hardware:</b>
  <ul>
  <li>Pantalla:<p>Resolución Mínima: 640x480 (se recomienda el uso de pantallas con resolución mínima de 800x600 o superiores)</p></li>
  <li>Memoria: <p>Mínimo: 1GB | Recomendado: 2GB o más</p></li>
  <li>Procesador: <p>Cualquier Intel / AMD x86_64</p></li>
  <li>Almacenamiento: <p>3MB (no se incluye el S.O, esto es un paquete de software independiente)</p></li>
  <li>Sistema Operativo: <p>Funcionamiento y desarrollo comprobado en Ubuntu Linux 20.04. Puede ser compatible con otras versiones.</p>
  </ul>
# Acceso Directo a la Versión más reciente:
<a href="https://github.com/LightOracle67/voipmin/releases/latest">Acceder a la Descarga</a>

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
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v0.2">Versión 0.2 - Acceder a la Descarga</a>

# Alpha (v0.3):
Ahora, se muestra el estado de los servicios compatibles con este paquete dentro del "Dashboard".
<li>Los estados que se soportan son : "Activo", "Inactivo", "Cargando...".</li>
<li>Los botones de "Configuración" y "Estado (arrancar, parar, reiniciar)", aún no tienen función.</li>
<h3>Versión de Pruebas -- V0.3 (Alpha)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v0.3">Versión 0.3 - Acceder a la Descarga</a>

# Alpha (v0.3a):
<li>Se ha removido completamente el soporte de "Bootstrap".</li>
<h3>Versión de Pruebas -- V0.3a (Alpha)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v0.3a">Versión 0.3a - Acceder a la Descarga</a>

# Alpha (v0.4):
<h2>Ahora se incluye el paquete en sí, y toda la configuración necesaria en un simple comprimido tar.gz</h2>
<h3>Versión de Pruebas -- V0.4 (Alpha)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v0.4">Versión 0.4 - Acceder a la Descarga</a>

# Alpha (v0.5):
<h2>Ahora se incluye el gestor y dos ficheros necesarios para la correcta implementación.</h2>
<h3>Versión de Pruebas -- V0.5 (Alpha)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v0.5">Versión 0.5 - Acceder a la Descarga</a>

# Versión de Producción 1 (v1.0.0):
<h2>Se ha completado la programación del gestor.</h2>
<h3>Versión de Producción -- V1.0.0 (Release)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v1.0.0">Versión 1.0.0 - Acceder a la Descarga</a>

# Versión de Solución de Errores 1.0.1 (v1.0.1):
<h3>Versión de Producción -- V1.0.1 (Release)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v1.0.1">Versión 1.0.1 - Acceder a la Descarga</a>

# Versión de Solución de Errores 1.1 (v1.1):
<h3>Versión de Producción -- V1.1 (Release)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v1.1">Versión 1.1 - Acceder a la Descarga</a>

# Versión de Solución de Errores 1.1.1 (v1.1.1):
<h3>Versión de Producción -- V1.1.1 (Release)</h3>
<a href="https://github.com/LightOracle67/voipmin/releases/tag/v1.1.1">Versión 1.1.1 - Acceder a la Descarga</a>
