---
title: Autenticación de 2 pasos
category: dev
excerpt: A veces nos hacen sufrir las contraseñas por eso recurrimos a algo que tenemos
toc: true
toc_stiky: false
---

### Para que se usan

La verificación de 2 pasos nos sirve para verificar que estamos autorizados a usar un recurso web
se basa en el principio de algo que tenemos representado en unos códigos generados por la aplicación o un token generado al vuelo.

### Cuando pueden hacernos pasar malos ratos

Al momento que perdemos la aplicación autenticador o el generador de token,
por ello debemos asignar metodos alternativos para generación de estos códigos,
o arriesgarnos a si esta almacenado en el movil que de un momento a otro se desinstale la aplicación
o peor que se pierda el dispositivo que genera los token
