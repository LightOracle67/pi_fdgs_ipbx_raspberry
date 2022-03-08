# pi_fdgs_ipbx_raspberry
Servidor IPBX completo en Raspberry Pi

# Observaciones Importantes
Este paquete, aunque se haya diseñado originalmente para ser usado en Raspberry Pi, puede ser utilizado
en cualquier distribución Linux, siempre que los paquetes necesarios estén instalados y configurados.
Se detallará la lista completa de paquetes requeridos, al final de este fichero.

# Alpha (v0):
Comienza el proceso de creación del proyecto en sí.
Por ahora, las funciones incluidas son:
·Inicio de Sesión con PHP y MySQL (encriptado)
·Dashboard (Inicio con información relevante sobre el servidor en sí)

Las funciones faltantes:
·Añadir al dashboard el estado de los servicios
·Administrar los servicios (Arranque (al inicio), Parada o Reinicio), desde el "Dashboard"
·Administrar la configuración de los servicios desde páginas individuales, recogiendo la configuración de los mismos y sirviéndola al usuario.
  
# Alpha (v0.1):
·Se añade soporte de Bootstrap para compatibilidad, portabilidad y diseño "responsive".

# Alpha (v0.2):
·Continúa la adaptación del "Dashboard".
·Se añaden nuevos contadores ("Porcentaje de Carga promedia del Servidor", "Carga de la CPU", "Carga total de Memoria Física", "Espacio consumido en Disco")
·Se añaden botones para gestionar el estado de los servicios, aún sin función.
-- Primer "Release" publicado
