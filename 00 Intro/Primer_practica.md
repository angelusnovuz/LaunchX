# **LaunchX-Primera practica**

![1646108129210.png](image/Primer_practica/1646108129210.png)

## **Overview**

Cuando se enfrentan a un problema, quieren resolver este problema, pero no saben a quién preguntar y se sienten confundidos, quieren leer artículos de acuerdo con su nivel, quieren un profesional que pueda orientarlos y guiarlos en lo que pueden hacer. La gente exige servicios de forma inmediata y con los mejores estándares de calidad. En el ámbito legal no solo es difícil encontrar asesores y representantes de confianza, sino también gestionar el tiempo para una reunión con un abogado cuando es necesario. Debido al alto coste y a la falta de conocimiento evitan acudir a una asesoría.

## **Planteamiento del Problema**

Descripción: Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a través de una página web llenando un formulario. Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción. Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal. El administrador del sitio recibe la notificación de una nueva demanda y con los datos llenados del formulario se crea automáticamente el documento legal en formato word para empezar el proceso. El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos. El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso. Al usuario le llegan correos de notificación para saber el avance de su proceso. La página debe de ser responsive para poderla ver desde el celular. La preferencia de colores del cliente es azul marino y blanco, pero acepta propuestas.

## **Posible solución**

Una solución digital que reúna todos los servicios y productos para el cuidado de las mascotas en una sola plataforma. Una aplicación que permite reservar rápida y fácilmente de cuidadores de mascotas y paseadores de perros, consulta veterinaria en línea, junto con una sección de comercio electrónico dedicada a los productos de cuidado de mascotas. de productos para el cuidado de mascotas.

Desenhista no es sólo un medio social para diseñadores o profesionales de las disciplinas creativas, que es un lugar democrático para compartir conocimientos. Sube un proyecto y otros diseñadores le dan feedback. Amentor le ayuda con las cosas que le resultan difíciles. Preguntas y respuestas para ayudar a los diseñadores.

La solución
•	Presentación de una plataforma de alquiler de muebles, electrodomésticos y productos electrónicos.
•	El usuario puede elegir el periodo de alquiler que desee (una semana, un mes o un año).
•	Puede reubicar fácilmente los artículos alquilados desde nuestra aplicación de forma gratuita.
•	Puede cambiar el artículo alquilado para actualizarlo.
•	No se aplicarán gastos de envío para los artículos alquilados.
•	Fácil limpieza y mantenimiento.

# **Proceso de Diseño**

La estrategia de diseño es el marco inicial de un proyecto que aclara ¿qué diseñar? y ¿por qué? antes de abordar cómo diseñarlo. Es la visión de una solución que debe validarse con clientes potenciales reales para demostrar que es deseada en el mercado. Comencé mi proyecto con un enfoque centrado en el usuario, abordando la experiencia del usuario en su totalidad.

![1646106451375.png](img/Proceso de diseño.jpg)

## Bosquejo de la app:

### Usuario

El usuario debe loguearse para llegar al home, en caso de no tener cuenta debe crear una.
En el Home tendrán dos opciones. Crear una solicitud nueva o ver el estado de su solicitud.
Crear una nueva solicitud de demanda: debe llenar un formulario con los datos pertinentes a la demanda, luego un formulario de pago por el recibimiento de la demanda.
Ver demandas: el usuario podrá ver el estado de su demanda de acuerdo a las actualizaciones del proceso y los comentarios que el abogado va ingresando a medida que el proceso avance.
Modificar sus datos de perfil y contraseña.

### Administrador (Abogado)

El administrador debe loguearse con la cuenta que les fue asignada
Ver solicitudes nuevas de demanda
Ingresar actualización en demandas anteriores: Selecciona demandas anteriores, luego en la lista selecciona la demanda a actualizar, luego un formulario para ingresar una actualización del proceso y los comentarios del mismo también puede solicitar un pago adicional para que el proceso continúe a la siguiente fase.
Ver pagos recibidos.

## Requerimientos:

1. Sistema de sign in y sign up
2. Formulario de nueva solicitud de consulta legal
3. Formulario o pasarela de pago
4. Visualización de actualizaciones en el proceso de la demanda
5. Sign up para administradores
6. Dashboard mostrando los pagos recibidos, las nuevas consultas solicitadas y en proceso
7. Pantalla para hacer modificaciones, agregar comentarios y solicitar nuevos pagos de las demandas en proceso
8. Crear documento legal en .docx automáticamente

## **Fase de Definición**

### Buyer Persona

Un buyer persona es una representación semi-ficticia de tu cliente ideal, elaborada a partir de estudios de mercado y datos reales sobre tus clientes existentes. Los buyer personas proporcionan estructura y contexto a tu empresa. Esto hace que sea más fácil diseñar el contenido, asignar el tiempo y los recursos del equipo y lograr una alineación en toda la organización. Si tienes información sobre el cliente ideal (desafíos, objetivos, datos demográficos, etc.), puedes implementar una estrategia para atraer a los mejores visitantes, leads y clientes para tu empresa.

Santiago Mendoza, Edad 30, Dueño de la concesionaria Mendoza Motors. Santiago es una persona muy activa. Es el primero en llegar a su trabajo y el último en irse. Estudió Contabilidad en la universidad porque siempre tuvo facilidad con las matemáticas y quería manejar las finanzas del negocio de su padre. Al graduarse empezó a trabajar tiempo completo en el negocio de su padre haciendo de esta una de las más exitosas del estado. Al pasar de los años compró la empresa a su padre, convirtiéndose en el único dueño. Tiene un grupo pequeño de amigos con los que les gusta salir a divertirse, pero rara vez encuentra tiempo para hacerlo. No tiene esposa aún, pero planea tenerla en los próximos años.

**Personalidad:** Es una persona muy positiva y alegre. Le gusta tomar el liderazgo y tomar las decisiones. Disfruta de la compañía de sus amigos.

**Metas:** Sueña con convertir a su concesionaria en la primera del estado. Fundar franquicias en todo el país. Invertir en nuevos emprendimientos. Tener una familia.

**Frustraciones:** Que tenga que hacer todo por sí mismo por incompetencia de sus empleados. Tener que lidiar con cuestiones legales. No tener suficiente tiempo para otras actividades. Que ya tiene treinta años y aún no se ha casado.

**Necesidades:** Más tiempo para otras actividades fuera del trabajo. Necesita personas calificadas a su alrededor. Requiere de una familia para sentirse completo.

### Público Objetivo

Tu público objetivo es tu grupo de clientes potenciales. Es el conjunto de personas que podría estar interesada en tu producto o servicio. Encontrar tu público objetivo es un paso fundamental para el marketing eficaz, el desarrollo de productos y la estrategia de negocios general. Los análisis de público objetivo consisten en describir a tu audiencia en términos de una variedad de parámetros demográficos, como la edad y el género, y de otras variables como ingresos, educación y ubicación o psicográficas como intereses y opiniones. Analizar el público objetivo te ofrece información valiosa para la mayoría de las funciones de negocios.
https://miro.com/app/board/uXjVOJnscFs=/?invite_link_id=292050268838

![1646107762216.png](image/Primer_practica/1646107762216.png)

### Perfil Geográfico:

- Que vivan en Tabasco o Chiapas.
- Que hablen español.
- Habitantes urbanos.

### Perfil Demográfico:

- Personas entre 28 y 50 años.
- Con ingresos de 8000 pesos en adelante.
- Sin distinción de género.
- Con título universitario.
- Trabajan en finanzas o negocios.
- Tienen vivienda propia.

### Perfil Psicográfico:

- Que tengan un estilo de vida ocupado.
- Valoran el tiempo y no les gusta esperar.
- Han tenido problemas legales anteriormente.
- No están conformes con el manejo de sus asuntos legales actualmente.

### Perfil de comportamiento:

- Personas activas y trabajadoras.
- Son abiertos a las nuevas tecnologías.
- Buscan la rapidez en los servicios.
- Les gusta lo moderno.
- Son activos en las redes sociales.
- Les gusta el orden y quieren estar en control en todos los aspectos de su vida.

## **Fase de Idea**

### User Flow

Creamos un flujo utilizando Miro para ilustrar cómo el usuario navegará por la aplicación.
https://miro.com/app/board/uXjVOKNZg6o=/?invite_link_id=617942212274

![1646107363363.png](image/Primer_practica/1646107363363.png)

### Clasificación de tarjetas

La clasificación por tarjetas es una técnica que consiste en pedir a los usuarios que organicen la información en grupos lógicos. Tras conocer los requisitos del usuario la clasificación por tarjetas se realiza para tener una idea de qué tipo de características y flujos ayudarían al usuario a alcanzar sus objetivos que ayudarán a organizar la arquitectura de la información.

![1646107469478.png](image/Primer_practica/1646107469478.png)

### Arquitectura de la información

La arquitectura de la información es una representación visual para los usuarios, de modo que éstos puedan conocer las características y la funcionalidad del producto y puedan encontrar cualquier cosa fácilmente.

![1646107352772.png](image/Primer_practica/1646107352772.png)

## **Fase de Diseño**

### Low Fidelity Wireframes

### High Fidelity Wireframes

### Mockups

https://www.figma.com/file/03buVInBwyNQoMYHrHE63o/Wireframes?node-id=0%3A1 

![1646114854144.png](image/Primer_practica/1646114854144.png)

![1646114832112.png](image/Primer_practica/1646114832112.png)

![1646114875198.png](image/Primer_practica/1646114875198.png)

![1646114889127.png](image/Primer_practica/1646114889127.png)

![1646114907316.png](image/Primer_practica/1646114907316.png)
