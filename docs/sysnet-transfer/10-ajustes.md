### Accede al portal en modo Administrador

1. Ingresa al portal de SYSNET Transfer con tus credenciales.
2. Dirígete al menú principal y selecciona la opción **Ajustes**.

![Imagen 35](https://raw.githubusercontent.com/lncproducciones/sysnet-docs/refs/heads/main/sysnet-transfer-wiki-imgs/035.png)

La sección de ajustes está organizada en bloques temáticos.

Dentro de **General**, se puede registrar y/o modificar el número de teléfono de WhatsApp donde se gestionará el soporte a los usuarios.

![Imagen 36](https://raw.githubusercontent.com/lncproducciones/sysnet-docs/refs/heads/main/sysnet-transfer-wiki-imgs/036.png)

**Tasas de cambio**: Agregue el valor de la tasa de cambio correspondiente, esta se visualizará al inicio de la plataforma.

![Imagen 37](https://raw.githubusercontent.com/lncproducciones/sysnet-docs/refs/heads/main/sysnet-transfer-wiki-imgs/037.png)

#### Portal de Autogestión "Mi Transfer" (Próximamente)

![Imagen 38](https://raw.githubusercontent.com/lncproducciones/sysnet-docs/refs/heads/main/sysnet-transfer-wiki-imgs/038.png)

#### Activar el módulo

* Activa el interruptor **Estado del módulo** para habilitar la autogestión de clientes.

#### Logotipo personalizado

* Haz clic en el área de carga de imagen.
* Sube tu logo con dimensiones **288x80 px** para asegurar una visualización óptima.
* Verifica que el logo se vea correctamente en la vista previa.

#### Subdominio web

* En el campo **Subdominio**, escribe el subdominio que deseas usar para el acceso de clientes (ejemplo: _clientes.tuempresa.com_).
* Asegúrate de que el subdominio esté correctamente vinculado a tu dominio principal.

#### Sucursal por defecto

* Usa el menú desplegable para elegir la sucursal que se asignará automáticamente a los clientes que ingresen por este portal.
* Ejemplo: **Oficina Principal** si es tu sede central.

#### Agente por defecto

* Introduce el nombre del agente que gestionará las solicitudes entrantes por defecto en el canal de Autogestión.

#### Llave ePayco

* Copia y pega tu **llave pública de ePayco** en el campo correspondiente.
* Esta llave permite integrar pagos en línea dentro del portal de autogestión.

### Recomendaciones adicionales

* **Verifica cada campo antes de guardar**, para evitar errores de configuración.
* **Prueba el portal como cliente** una vez configurado para asegurarte de que todo funcione correctamente.

![Imagen 39](https://raw.githubusercontent.com/lncproducciones/sysnet-docs/refs/heads/main/sysnet-transfer-wiki-imgs/039.png)

### Configuración de notificaciones

* **Activar el módulo**: Activa el interruptor que dice: **Habilitar el módulo de notificación por correo electrónico de las transferencias y pagos recibidos.**
* **Configurar el servidor SMTP**: En el campo _Servidor SMTP_, ingresa la dirección del servidor de correo saliente (ejemplo: smtp.tuempresa.com).
* En **Puerto**, escribe el número de puerto correspondiente (comúnmente 587 o 465).
* **Autenticación**: En **Usuario**, coloca el correo electrónico que se usará para enviar las notificaciones. En **Contraseña**, ingresa la clave de acceso del correo.
* **Definir destinatarios**: En el campo **Destinatario(s)**, escribe hasta dos correos electrónicos que recibirán las notificaciones.

Finalmente. haz clic en el botón de **Guardar cambios** para aplicar la configuración.

### Recomendaciones técnicas

* Verifica que el servidor SMTP esté activo y que las credenciales sean correctas.
* Si usas servicios como Gmail, asegúrate de habilitar el acceso a aplicaciones menos seguras o generar una contraseña específica.
* Realiza una **prueba de envío** para confirmar que los correos llegan correctamente.

---
<img src="../img/logo-web.png" alt="" style="height: 30px !important;" />