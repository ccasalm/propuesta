
% Sitio Web Para Comprar Entradas De Eventos "Asisteatuevento"
% Christian Casal
% Curso 2019/20

# Descripción general del proyecto

Asisteatuevento consiste en la idea de un sitio web cuya finalidad será vender entradas de cualquier tipo de evento (legal). Habrá dos tipos de usuarios, los clientes que podrán comprar sus entradas para los eventos y las empresas que venden las entradas de los eventos.

Los usuarios cliente podrán acceder a una lista de todos los eventos e incluso filtrar para buscar un evento concreto y por supuesto comprar sus entradas.

Los usuarios empresa podrán realizar un seguimiento de las entradas vendidas, así como las opiniones sobre sus eventos.


## Funcionalidad principal de la aplicación

En la página principal aparecerán los eventos ordenados de más recomendados a menos, dándole siempre la opción a la empresa vendedora de pagar un servicio para mejorar su visibilidad en dicha lista. Los eventos se podrán filtrar por nombre del evento, fecha, ubicación, nombre de empresa organizadora.

Siempre que el usuario permita conocer su ubicación, se le mostrará eventos cercanos.

Una vez cliquee en un determinado evento saldrá más información del mismo y por supuesto la opción de comprarla. 

Usuarios:
 - Cliente. Tendrán que registrarse para poder comprar entradas.Tendrán acceso a su perfil, para ver sus datos personales y historial de compras.
 - Empresa. Tendrán que registrarse y autenticarse para poder poner a la venta entradas para sus eventos. Tendrán acceso a su perfil, un seguimiento de las ventas de sus entradas, valoraciones sobre la misma empresa y sobre el evento por parte de los usuarios. Además de un servicio de pago para obtener ventajas, como por ejemplo mejorar la visibilidad en la lista de eventos recomendados.

Para que un evento se publique, primero tendrá que ser validado por un administrador del sitio web, para comprobar que el contenido es el adecuado.

Los usuarios clientes comprarán su entrada y podrán imprimirla en formato PDF desde la propia web de asisteatuevento, en dicha entrada aparecerán los datos del usuario que compró la entrada, junto a los datos de la empresa vendedora de la misma, certificando siempre la autenticidad de la entrada.

Una vez finalizada la compra por parte de un usuario cliente, se analizará sus gustos y se le ofrecerá información de próximos eventos  de la misma categoría del que compró.

Los eventos admitirán comentarios y valoraciones por parte de los usuarios, lo que proporcionará una mejor visibilidad en el lista de eventos, si la valoración es positiva por supuesto.

## Objetivos generales

* Objetivo: "Comprar entradas (usuario cliente) y vender entradas (usuario empresa)".
* Casos de uso: 
	- Invitado: "buscar y filtrar eventos", "ver valoraciones", "ver información detallada sobre un evento", "registrarse".
	- Usuario cliente: "iniciar sesión", "cerrar sesión", "comprar entrada", "comentar evento", "buscar eventos", "ver valoraciones", "ver información detallada sobre un evento", "buscar y filtrar eventos", "valorar evento", "ver perfil personal", "modificar perfil personal", "eliminar cuenta de usuario cliente", "Seguir y recibir notificaciones de eventos de una determinada empresa", "contactar con la empresa organizadora del evento".
	- Usuario empresa: "iniciar sesión", "cerrar sesión", "publicar evento", "modificar evento", "eliminar evento", "ver perfil de la empresa", "modificar perfil de la empresa", "ver valoraciones de otras empresas", "ver información detallada sobre un evento", "buscar y filtrar eventos", "contratar servicios", "ver seguimiento de las ventas de las entradas de un evento propio", "ver comentarios en sus eventos y valoraciones", "eliminar cuenta de usuario empresa".
	- Administrador: "iniciar sesión", "cerrar sesión", "comentar evento", "buscar eventos", "ver valoraciones", "ver comentarios", "eliminar comentarios", "ver información detallada sobre un evento", "buscar y filtrar eventos", "valorar evento", "ver perfiles de los usuario cliente", "modificar perfil de los usuarios cliente", "eliminar cuenta de usuario cliente", "eliminar cuenta de usuario empresa", "contactar con la empresa organizadora del evento". "publicar evento", "modificar evento", "eliminar evento", "ver perfiles de las empresas", "modificar perfiles de las empresas", "ver valoraciones de las empresas", "ver información detallada sobre un evento", "buscar y filtrar eventos", "contratar servicios", "ver seguimiento de las ventas de las entradas de un evento propio", "banear cuentas de usuarios".

# Elemento de innovación

- Amazon S3 para almacenar los datos, imágenes de los usuarios y eventos.
- Paypal. Como método de pago.
