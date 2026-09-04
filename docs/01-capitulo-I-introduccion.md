# Capítulo I: Introducción

En esta sección, se presenta la visión general sobre el origen de VanguardTech, los desafíos que impulsaron su creación y la propuesta de valor que ofrecemos al sector de bienes raíces comerciales. Además, se detalla la misión, visión y el perfil profesional del equipo detrás de esta innovación tecnológica.

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

VanguardTech es una startup de base tecnológica enfocada en resolver una problemática crítica y desatendida en el sector comercial urbano: la vulnerabilidad física de los locales y la gestión ineficiente de los servicios básicos en galerías comerciales. Observamos que la administración tradicional de estos recintos depende de inspecciones manuales esporádicas y cobros estimados que generan conflictos constantes entre dueños e inquilinos.

Ante este escenario, VanguardTech desarrolla StorePulse, una solución de software basada en una arquitectura empresarial IoT. Esta plataforma integral articula prototipos físicos de dispositivos IoT (con sensores y medidores controlados por Embedded Applications), procesamiento en el borde (Edge Computing) y una RESTful API centralizada en la nube. Para la interacción, ofrecemos Web y Mobile Applications adaptativas que visualizan información cuantitativa, además de una Landing Page promocional.

De esta manera, facilitamos el acceso a infraestructuras tecnológicas robustas mediante herramientas open-source, permitiendo a administradores e inquilinos gestionar su patrimonio de forma remota, segura y transparente.

**Misión:**

Nuestra misión es proveer a los administradores e inquilinos de galerías comerciales un ecosistema de software y hardware IoT accesible que automatice la seguridad perimetral y transparente el consumo de servicios básicos. Buscamos erradicar la incertidumbre operativa y económica mediante el cálculo y visualización de datos cuantitativos en tiempo real, fomentando un entorno de trabajo seguro y una convivencia comercial justa.

**Visión:**

Consolidarnos en los próximos cinco años como la startup líder en la transformación digital del sector comercial a nivel nacional, demostrando un modelo de negocio altamente escalable y con potencial de crecimiento exponencial. Aspiramos a establecer un nuevo estándar operativo donde la integración de Edge y Cloud Computing en galerías tradicionales sea la norma, transformando espacios vulnerables en ecosistemas comerciales seguros, inteligentes y autogestionados. 

### 1.1.2. Perfiles de integrantes del equipo

| Foto | Nombres y Apellidos | Código | Carrera | Conocimientos y aporte al equipo |
| :---: | :--- | :---: | :--- | :--- |
| ![Renzo Araujo](../assets/team/renzo-araujo.png) | Renzo José Araujo Ingunza | U202113612 | Ingeniería de Software | |
| ![Sebastián Córdova](../assets/team/sebas-cordova.jpeg) | Sebastián Córdova Valdivia | U202111041 | Ingeniería de Software | Estudiante de Ingeniería de Software con interés en el desarrollo full-stack y el análisis de información. Busca especializarse en ciberseguridad, en las áreas de Pentesting y SOC, con el objetivo de diseñar sistemas eficientes y seguros. |
| ![Angelo Curi](../assets/team/angelo-curi.png) | Angelo Marcio Curi Marcelo | U202022387 | Ingeniería de Software | |
| ![Miguel Esquirva](../assets/team/miguel-esquirva.png) | Miguel Juan Diego Esquirva León | U202310837 | Ingeniería de Software | |
| ![Henry Diaz](../assets/team/henry-diaz.png) | Henry Kevin Diaz Gutierrez | U201819674 | Ingeniería de Software | |
| ![Adrian Quiroz](../assets/team/adrian-quiroz.png) | Adrian Quiroz Caceres | U202214864 | Ingeniería de Software | |
| ![Joaquín Carranza](../assets/team/joaquin-carranza.png) | Joaquín Enrique Carranza Tesén | U20191B935 | Ingeniería de Software | |

## 1.2. Solution Profile

En esta sección se presentan los antecedentes y la problemática que sustentan la propuesta de StorePulse, así como el proceso de Lean UX mediante el cual el equipo transformó dicha problemática en un conjunto de creencias explícitas y verificables sobre el negocio, los usuarios y las funcionalidades del producto.

### 1.2.1. Antecedentes y problemática

**Técnica de las 5 'W's y 2 'H's**

* **Who (Quién):**

  **Usuarios principales:**

    - **Administrador de galería:** responsable de la rentabilidad, el mantenimiento y la seguridad de las áreas comunes del inmueble, así como del cobro de los      gastos comunes a los inquilinos. Su problema es que la supervisión depende de recorridos presenciales que no cubren todos los locales ni todo el horario, y que no dispone de evidencia para sustentar los importes que factura.

    - **Inquilino del local:** comerciante que alquila un espacio dentro de la galería y cuyo capital de trabajo está invertido en la mercadería almacenada. Su problema es que se entera de una intrusión al abrir su local al día siguiente, y que no puede verificar si el importe de servicios que se le imputa corresponde a su consumo real.

    - **Afectados indirectos:** trabajadores del local, clientes visitantes y comercios colindantes, dado que un siniestro dentro de un local se propaga al resto del inmueble.

* **What (Qué):**

    - **El desafío:** las galerías comerciales operan sin información medida sobre lo que ocurre dentro de sus instalaciones. La intrusión se descubre horas después, el humo se advierte cuando el fuego ya se propagó y el consumo de servicios se factura mediante prorrateos estimados que nadie puede comprobar. Los tres problemas se atienden hoy por separado y de forma reactiva, con herramientas concebidas para un comercio autónomo y no para un inmueble de propiedad compartida.

* **Where (Dónde):**

    - **Entorno físico:** galerías comerciales sujetas al régimen de propiedad exclusiva y propiedad común, donde decenas de locales independientes comparten una misma edificación, una acometida única de energía y agua, pasillos comunes y con frecuencia un solo vigilante para todo el inmueble.

    - **Mercado objetivo:** conglomerados comerciales de alta densidad de locales en Lima Metropolitana, iniciando en Gamarra (La Victoria), Mesa Redonda, Las Malvinas y el jirón Wilson (Cercado de Lima), con proyección hacia galerías de otras regiones del país.

* **When (Cuándo):**

    - **Ciclo de uso:** el inquilino consulta el estado de su local a diario, al abrir y al cerrar. El administrador revisa la información del inmueble de forma semanal y en cada ciclo mensual de facturación de servicios.

    - **Eventos críticos:** las intrusiones se concentran en el horario de cierre, la noche y la madrugada. Los incendios no siguen un patrón horario, pero su gravedad depende del tiempo transcurrido hasta la detección. Los tres problemas se agravan durante las campañas comerciales de julio y diciembre, cuando el volumen de mercadería almacenada alcanza su punto máximo.

* **Why (Por qué):**

    - **Causa raíz:** la gestión de la galería descansa en la inspección humana presencial y en el registro manual, mientras que la infraestructura de servicios fue construida con acometidas compartidas sin medición por unidad. No existe ningún punto del proceso donde se genere un dato verificable.

    - **Desencadenante:** el incremento sostenido de la delincuencia contra los pequeños comercios y la persistencia de siniestros en galerías han elevado el riesgo, mientras que la oferta de seguridad electrónica disponible mantiene costos y contratos concebidos para el local individual, fuera del alcance del microempresario promedio.

* **How (Cómo):**

    - **Condiciones actuales:** la galería contrata uno o dos vigilantes para todo el edificio e instala, en algunos casos, cámaras cuyas grabaciones se revisan únicamente después del incidente. La prevención de incendios se limita a extintores e inspecciones municipales. La facturación de servicios se calcula en una hoja de cálculo y los desacuerdos se resuelven por negociación directa.

    - **Preferencias del usuario:** ninguno de los dos segmentos posee formación técnica, por lo que buscan una solución que no exija configuración ni interpretación de datos especializados, y que se integre a su rutina sin interrumpirla.

* **How Much (Cuánto):**

    - **Cuantificación del daño:** los pequeños comercios de Lima registran pérdidas superiores a **S/ 450 000 diarios** por efecto de la delincuencia, con importes de entre **S/ 3 000 y S/ 7 000** por negocio afectado en casos de cobro de cupos. El **65 %** de las incidencias reportadas en establecimientos comerciales corresponde a intentos de robo. En materia de incendios, un solo siniestro compromete simultáneamente la totalidad de los locales del inmueble.

    - **Brecha de adopción:** la penetración de videovigilancia monitoreada en negocios se mantiene en torno al **15 %**, muy por debajo de la magnitud del riesgo declarado por los propios comerciantes.

<div class="page"></div>

El análisis bajo la técnica de las 5 'W's y 2 'H's revela que el problema no es la ausencia de tecnología en el mercado, sino que la disponible fue diseñada para un comercio autónomo y no para un edificio donde decenas de negocios independientes comparten infraestructura, riesgos y facturación.

La magnitud del fenómeno delictivo sustenta este diagnóstico. Según **Gestión (2025)**, seis de cada diez pequeños comerciantes identifican la inseguridad como el mayor desafío de su distrito, por encima de la situación económica o política. El Sexto Reporte del Observatorio del Crimen y la Violencia, citado por **Gestión (2026)**, estima el costo de la inseguridad para el país en US$ 11 800 millones anuales y registra que el 59 % de los limeños conoce negocios cerrados o restringidos por la delincuencia, frente al 50 % del año previo. Las galerías figuran entre los cinco tipos de negocio más vulnerables, mientras que la adopción de videovigilancia monitoreada apenas bordea el 15 % (**El Comercio, 2024a**).

A ello se suma un riesgo de alcance colectivo que el formato amplifica. En mayo de 2024 un incendio consumió la galería Los Portales, en el jirón Andahuaylas, y se propagó a los locales colindantes; una de las galerías afectadas no contaba con licencia de funcionamiento (**El Comercio, 2024b**). El Cuerpo General de Bomberos Voluntarios del Perú advirtió entonces que la mercadería apilada hasta el techo obstaculiza las labores de extinción (**Infobae, 2024**), de modo que el factor determinante es el tiempo de detección. El tercer eje, la opacidad en el cobro de servicios, carece de mediciones publicadas para el caso peruano, por lo que su cuantificación forma parte de los objetivos de las entrevistas del Capítulo II. El universo afectado es considerable: solo en el Emporio Comercial de Gamarra el **INEI (2018)** registró 39 630 establecimientos con 80 183 trabajadores, donde el 99,6 % son micro y pequeñas empresas.

**Enunciado del problema**

Los administradores de galerías comerciales de Lima Metropolitana y los inquilinos que ocupan sus locales operan sin información medida sobre lo que ocurre dentro del inmueble. La seguridad depende de vigilancia presencial que no cubre la totalidad de los locales ni del horario; el incendio se detecta cuando ya se propagó, en edificaciones donde la contigüidad y la densidad de material inflamable multiplican las consecuencias; y los servicios se facturan mediante prorrateos que ninguna de las partes puede sustentar. El resultado es una operación reactiva, con pérdidas patrimoniales evitables, exposición a siniestros de alcance colectivo y una relación comercial erosionada por cobros no verificables.


**Aspectos que debe resolver la solución**

StorePulse debe atender los siguientes aspectos, ordenados por su contribución al problema descrito.

1. Detectar y notificar la intrusión en un local en el momento en que ocurre, mediante sensores de movimiento y activación por proximidad, con registro visual asociado al evento.

2. Detectar la presencia de humo en fase temprana y escalar la alerta de forma simultánea al inquilino del local afectado y al administrador de la galería.

3. Medir el consumo individual de servicios por local y ponerlo a disposición de ambas partes con el mismo nivel de detalle, de modo que la facturación deje de basarse en estimaciones.

4. Procesar los datos recolectados para producir información cuantitativa derivada, como el consumo acumulado por periodo, el promedio histórico por local y la detección de desviaciones respecto de la línea base, y presentarla mediante visualizaciones comprensibles para usuarios sin formación técnica.

5. Diferenciar el alcance de la información según el rol: el administrador accede a la vista consolidada del inmueble y el inquilino únicamente a la de su propio local.

6. Garantizar la operación de la detección y el registro local aun cuando la conectividad con la nube se interrumpa, mediante procesamiento en el borde.

**Objetivos**

*Objetivo general:* desarrollar una solución de software basada en IoT que permita a administradores e inquilinos de galerías comerciales de Lima Metropolitana supervisar de forma remota la seguridad perimetral, el riesgo de incendio y el consumo de servicios de sus locales, sustituyendo la inspección manual y el cobro estimado por información medida y verificable.

*Objetivos específicos:*

- Implementar una aplicación embebida sobre un prototipo físico de dispositivo IoT con sensores de movimiento, proximidad, humo y medición de consumo.
- Desarrollar un Edge API de elaboración interna que reciba, valide y almacene localmente la telemetría, y la transmita al servicio en la nube.
- Desarrollar un RESTful API de elaboración interna que consolide la información de todos los locales, gestione la identidad y el control de acceso por rol, y exponga los cálculos estadísticos sobre el consumo histórico.
- Construir aplicaciones web y móvil integradas con el RESTful API, con alertas y visualización de información cuantitativa en una interfaz adaptable.
- Publicar un sitio web estático de Landing Page que presente el modelo de negocio a ambos segmentos y los dirija al punto de acceso correspondiente.
- Validar la propuesta con representantes de ambos segmentos mediante entrevistas y evaluación según heurísticas.

**Restricciones**

- *Alcance funcional:* la solución cubre detección, notificación, medición y visualización. No incluye respuesta física ante un evento ni sistemas de extinción de incendios.
- *Alcance del dispositivo:* el componente de hardware se entrega como prototipo físico con un subconjunto relevante de características, orientado a demostrar el flujo de datos de extremo a extremo.
- *Alcance geográfico:* la investigación y la validación se circunscriben a galerías comerciales de Lima Metropolitana.
- *Alcance temporal:* el desarrollo se ejecuta dentro del ciclo académico 2026-20, organizado en tres Sprints.
- *Restricciones tecnológicas:* la construcción se ciñe al conjunto de tecnologías y herramientas establecido para el curso, con predominio de soluciones open-source.
- *Restricciones normativas y éticas:* el tratamiento de los datos recolectados, en particular el registro visual asociado a eventos de seguridad, se sujeta a los términos y condiciones del servicio.

<div class="page"></div>

### 1.2.2. Lean UX Process

En esta sección se detalla el proceso de trabajo aplicado por el equipo para StorePulse. Mediante un enfoque ágil y colaborativo, las creencias iniciales del equipo sobre el negocio y sus usuarios se declararon de forma explícita y se convirtieron en hipótesis verificables. Este proceso permite alinear los resultados esperados del negocio con las necesidades del administrador de galería y del inquilino de local, garantizando que las funcionalidades propuestas respondan a un beneficio identificado y no a una suposición no examinada.

#### 1.2.2.1. Lean UX Problem Statements

Se elabora un único Problem Statement para todo el proyecto, considerando ambos segmentos objetivo, según la plantilla *Brand new initiative*.

El estado actual de **la gestión operativa de galerías comerciales en Lima Metropolitana** se ha enfocado principalmente en **la vigilancia presencial de áreas comunes, la inspección manual periódica y el prorrateo estimado de los servicios básicos, atendiendo a administradores e inquilinos únicamente después de que un incidente ha ocurrido**.

Lo que los productos y servicios existentes no logran atender es **la ausencia de medición individual por local: las soluciones de seguridad electrónica se ofrecen como suscripciones concebidas para un comercio autónomo, con costos y contratos que no se ajustan al formato de galería, y ninguna integra en un mismo lugar la detección de intrusión, la detección temprana de humo y el consumo verificable de servicios**.

Nuestro producto atenderá esta brecha mediante **una plataforma IoT que instala dispositivos de bajo costo en cada local, procesa la telemetría en el borde para operar aun sin conectividad, y expone la información en aplicaciones web y móvil con alcance diferenciado según el rol del usuario**.

Nuestro enfoque inicial será **los administradores e inquilinos de galerías comerciales de alta densidad de locales en Lima Metropolitana, específicamente en Gamarra, Mesa Redonda, Las Malvinas y el jirón Wilson**.

Sabremos que hemos tenido éxito cuando observemos que **los administradores sustituyen la inspección manual por la revisión del tablero de control, los inquilinos consultan el consumo de su local antes de cuestionar la facturación, y ambos actúan sobre una alerta durante el evento y no después de él**.

#### 1.2.2.2. Lean UX Assumptions

En esta sección el equipo declara de forma explícita las creencias que sostienen la propuesta de StorePulse, organizadas en las cinco categorías del proceso Lean UX. Cada enunciado corresponde a una creencia resultante de la discusión del equipo y no a una pregunta de exploración. Los Feature Assumptions constituyen la base sobre la cual se formulan los Hypothesis Statements de la sección siguiente.

**1. Business Assumptions**

- Creemos que existe un mercado sostenible en las galerías comerciales de Lima Metropolitana, dado el volumen de locales agrupados por inmueble y la baja penetración de soluciones de monitoreo.
- Creemos que el administrador de la galería es quien toma la decisión de compra y asume el costo de la suscripción, mientras que el inquilino es el usuario beneficiario.
- Creemos que un modelo de suscripción mensual escalonado por número de locales monitoreados se ajusta a la capacidad de pago de una administración de galería.
- Creemos que la venta por inmueble completo, y no por local individual, reduce el costo de adquisición y hace escalable el crecimiento del negocio.
- Creemos que ningún competidor local ofrece hoy la detección de intrusión, la detección de humo y la medición de consumo integradas en una misma plataforma para el formato de galería.
- Creemos que el uso de tecnologías open-source mantiene el costo de operación por debajo del precio de las alternativas de monitoreo disponibles en el mercado.


**2. Business Outcome Assumptions**

- Creemos que las disputas por cobros de servicios entre administradores e inquilinos se reducirán en un 30 % durante los primeros seis meses de uso de la plataforma.
- Creemos que el tiempo de resolución de un reclamo por facturación se reducirá en un 50 %, al disponer ambas partes del mismo registro de consumo.
- Creemos que la tasa de rotación de inquilinos en las galerías suscritas se reducirá en un 15 % anual, al disminuir las pérdidas por robo y los conflictos por cobros.
- Creemos que el 70 % de los inquilinos con un local monitoreado usará la aplicación móvil al menos una vez por semana.
- Creemos que el 30 % de las galerías que reciban una demostración del producto contratará una suscripción activa.
- Creemos que la retención de suscripciones tras el tercer mes superará el 70 %.

**3. User Assumptions**

- Creemos que el administrador de galería es un adulto entre 35 y 60 años, encargado de la infraestructura general del inmueble, que gestiona las operaciones desde una oficina y prefiere una vista consolidada en computadora.
- Creemos que el inquilino de local es un microempresario entre 25 y 55 años cuyo capital de trabajo está invertido en la mercadería almacenada y que opera principalmente desde su teléfono móvil mientras atiende proveedores y clientes.
- Creemos que ambos segmentos poseen un teléfono inteligente con acceso a internet móvil, dado que la penetración de este dispositivo en Lima Metropolitana alcanza el 99,2 % (OSIPTEL, 2025).
- Creemos que ninguno de los dos segmentos posee formación técnica, por lo que la información debe presentarse sin terminología especializada ni exigir configuración.
- Creemos que el inquilino desconfía de que el administrador acceda a información sobre la actividad interna de su local, por lo que el alcance de los datos debe estar delimitado por rol de forma explícita.
- Creemos que el administrador es quien autoriza la instalación del hardware en el inmueble, por lo que la adopción del inquilino depende de una decisión previa que no controla.

**4. User Outcome and Benefit Assumptions**

- Creemos que el administrador desea reducir las horas de trabajo manual que dedica a recorrer el inmueble y a elaborar los recibos de servicios.
- Creemos que el administrador desea sustentar el cobro de servicios con evidencia verificable, para reducir el estrés de la gestión operativa y las fricciones con sus inquilinos.
- Creemos que el inquilino desea enterarse de una intrusión en su local mientras ocurre y  no al abrir al día siguiente.
- Creemos que el inquilino desea comprobar que el importe de servicios que se le imputa corresponde únicamente a lo que efectivamente consumió.
- Creemos que ambos desean ser advertidos de la presencia de humo con antelación suficiente para actuar antes de que el fuego alcance los locales contiguos.
- Creemos que ambos valoran la tranquilidad de contar con vigilancia permanente sobre el inmueble por encima de la sofisticación de las funcionalidades ofrecidas.

**5. Feature Assumptions**

- Creemos que la detección de intrusión mediante sensores de movimiento y activación por proximidad, con notificación inmediata y captura de imagen asociada al evento, permitirá al inquilino reaccionar durante el evento y distinguir una alerta real de una falsa sin trasladarse al local.
- Creemos que la detección de humo con escalamiento simultáneo al inquilino y al administrador reducirá el tiempo entre el inicio del fuego y la respuesta.
- Creemos que los medidores inteligentes de energía y agua instalados por local sustituirán el prorrateo estimado por una facturación verificable por ambas partes.
- Creemos que un tablero de control web con visualización de consumo acumulado, promedio histórico y desviación respecto de la línea base permitirá a ambos segmentos interpretar la información sin formación técnica.
- Creemos que el control de acceso por rol, que limita al inquilino a su propio local y otorga al administrador la vista consolidada del inmueble, es condición para que el inquilino acepte el uso de la plataforma.
- Creemos que una aplicación móvil nativa con notificaciones push de emergencias en tiempo real permitirá al inquilino supervisar su local mientras se desplaza.
- Creemos que el procesamiento y almacenamiento local en el Edge API mantendrá la detección y el registro operativos aun cuando se interrumpa la conectividad con la nube.
- Creemos que un Landing Page estático con contenido y llamadas a la acción diferenciados por segmento comunicará la propuesta de valor y conducirá al visitante al punto de acceso correspondiente.


---

#### 1.2.2.3. Lean UX Hypothesis Statements

*Hypothesis 1 — Detección de intrusión con registro visual*

* Creemos que lograremos **reducir en un 15 % la tasa de rotación de inquilinos** si **los inquilinos de local** alcanzan **la capacidad de reaccionar ante una intrusión mientras ocurre y de distinguir una alerta real de una falsa sin trasladarse al inmueble** con **la detección por sensores de movimiento y proximidad, con notificación inmediata y captura de imagen asociada al evento**.

*Hypothesis 2 — Detección temprana de humo*

* Creemos que lograremos **una conversión del 30 % de las galerías que reciben una demostración hacia una suscripción activa** si **los administradores de galería** alcanzan **la advertencia de humo con antelación suficiente para actuar antes de que el fuego alcance los locales contiguos** con **el sensor de humo y el escalamiento simultáneo de la alerta al inquilino y al administrador**.

*Hypothesis 3 — Medición individual de consumo*

* Creemos que lograremos **reducir en un 30 % las disputas por cobros de servicios** si **los administradores de galería y los inquilinos de local** alcanzan **una facturación sustentada en consumo real y no en estimaciones** con **los medidores inteligentes de energía y agua instalados por local**.

*Hypothesis 4 — Tablero de control y visualización cuantitativa*

* Creemos que lograremos **reducir en un 50 % el tiempo de resolución de reclamos por facturación** si **los administradores de galería y los inquilinos de local** alcanzan **la comprensión de su consumo y de sus desviaciones sin formación técnica** con **la visualización de consumo acumulado, promedio histórico y desviación respecto de la línea base en el tablero de control**.

*Hypothesis 5 — Control de acceso por rol*

* Creemos que lograremos **una retención de suscripciones superior al 70 % tras el tercer mes** si **los inquilinos de local** alcanzan **la certeza de que el administrador no accede a la actividad interna de su local** con **el control de acceso por rol que delimita el alcance de la información para cada perfil**.

*Hypothesis 6 — Aplicación móvil con notificaciones push*

* Creemos que lograremos **que el 70 % de los inquilinos use la aplicación al menos una vez por semana** si **los inquilinos de local** alcanzan **la posibilidad de supervisar su local mientras se desplazan atendiendo proveedores y clientes** con **la aplicación móvil nativa y las notificaciones push de emergencias en tiempo real**.

*Hypothesis 7 — Procesamiento en el borde*

* Creemos que lograremos **una retención de suscripciones superior al 70 % tras el tercer mes** si **los administradores de galería y los inquilinos de local** alcanzan **la certeza de que la detección y el registro continúan operando ante una caída de conexión** con **el procesamiento y almacenamiento local en el Edge API**.

*Hypothesis 8 — Landing Page diferenciado por segmento*

* Creemos que lograremos **una conversión del 30 % de las galerías que reciben una demostración hacia una suscripción activa** si **los administradores de galería** alcanzan **la comprensión de la propuesta de valor aplicada a su formato de negocio** con **el Landing Page de contenido y llamadas a la acción diferenciados por segmento**.

---

#### 1.2.2.4. Lean UX Canvas

A continuación, mostraremos el análisis de los procesos iterativos y descubrimientos realizados por los miembros del equipo VanguardTech para asentar las bases de valor propuesta dentro de la solución; centrándonos en solventar las problemáticas críticas y sobre todo maximizar el beneficio percibido por el cliente.

![Lean-UX-Canvas - VanguardTech](../assets/ux/Lean-UX-Canvas.jpg)

<div class="page"></div>

## 1.3. Segmentos objetivo

En esta sección se presentan los criterios que VanguardTech consideró en la selección de sus segmentos objetivo, de acuerdo con su relevancia en el dominio de la seguridad y la gestión operativa de galerías comerciales. A continuación se describe cada segmento junto con sus características demográficas y la información estadística que justifica su inclusión en el mercado objetivo.

1. **Administrador o propietario de galería comercial**

  * **Descripción:** Este segmento está conformado por los responsables de la rentabilidad, el mantenimiento y la seguridad de las áreas comunes de inmuebles comerciales sujetos al régimen de propiedad exclusiva y propiedad común. Recaudan los gastos comunes de los inquilinos, responden ante la autoridad municipal por las condiciones de seguridad del edificio y autorizan cualquier intervención sobre su infraestructura, por lo que constituyen el decisor de compra de la solución.

  * **Características demográficas:** Este perfil corresponde mayoritariamente a personas entre 35 y 60 años, de ambos géneros, residentes en Lima Metropolitana, con educación superior técnica o universitaria y experiencia previa en administración de propiedades o en el comercio. Gestionan las operaciones desde una oficina dentro del inmueble o de forma remota, utilizan la computadora como interfaz principal apoyándose en hojas de cálculo para el control de cobros, y priorizan la vista consolidada del edificio sobre el detalle de un local individual.

  * **Información estadística:** Las galerías comerciales figuran entre los cinco tipos de negocio más vulnerables al delito identificados por el sector de seguridad privada, mientras que la penetración de servicios de videovigilancia monitoreada en negocios apenas bordea el 15 %, lo que evidencia una brecha amplia entre el nivel de riesgo y la protección efectivamente contratada (El Comercio, 2024). El 59 % de los limeños conoce negocios que han cerrado o restringido sus actividades por causa de la delincuencia, frente al 50 % del año previo (Gestión, 2026), presión que recae directamente sobre la ocupación del inmueble que este segmento administra. No existe registro público que cense a los administradores de galerías del país, por lo que el tamaño del segmento se estima a partir del número de inmuebles: solo en el Emporio Comercial de Gamarra, los 39 630 establecimientos registrados por el Instituto Nacional de Estadística e Informática se distribuyen en galerías concentradas en un perímetro reducido (INEI, 2018).

