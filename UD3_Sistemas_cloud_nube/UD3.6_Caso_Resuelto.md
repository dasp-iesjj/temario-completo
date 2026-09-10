## UD3 · Apartado 6 — 🧩 Caso resuelto

> **[Módulo: Digitalización Aplicada a los Sectores Productivos]** · **Unidad 3 de 5**
> 🧭 Índice del módulo: [[00_Indice_DASP]]
>
> **📍 Cuándo se lee:** después del fundamento y antes de la práctica profesional. Es el modelo de cómo se elige una solución cloud y se justifica.

---

> [!info] 📌 El caso: la nube y la investigación del cáncer
> **Emma** está terminando su residencia de **oncología**. Su unidad trabaja con **equipos de hospitales extranjeros** en un estudio clínico sobre el cáncer.
>
> **Qué quieren hacer:** identificar pacientes que cumplan ciertos criterios y **secuenciar su ADN** para estudiarlo. Los motivos:
> - Secuenciar el genoma de una persona puede **identificar el gen causante** de un cáncer, y con eso decidir **qué fármacos son más eficaces** en ese caso concreto.
> - El cáncer aparece cuando determinadas alteraciones genéticas permiten que algunas células crezcan y se dividan sin el control normal.
> - **Cada equipo por separado tiene muy poca información.** La cura pasa por conocer más del genoma humano, y para eso hay que **trabajar de forma colaborativa**.
>
> A Emma, que además sabe de digitalización, le encargan **investigar qué tecnología usar** y presentar un informe en una videoconferencia el mes siguiente. También tiene que **elegir herramientas** para tres cosas: colaborar y compartir archivos · compartir datos científicos citables en abierto · gestionar tareas del proyecto.
>
> *Caso adaptado de la práctica profesional resuelta del capítulo 3 del libro de referencia.*

> [!tip] Por qué te enseño este caso y no otro
> Porque aquí **la tecnología no es el objetivo: es lo único que hace posible el objetivo**. Sin un sitio común donde poner los genomas, seis equipos en seis países tienen seis estudios pequeños en lugar de uno grande.
>
> Y porque el criterio `CE.03.e` pide *identificar las ventajas de la nube en los sistemas conectados*. Este caso es exactamente eso, pero con algo en juego.

---

## Fase 1 · Qué necesita el proyecto, antes de mirar tecnología

Emma parte de una constatación: **van a trabajar con muchísimos datos y desde sitios distintos**, así que hace falta **un repositorio común**. Los puntos que decide desarrollar en su informe:

1. **Ventajas de la nube** para el estudio, empezando por la más obvia: **compartir datos**.
2. Que la nube sirve también para **otras investigaciones** que necesiten almacenamiento masivo.
3. Las **fases del estudio**.
4. Qué son las **nubes biomédicas** y las **nubes genómicas**.
5. **Por qué cloud y no edge, fog o mist.**
6. **Quién debe gestionar esa nube**: ¿un consorcio hospitalario privado o un proveedor tipo Amazon, Google o Rackspace?
7. **Qué herramientas colaborativas** concretas usar.

> [!important] Fíjate en el punto 5, que es el que se te va a evaluar
> Emma **no da por hecho** que la solución es la nube: **lo argumenta**, y lo argumenta descartando las otras tres. Eso es lo que separa un informe de una recomendación de vendedor.

## Fase 2 · La decisión técnica, con sus razones

> [!success] Por qué **cloud** y no edge, fog ni mist
> Porque es la que mejor se adapta al trabajo que hay que hacer, y porque permite:
> - **colaboración a escala internacional**,
> - **control sobre los datos**,
> - **centralización de la autenticación y la autorización** *(quién entra y qué puede ver)*,
> - **automatización**,
> - y **mayor seguridad**.
>
> **Y el razonamiento de fondo:** aquí no hay ningún problema de latencia. Nadie necesita una respuesta en milisegundos. Lo que hace falta es **muchísimo procesamiento y muchísimo almacenamiento compartido** — que es literalmente la casilla donde la nube gana y el edge pierde.

> [!info] Y una decisión que no es técnica: **de quién es la nube**
> Emma valora que, **por el tamaño de los servidores y el tipo de procesamiento, un proveedor comercial saldría excesivamente caro**. Su propuesta: **gestionarlo de forma privada, con acceso público**.
>
> Es decir: se elige el modelo de despliegue **por coste y por control de datos sensibles**, no por moda. Datos clínicos de pacientes de varios países no son un caso cualquiera.

## Fase 3 · Cómo funcionará el estudio

Las cuatro fases que Emma describe:

| # | Fase |
|---:|---|
| 1 | Elegir los pacientes con cáncer cuyo genoma se va a secuenciar |
| 2 | **Secuenciar** su genoma, analizando **millones de variantes genéticas** |
| 3 | **Análisis bioinformático con técnicas de inteligencia artificial** y selección de las variantes más importantes |
| 4 | **Validación con ensayos funcionales**, para establecer qué variantes son clave para **personalizar diagnósticos y tratamientos** |

> [!example] 📖 Dos términos del caso
> - **Nube biomédica** — plataforma que contiene datos genómicos, historias clínicas, imágenes médicas, etcétera.
> - **Nube genómica** — una nube biomédica que contiene **datos genómicos**. Es decir: toda nube genómica es biomédica, pero no al revés.

## Fase 4 · Las herramientas, y por qué cada una

Todas las que elige son **SaaS**, que es donde vive hoy el software colaborativo:

| Necesidad | Herramientas valoradas | La que elige y por qué |
|---|---|---|
| **Colaborar, comunicarse y compartir archivos** | Slack · Zoom · Google Workspace | **Slack**, para mensajería y trabajo de equipo |
| **Compartir datos científicos en abierto** | Zenodo · Figshare · Labguru | **Zenodo y Figshare**: repositorios de **acceso abierto** que permiten **citar** datos y resultados de investigación |
| **Gestionar tareas y procesos** | Trello · Asana · Jira | **Trello**, por ser flexible, simple y colaborativa |
| *(Analizar y visualizar datos)* | Tableau · Google Analytics · Power BI | — |

> [!tip] 💡 Lo que hay que copiar de esta tabla no son los nombres
> Es el método: **por cada necesidad, tres candidatas y una elegida con su motivo**. En el informe de la práctica profesional se te va a pedir exactamente esta tabla, con las necesidades de otra empresa.
>
> Una tabla con una sola herramienta por fila **no demuestra que hayas elegido**: demuestra que has cogido la primera.

---

> [!success] 🎯 Lo que este caso te enseña a hacer
> 1. **Empezar por lo que necesita el proyecto**, no por el catálogo.
> 2. **Justificar cloud descartando edge, fog y mist** — con el argumento de la latencia y el procesamiento.
> 3. **Elegir el modelo de despliegue por coste y por sensibilidad de los datos.**
> 4. **Proponer herramientas concretas, con alternativas y con motivo.**
>
> Ese es el guion del correo que le vas a escribir a Marta en el apartado 7.

---

| ← Anterior | 🧭 Índice | Siguiente → |
| :--- | :---: | ---: |
| [[UD3.5_Glosario_y_Quizlet]] | [[00_Indice_DASP]] | [[UD3.7_Actividades]] |
