# Ideas de proyecto · DAW

Veinte ideas de partida. Todas tienen un cliente o una necesidad identificable y se pueden construir en las horas del
módulo apoyándose en lo que ya trabajáis en otros módulos. Podéis combinarlas, recortarlas o proponer otra: lo que no
cambia es que tiene que haber **un cliente, un plan y algo que funcione en la demo**.

Cómo elegir: coged una que os guste, buscad un cliente real (un comercio, una asociación, un departamento del centro,
una familia) y preguntadle qué le haría falta de verdad. El proyecto bueno sale de esa conversación, no de la lista.

| # | Idea | Qué es | Tecnologías del ciclo | Lo mínimo que tiene que funcionar |
|---|---|---|---|---|
| 1 | **Reservas de aulas y talleres** | Web para que el profesorado reserve espacios del centro con calendario, roles (profesor / jefatura) y avisos. | Laravel, MySQL, API REST, Nginx, Docker, SMTP | Un profesor reserva, jefatura aprueba, llega el correo y el calendario refleja la ocupación |
| 2 | **Préstamo de material con QR** | Inventario y préstamo de portátiles, cámaras y herramientas con etiquetas QR, histórico y avisos de devolución. | Laravel o PHP, MySQL, API REST, generación de QR, JS | Escanear un QR con el móvil registra un préstamo y la devolución; panel con lo que está fuera |
| 3 | **Tienda para un comercio local** | Catálogo y pedidos de un comercio real (sin pago online): carrito, pedido por correo/WhatsApp, panel del comerciante. | Laravel, MySQL, API REST, JS, SMTP | El cliente hace un pedido, el comerciante lo ve en su panel y cambia su estado |
| 4 | **Incidencias TIC del centro** | Tickets para avisar de equipos rotos o fallos de red: formulario, cola, estados, responsable y estadísticas. | Laravel, MySQL, API REST, gráficas JS | Alta de incidencia, asignación, cierre y gráfica de incidencias por aula |
| 5 | **Portal de prácticas en empresa** | Ofertas de FCT/dual, candidaturas del alumnado y seguimiento por el tutor. | Laravel, MySQL, roles, API REST | Empresa publica oferta, alumno se apunta, tutor ve el estado |
| 6 | **Votaciones en tiempo real** | Encuestas y votaciones del centro (delegados, actividades) con resultados en directo en una pantalla. | PHP/Laravel, MySQL, API REST, JS con actualización periódica o WebSockets | Votación con un voto por usuario y resultados que se actualizan solos en otra pantalla |
| 7 | **Panel IoT del aula** | Sensores (temperatura, CO2, ruido) que envían datos a una API y un panel web con gráficas y alertas. | IoT (ESP32/Raspberry), API REST en PHP/Python, MySQL, gráficas JS | Un sensor real enviando datos cada minuto y una gráfica del último día con una alerta |
| 8 | **Mercadillo de segunda mano del centro** | Anuncios de compra-venta entre alumnado con fotos, categorías, favoritos y mensajes básicos. | Laravel, MySQL, subida de imágenes, API REST | Publicar un anuncio con foto, buscar por categoría y contactar al vendedor |
| 9 | **Menú del comedor con alérgenos** | Menú semanal con alérgenos, valoración de platos y avisos; panel para cocina. | PHP/Laravel, MySQL, API REST, JS | Cocina publica el menú, se filtra por alérgeno y el alumnado valora los platos |
| 10 | **Actividades extraescolares** | Inscripción en clubs y actividades: plazas, listas de espera, grupos y avisos por correo. | Laravel, MySQL, SMTP, roles | Inscribirse, quedar en lista de espera y recibir el aviso cuando hay plaza |
| 11 | **Generador de landings para pymes** | Herramienta para que un comercio sin web cree una landing a partir de plantillas y la publique con un clic. | PHP/Laravel, plantillas, Nginx, Docker, despliegue | Elegir plantilla, rellenar datos y obtener una web publicada en una URL propia |
| 12 | **Citas para una peluquería o clínica** | Reserva de citas con horarios, servicios, recordatorio por correo y agenda del profesional. | Laravel, MySQL, SMTP, API REST | Un cliente reserva, el profesional la ve en su agenda y llega el recordatorio |
| 13 | **Red social de proyectos del centro** | Perfiles de alumnado, proyectos publicados, comentarios y reacciones (una versión más completa de esta web). | Laravel, MySQL, API REST, autenticación, subida de imágenes | Registro, publicar un proyecto con imagen, comentar y reaccionar |
| 14 | **Quiz en directo para clase** | Preguntas que el profesor lanza y el alumnado responde desde el móvil, con ranking al final. | PHP/Laravel, MySQL, API REST, JS en tiempo real | Una partida completa con cinco preguntas, diez participantes y ranking |
| 15 | **Gastos compartidos** | App web para repartir gastos de un grupo (viaje de fin de curso, piso): quién debe a quién, PWA instalable. | Laravel o PHP, MySQL, API REST, PWA | Grupo con gastos de varias personas y el cálculo correcto de las deudas |
| 16 | **Bolsa de empleo y antiguos alumnos** | Portal donde empresas publican ofertas y antiguos alumnos del centro se apuntan y mantienen su perfil. | Laravel, MySQL, roles, API REST, SMTP | Empresa publica, antiguo alumno se apunta, el centro modera |
| 17 | **Biblioteca del centro** | Catálogo de libros con búsqueda, préstamos, reservas y avisos de devolución. | Laravel, MySQL, API REST, lectura de ISBN/QR | Buscar un libro, reservarlo, registrar el préstamo y el aviso de devolución |
| 18 | **Panel de control de un servidor** | Web para ver el estado de un servidor Linux (CPU, disco, servicios, logs) y reiniciar servicios con permisos. | Python o PHP para la API, bash, Nginx, autenticación | Ver métricas reales del servidor del aula y reiniciar un servicio desde la web |
| 19 | **Tema o plugin WordPress a medida** | Para una asociación real: tema propio o plugin (eventos, socios, inscripciones) y despliegue. | WordPress, PHP, MySQL, Apache/Nginx, despliegue | Plugin instalado en un WordPress real con una funcionalidad completa usada por el cliente |
| 20 | **Rutas de montaña con mapa** | Catálogo de rutas con mapa, tracks GPX, dificultad, fotos y comentarios. | PHP/Laravel, MySQL, Leaflet (JS), subida de ficheros | Subir una ruta con su GPX y verla dibujada en el mapa con sus datos |
