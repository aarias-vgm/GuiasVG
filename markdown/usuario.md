# GUÍA USUARIO :bust_in_silhouette:

[🔙 Volver](../README.md)

## Odoo

### Crear usuario en Odoo

1. :arrow_right: Ir a `Odoo -> Usuarios`.
1. :new: Crear.
1. :keyboard: Escribir **nombre** y **correo**.
1. :lock: Establecer **permisos**.
1. :floppy_disk: Guardar.
1. :key: [Cambiar **contraseña**][cambiar-contraseña-odoo].
1. :envelope: [Enviar credenciales por correo][enviar-credenciales-correo].

### Eliminar usuario en Odoo

1. :arrow_right: Ir a `Odoo -> Usuarios`.
1. :computer_mouse: Click en _usuario_.
1. :pencil2: Editar **correo** \(ejemplo: poner el sufijo "_old"\).
1. :floppy_disk: Guardar.
1. :key: [Cambiar **contraseña**][cambiar-contraseña-odoo].
1. :ballot_box_with_check: Seleccionar _usuario_.
1. :computer_mouse: Click en `Acción`
1. :open_file_folder: Archivar.
1. :floppy_disk: Guardar.

### Cambiar contraseña en Odoo

1. :ballot_box_with_check: Seleccionar _usuario_.
1. :computer_mouse: Click en `Acción -> Cambiar contraseña -> Nueva contraseña`.
1. :keyboard: Escribir **contraseña**.
1. :floppy_disk: Guardar.

## Zoho

### Crear usuario en Zoho

1. :arrow_right: Ir a `Zoho -> Consola de administración -> Usuarios`.
1. :computer_mouse: Click en `Agregar -> Comprar ahora -> Mejorar versión User / Complementos`.
1. :pushpin: Establecer _`[Adicional user = 1]`_ en _**Nro. de Unidades**_.
1. :arrow_forward: Continuar.
1. :key: [Cambiar **contraseña**][cambiar-contraseña-odoo].
1. :envelope: [Enviar credenciales por correo][enviar-credenciales-correo].

### Desactivar usuario en Zoho

1. :key: [Cambiar **contraseña**][cambiar-contraseña-zoho].
1. :arrow_right: Ir a `Zoho -> Consola de administración -> Usuarios`.
1. :computer_mouse: Click en _usuario_.
1. :mag_right: Buscar `Información personal`.
1. :pushpin: Establecer _`[Situación = Inactivo]`_.
1. :ballot_box_with_check: Seleccionar:  
    > - [X] Bloquear correos electrónicos entrantes  
    > - [X] Eliminar reenvío de correo electrónico  
    > - [X] Eliminar del grupo  
    > - [X] Quitar alias de correo electrónico  
1. :arrow_forward: Continuar.

### Eliminar usuario en Zoho

1. :arrow_right: Ir a `Zoho -> Consola de administración -> Usuarios`.
1. :ballot_box_with_check: Seleccionar _usuario_.
1. :wastebasket: Eliminar
1. :arrow_forward: Continuar.

### Cambiar contraseña en Zoho

1. :arrow_right: Ir a `Zoho -> Consola de administración -> Usuarios`.
1. :computer_mouse: Click en _usuario_.
1. :mag_right: Buscar `Seguridad -> Cambiar contraseña`.
1. :keyboard: Escribir **contraseña**.
1. :ballot_box_with_check: Seleccionar:  
    > - [ ] Enviar credenciales por correo electrónico
    > - [ ] Forzar a usuario a cambiar de contraseña en el primer inicio de sesión
    > - [X] Cierre sesión en todos los dispositivos (recomendado)
1. :arrow_forward: Continuar.

## Otros

### Enviar credenciales por correo

1. Enviar credenciales por correo:

```plaintext
Nuevas credenciales de Odoo y Zoho para el usuario USUARIO:

Usuario: USUARIO
Contraseña: CONTRASEÑA
```

[cambiar-contraseña-odoo]: #cambiar-contraseña-en-odoo
[cambiar-contraseña-zoho]: #cambiar-contraseña-en-zoho
[enviar-credenciales-correo]: #enviar-credenciales-por-correo