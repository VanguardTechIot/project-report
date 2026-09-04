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


