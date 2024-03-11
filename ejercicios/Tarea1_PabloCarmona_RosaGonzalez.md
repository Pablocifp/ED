> # Tarea 1 - Especificación de Requisitos Software (ERS)
> - # Motive
>> - ### Puntos Fuertes:
>>> - No recopila Datos personales
>>> - No requiere codigo, es decir, no usan ningun metodo de codificación
>>> - Listado de tiendas más vistas
>>> - Registro de tiendas
>> - ### Puntos Debiles:
>>> - Solo permite compra online
>>> - Su uso no es gratuito para el usuario
>>> - Las tiendas no adaptadas al entorno digital se quedan atrás
>>> - Solo permite plantillas y no puede ser personalizado al gusto.
>
>> - ### Descripción General
>>> - El sistema no requiere de datos del usuario para funcionar, exceptuando el método de pago, lista las tiendas que hayan pagado una cuota mínima mostrando su contenido y ofertas actualizándose diariamente, los usuarios podrán tener beneficios dependiendo de su tarifa y un listado de sus anteriores compras y futuras, pueden registrar una tienda en sus preferencias para tener sus productos favoritos a su disposición, indicando dónde recoger su pedido, dispone solo de plantillas y no puede ser personalizado por el administrador.
>
> - # Doofinder
>> - ### Puntos Fuertes:
>>> - Entiende con más precisión los comandos por voz y los autocorrige.
>>> - Añade Filtros para búsquedas exactas
>>> - Aprende en tiempo real, guardando tus búsquedas y adaptándolo a ti
>>> - Compatible con otros programas (Wordpress, etc.)
>> - ### Puntos Debiles:
>>> - Solo permite compra online
>>> - Su uso no es gratuito para el usuario
>>> - Las tiendas no adaptadas al entorno digital se quedan atrás
>>> - A mayor el numero de peticiones mas aumenta el precio
>>> - Si alguien es mudo no le sirve el comando de voz
>> - ### Descripción General
>>> - El sistema requiere de datos del usuario para funcionar incluido el método de pago el cual se va incrementando segun el numero de peticiones, lista las tiendas que hayan pagado una cuota mínima mostrando su contenido y ofertas actualizándose diariamente, los usuarios podrán tener beneficios dependiendo de su tarifa y un listado de sus anteriores compras y futuras, sus búsquedas están personalizadas y pueden usar su voz para ello, también compartir estas búsquedas con otros usuarios, pueden registrar una tienda en sus preferencias para tener sus productos favoritos a su disposición, indicando dónde recoger su pedido.
>
> - # SmallStore
>> - ### Descripcion del problema
>>> - Estamos desarrollando un sistema de búsqueda para una aplicación que tiene como objetivo ayudar a los usuarios a encontrar productos disponibles en tiendas y pequeños comercios de una ciudad específica llamada “SmallStore”. Este sistema debe permitir:
>> - ### Usuarios
>>> - Buscar productos por nombre o categoría.
>>> - Ver una lista de tiendas que ofrecen los productos deseados.
>>> - Obtener información detallada sobre los productos, incluyendo imágenes, precios, disponibilidad y ubicación de la tienda.
>>> - Ver reseñas y calificaciones de productos y tiendas por parte de otros usuarios.
>>> - Guardar productos en una lista de favoritos para futuras compras.
>>> - Realizar pedidos, cuando esté disponible, y programar la recogida en la tienda o punto de recogida.
>>> - Registro del usuario y cuotas de pago opcional.
>>> - Compartir información sobre productos y tiendas con amigos a través de redes sociales u otras aplicaciones de mensajería.
>>> - Obtener direcciones y mapas para llegar a la tienda seleccionada.
>>> - Adaptable a distintos idiomas.
>> - ### Comercios y Tiendas
>>> - Registrar su negocio en la aplicación.
>>> - Agregar información detallada sobre sus productos, incluyendo nombre, imagen, categoría, precio y disponibilidad.
>>> - Actualizar su inventario en tiempo real.
>>> - Administrar pedidos, pagos por adelantado.
>>> - Responder a reseñas y comentarios de los usuarios.
>>> - Promocionar ofertas y descuentos especiales.
>>> - Acceder a métricas y estadísticas sobre el rendimiento de su negocio en la aplicación.
>>> - Recursos gratuitos.
>>> - Personalizacion del espacio de tu negocio.
>> - ### Descripcion General
>>> - Un buscador adaptado al usuario en el cual encuentre lo que este buscando incluyendo una opcion, reservarlo y recoger en tienda la cual indicara si tiene una pagina web propia y su respectiva localizacion en la ciudad, si el producto esta sin stock se reserva hasta que este reabastecido, este contara con un registro y uso gratuito, una cuenta de pago le permitira aceder a ofertas especiales, tus busquedas pueden ser compartidas con tu circulo personal para una mayor facilidad a la hora de indicarles ciertos productos, tambien dando libertad a los que visiten la ciudad y quieran hacer comprar sin perderse al no entender el idioma, las tiendas pueden registrarse y vender sus productos ofreciendo informacion sobre estos y si estan disponibles, tambien tendran un perfil en el que indicara sus caracteristicas y las opiniones de los clientes tanto como si posee ofertas y/o descuentos, personalizandolo a su gusto.
>>> - Fomentar el comercio y el turismo en la ciudad mostrando productos que no esten disponibles en sus provincias, paises, etc.
>> - ### Descripcion Resumen
>>> - Aplicacion que reuna todos los comercios disponibles en la ciudad en una web, para que cualquier usuario sea ciudadano o turista pueda efectuar compras en la ciudad
>> - ### Objetivos
>>> - OBJ-1 Inicio de sesion y registro de  los usuarios y comercios en el sistema.
>>> Almacenamiento de los datos de los usuarios y comercios los cuales pueden ser modificados por el cliente.
>>> - OBJ-2 Gestionar el formato de busqueda de articulos.
>>> Busqueda a traves de una barra de busqueda y filtros correspondientes, para localizar articulos o comercios concretos.
>>> - OBJ-3 Gestion de los perfiles de las tiendas.
>>> Almacenamiento de los productos y muestrario de estos incluyendo la posibilidad de modificarlo en cualquier momento por el propietario de la tienda, inclusion de la localizacion de esta y actualizacion constante de esta.
>>> - OBJ-4 Servicos que ofrecen.
>>> Aqui se engloban varios detalles como si el pago se hara a traves de la aplicacion o al recogerlo al local, si ofrece otros servicios como arreglar zapatos, costura y cualquier otro servicio extra.
>>> - OBJ-5 Gestion de las publicaciones.
>>> Un apartado donde cada usuario puede compartir su experiencia al realizar compras en un determinado comercio e incluyendo una posible calificacion de sus servicios, pudiendo compartir esta informacion con conocidos y gente cercana.
>>> - OBJ-6 Seguridad
>>> Este objetivo es importante ya que queremos que nuestros usuarios tengan una experiencia libre de estafas y engaños, al recibir una alerta de intento de estafa por parte de un usuario se debera proceder y confirmar si la denuncia fue cierta, en caso afirmativo se tomaran medidas.
>> - ### Lista inicial de requisitos:
>> - #### Requisitos funcionales:
>>> - RF1-Inicio de Sesion.
>>> - RF1.1-Registro Usuario.
>>> - RF1.1.1-Seleccion clase de usuario.
>>> - RF1.1.1.1-Cliente.
>>> - RF1.1.1.1.1-Historial del usuario.
>>> - RF1.1.1.1.2-Detalles sobre sus compras.
>>> - RF1.1.1.1.3-Producto mas comprado.
>>> - RF1.1.1.1.4-Reseñas y calificaciones realizadas.
>>> - RF1.1.1.2-Vendedor.
>>> - RF1.1.1.2.1-Negocio.
>>> - RF1.1.1.2.1.1-Datos sobre el negocio.
>>> - RF1.1.1.2.1.2-Articulos que ofrece.
>>> - RF1.1.1.2.1.3-Localizacion.
>>> - RF1.1.1.2.1.4-Otros Servicios que ofrece.
>>> - RF1.1.2-Modificacion y actualizacion de los perfiles.
>>> - RF1.1.3-Eliminacion de Perfiles.
>>> - RF2-Gestion Buscador.
>>> - RF2.1-Busqueda de productos.
>>> - RF2.1.1-Busqueda por nombre.
>>> - RF2.1.2-Busqueda por filtros.
>>> - RF2.1.2.1-Filtrar por precio.
>>> - RF2.1.2.2-Filtrar por clase.
>>> - RF2.1.2.3-Filtrar por valoraciones.
>>> - RF2.2-Informacion comercios.
>>> - RF2.2.1-Galeria de comercios
>>> - RF2.2.1.1-Nombre del Comercio.
>>> - RF2.2.1.2-Imagen del comercio
>>> - RF2.2.2-Productos.
>>> - RF2.2.2.1-Nombre producto.
>>> - RF2.2.2.2-Precio producto.
>>> - RF2.2.2.3-Stock.
>>> - RF2.2.2.3.1-Reservar.
>>> - RF2.2.2.4-Imagen del producto
>>> - RF2.2.2.5-Comercio que posee el producto.
>>> - RF2.2.3-Pedidos online.
>>> - RF2.2.3.1-Realizar pedido.
>>> - RF2.2.3.2-Recogida en tienda.
>>> - RF2.2.4-Lista de futuras compras.
>>> - RF2.2.5-Compartir informacion.
>>> - RF3-Inventario de las tiendas.
>>> - RF3.1-Modificacion de los productos.
>>> - RF3.1.1-Publicar productos
>>> - RF3.1.2-Stock
>>> - RF3.1.3-Eliminar Producto
>>> - RF3.2-Recogidas
>>> - RF3.2.1-Reservas Pendientes
>>> - RF3.3-Ofertas
>>> - RF3.4-Calificacion del Comercio
>>> - RF4-Publicaciones
>>> - RF4.1-Publicaciones del usuario
>>> - RF4.1.1-Añadir comentarios
>>> - RF4.1.1.1-Modificar comentario
>>> - RF4.1.1.2-Eliminar comentario
>>> - RF4.1.2-Poner calificacion
>>> - RF4.1.2.1-Modificar calificacion
>>> - RF4.1.2.2-Eliminar calificacion
>>> - RF4.1.3-Valoracion aplicacion
>>> - RF4.1.3.1-Calificacion de su funcionamiento.
>>> - RF4.1.3.2-Sugerencias.
>>> - RF4.2-Consulta de valoraciones.
>>> - RF5-Seguridad.
>>> - RF5.1-Denuncias.
>>> - RF5.1.1-Estafa.
>>> - RF5.1.1.1-Nombre de usuario.
>>> - RF5.1.1.2-Pruebas estafa.
>>> - RF5.1.1.3-Iniciar devolucion.
>>> - RF5.1.1.4-Eliminacion de posible estafador.
>>> - RF5.2-Pagos.
>>> - RF5.2.1-Pagos online.
>>> - RF5.2.1.1-Metodo de pago.
>>> - RF5.2.2-Pagos en tienda.
>> - #### Requisitos no funcionales:
>>> - RNF1-Funcionalidad.
>>> - RNF1.1-Debe aguantar un flujo constante de usuarios que se conecten y desconecten.
>>> - RNF1.2-Transmision de informacion en un corto periodo sin colapsos.
>>> - RNF2-Seguridad.
>>> - RNF2.1-Almacenamiento de datos de usuarios y comercios registrados actualizados periodicamente.
>>> - RNF2.2-Cada usuario tendra su propio perfil que estara protegido por contraseñas.
>>> - RNF3-Funcionamiento.
>>> - RNF3.1-Facilidad de uso para todas las personas.
>>> - RNF3.2-Tutoriales disponibles para aquellos con dificultades.
>>> - RNF4-Disponibilidad.
>>> - RNF4.1-Disposicion de la aplicacion en todo momento, salvo cuando la aplicacion este en mantenimiento.
>>> - RNF4.2-Evitar posibles caidas.
>>> - RNF5-Implementacion.
>>> - RNF5.1-Debe tener soporte web y estar disponible para otros dispositivos.
>>> - RNF6-Operaciones.
>>> - RNF6.1-Cada tipo de usuario estara restringido, si el usuaro es un cliente puede interactuar de forma publica con otros usuarios, pero aquellos con perfil de vendedor no podran realizar ninguna de las funciones que hacen los usuarios clientes.
>>> - RNF7-Soporte.
>>> - RNF7.1-Debe funcionar en cualquier buscador que este usando el dispositivo.
>>> - RNF8-Legalidad.
>>> - RNF8.1-El sistema tendra licencia y derechos reservados, por lo que su uso compartido esta prohibido.
>>> - RNF8.2-Los desarrolladores se haran cargo del mantenimiento del sistema.
>>> - RNF8.2-Si se detecta algun intento o se ha cometido una estafa inmediatamente si se a reputado dicha actividad la cuenta en cuestion sera elimada y se pondra en alerta a los usuarios, amonestandoles por las molestias.
>> - #### Requisitos de Informacion
>>> - RI1-Usuario.
>>> - Informacion para la creacion de una cuenta en la aplicacion.
>>> - Correo.
>>> - Nombre.
>>> - Apellidos.
>>> - Tipo de Cuenta (Cliente, Vendedor).
>>> - Publica o Privada (En el caso de ser Cliente).
>>> - Contraseña.
>>> - Numero de telefono.
>>> - Historial.
>>> - Localizacion GPS.
>>> - RI2-Vendedor.
>>> - Informacion necesaria del perfil de la tienda, sus productos y servicios ofrecidos.
>>> - Nombre de la tienda.
>>> - Imagen de la tienda.
>>> - Localizacion GPS de la tienda.
>>> - Descripcion.
>>> - Articulos que posee.
>>> - Servicios que ofrece.
>>> - Verificacion.
>>> - Numero de visitas.
>>> - Comentarios de las Tiendas y la calificacion general.
>>> - RI3-Pago.
>>> - El metodo por el cual se realizaran las transacciones.
>>> - Tarjeta.
>>> - Pago en Local.
>>> - Otros metodos de pago.
>>> - RI4-Aplicacion.
>>> - Informacion General de la aplicacion y su funcionamiento en algunos aspectos.
>>> - Descripcion sobre que hacemos.
>>> - Seguridad de los Perfiles.
>>> - Permisos.
>>> - Barra de Busqueda personalizada.
>>> - Filtros.
>>> - Almacenamiento de futuras compras.
>>> - Galeria de tiendas.
>> - ## Glosario de Terminos
>>> - 1-Usuarios: Creacion de los usuarios indicando sus datos.
>>> - 1.1-Tipos de Usuarios: Dependiendo del tipo que se escoja tendra una interaccion distinta con la aplicacion.
>>> - 1.2-Publica y Privada: Esto indica si el perfil del Cliente es publico compartiendo donde realizo sus compras en caso de ser publico, al ser privado estara restringido a los usuarios que seleccione.
>>> - 2-Vendedor: Creacion del perfil del vendedor indicando sus datos el cual posee un perfil publico y no puede observar el perfil de los clientes.
>>> - 2.1-Perfil del Negocio: Añade informacion descriptiva de la tienda como de los productos y servicios que ofrece.
>>> - 2.2-Confirmacion de que este verificada: Comprobacion de que la tienda creada sea verdadera y no una estafa.
>>> - 2.3-Calificacion: Seccion en la cual se podra comentar, calificar y visualizar los clientes que han interactuado con ella.
>>> - 3-Funcionamiento de la Aplicacion: Apartados que identifican el funcionamiento de algunas secciones.
>>> - 3.1-Barra de Busqueda: Pestaña en la que indicara por teclado que resultado esta buscando, pudiendo mejorar los resultados con un filtro.
>>> - 3.2-Seguridad: Apartados en los cuales se pueden denunciar o avisar sobre posibles estafas o fraudes que se esten realizando.
>>> - 3.3-Permisos: Administracion de los permisos los cuales permiten realizar busquedas mediante fotos y obtener la localizacion geografica tanto de clientes como tiendas para llegar hasta ellas con facilidad.
>>> - 3.4-Acceso Directo: La aplicacion no necesita que el usuario tenga que poner su contraseña y cuenta para acceder, esto es opcional.
>>> - 3.5-Galeria de Tiendas: Muestra las tiendas que encajen con la busqueda realizada y posibilita moverse entre ellas.
>>> - 3.6-Historial: Guarda los resultados de busquedas anteriores.
>>> - 4-Otros metodos de pago: Esta seccion va incluida por si se quiere hacer pagos con aplicaciones como Bizum entre otras.
>>> - 4.1-Almacenamiento de futuras compras: Almacena en la seccion de compra los productos que desea sin necesidad de comprarlos de uno en uno, una vez confirmado ya se tramitara el pago.
>> - ### Trabajos que hemos hecho cada uno:
>>> - Pablo: Motive y Doofinder con sus puntos fuertes y debiles.
>>> - Conjunto: Usuarios, Comercios y Tiendas, Descripción General, RF, RNF, RI, Glosario.
>>> - Rosa: Traspaso del Documento a Markdown.