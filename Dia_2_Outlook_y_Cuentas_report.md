# Outlook no sincroniza

- Se refiera a cuando la aplicación de correo no puede comunicarse con los servidores de Microsoft
- En soporte esto suele deberse a problemas de credenciales guardadas,
  Perfiles dañados o fallos de red.

# Cuentas y Licencias básicas

- Dentro de M365 tener una cuenta de correo creada no es suficiente ya que es limitada
- El usuario necesita una licencia asignada (como Business Basic, Standard, etc.), para poder utilizar servicios como Outlook, Teams, OneDrive o instalar las aplicaciones de Office.

# Cómo se interconectan con otras herramientas

1. Windows Server y Active Directory: Un usuario necesita permisos y asignación de grupos correctos,
   para acceder a recursos de red (carpetas compartidas, impresoras).
2. Microsoft 365: Los permisos se manejan mediante la asignación de licencias.
   Si un usuario dice que no puede usar un servicio, el administrador primero debe revisar si la cuenta tiene licencia activa.

# Práctica guiada paso a paso

1. Ingresar a Outlook principal.
2. Arriba a la derecha presionar configuraciones.
3. Buscando cuentas a la izquierda en el nuevo panel y haciendo clic ahí.
4. Derecha junto al correo, pulsar Administrar.
5. Luego presionar Cerrar Sesión - esto para que la caché se cierre y se reinicie.
6. Volver a ingresar credenciales y así el e-mail se restablecerá.
7. Y listo, el e-mail funcionará.

<img width="522" height="350" alt="image" src="https://github.com/user-attachments/assets/3a4f7a57-94c3-4f1d-90f7-61367c433ca0" />

<img width="476" height="262" alt="image" src="https://github.com/user-attachments/assets/570944c9-7351-444e-8d73-8543acaf9685" />

# Resumen:

1. Comprendimos la diferencia crítica entre el acceso web (la nube pura) y un cliente de escritorio (la app instalada)
2. Entendimos cómo opera la sincronización.
3. Y porque la gestión de cuentas y licencias en el entorno personal de Outlook difiere visualmente del panel empresarial.
4. Aplicamos con éxito la resolución estándar de soporte cuando una app de correo deja de sincronizar.
5. Cerrar sesión y volver a autenticarse para limpiar la caché de credenciales.
