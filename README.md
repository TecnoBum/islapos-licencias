# IslaPOS · Registro de licencias

Registro público firmado `licencias.txt`. Los clientes comprueban firma, equipo, negocio, vencimiento y revocación; no necesitan token GitHub. Contiene identificadores y huellas de equipos, sin nombres ni comprobantes de pago. No editar a mano.

## Administrador Android
Abrir IslaPOS Administrador con la contraseña del propietario. En Ajustes introducir una vez un token fine-grained de GitHub limitado a este repositorio, permiso Contents lectura y escritura. Se guarda cifrado en Android Keystore, nunca en el registro ni en la APK distribuida. Crear licencias después de verificar manualmente el pago; publicar y compartir el código. Exportar respaldos cifrados periódicos.

## Cliente
Actualizar a IslaPOS 1.0.3, copiar la huella de equipo en Más → Conexión y enviarla al solicitar licencia. Pegar el código recibido y validar con internet. Las APK anteriores no consultan este registro. Las revocaciones surten efecto al comprobar de nuevo, con margen sin conexión de hasta 10 horas. El acceso requiere reconexión tras reiniciar. Los datos no se borran al vencer.

La lectura usa la API pública de GitHub para reducir caché; está sujeta a sus límites de disponibilidad y peticiones. No hay sincronización de inventario en este archivo.
