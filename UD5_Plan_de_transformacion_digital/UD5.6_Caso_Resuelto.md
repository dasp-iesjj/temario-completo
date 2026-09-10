## UD5 · Apartado 6 — 🧩 Caso resuelto

> **[Módulo: Digitalización Aplicada a los Sectores Productivos]** · **Unidad 5 de 5**
> 🧭 Índice del módulo: [[00_Indice_DASP]]
>
> **📍 Cuándo se lee:** después del fundamento y antes de escribir tu plan. Es el modelo **del método**: cómo se analiza una empresa y cómo se decide. Los diagramas y el documento final los tienes en [[UD5.3_Fundamento]] y en [[UD5.2_Donde_Estamos]].

---

> [!info] 📌 El caso: el catering El Tenedor
> **Emma** trabaja en la consultora **Trompisoft Ibérica** y tiene que hacer el **plan de transformación digital** de **El Tenedor**, una pequeña empresa de catering.
>
> **Qué hace El Tenedor:** prepara y sirve menús para **comedores colectivos y organismos públicos**.
>
> **Quién manda:** **Antonio**, el gerente. Sabe muchísimo de hostelería, tiene una larga experiencia en restauración y ha llevado otras empresas del sector. Y cree que **la transformación digital es necesaria para sobrevivir**. Por eso llama a la consultora.
>
> *Caso adaptado de la práctica profesional resuelta del capítulo 5 del libro de referencia.*

> [!tip] Por qué este caso y no uno de una multinacional
> Porque es **una pyme de verdad**: cuatro departamentos, un gerente que sabe de su oficio y no de tecnología, y **un chico para todo**.
>
> Y porque el problema que tiene **no lo resuelve ninguna tecnología por sí sola**. Lo resuelve **verlo**.

---

## Fase 1 · Enterarse de cómo funciona la empresa · `CE.05.a`

Emma **no** empieza eligiendo software. Empieza **reuniéndose con Antonio y con otros miembros de la empresa** para conocer su funcionamiento, su estructura y sus recursos.

**Sus dos objetivos en esta fase:** identificar **las etapas** de la compañía y elegir **cuáles son susceptibles de ser digitalizadas** para integrarlas en el mismo sistema.

### 1.1 · Cómo está organizada

| Departamento | Quién y qué |
|---|---|
| **Comedores** | Cocineros y personal de sala |
| **Servicio de dietista** | Hace los menús y otras gestiones |
| **Administración** | Trata con los proveedores y gestiona que los comedores tengan lo que necesitan |
| **Gerencia** | Coordinación. La lleva **Antonio** |
| *(y además)* | **Isaac**, un chico para todo: a veces lleva productos con la furgoneta a los comedores y otras ayuda en administración |

### 1.2 · Cómo trabajan, de verdad

> [!danger] 🛑 Y aquí aparece el problema, que no es informático
> - **Los comedores trabajan de forma independiente**, y cada uno tiene **su pequeño almacén**. Cuando les falta algo para los menús de la semana, **piden a la oficina central que lo compre**.
> - **La oficina central busca el proveedor más económico** y este envía a cada comedor. Pero **la oficina central no sabe qué productos tiene cada comedor**.
> - **La dietista** crea los menús y los distribuye a las cocinas.
>
> **Resultado:** los comedores tiran comida, y los cocineros dicen que es una pena que los compañeros de otro comedor no puedan aprovecharla. Se da la paradoja de que **un comedor está tirando cebollas y otro le ha pedido a la oficina central que se las compre**.

---

## Fase 2 · Qué se puede mejorar · `CE.05.b`

Emma hace una **auditoría previa** y detecta esto:

| # | Lo que ha detectado | Qué implica |
|---:|---|---|
| 1 | Se puede **centralizar la gestión de los almacenes** | Se tira menos producto · se ahorra al no tener tanta mercancía almacenada · **hace falta menos espacio** · los productos están más controlados |
| 2 | El almacén centralizado permite **repartir los excedentes** de un comedor entre los que necesiten esos productos | Es la solución directa al problema de las cebollas |
| 3 | **No se sabe el coste exacto de cada menú**, porque, aunque se conozcan los platos, varía según el número de comensales | Hace falta un **KPI: precio medio del menú** |
| 4 | **No se conoce el grado de aceptación de los platos** | Objetivo: ofrecer los platos **más sanos y baratos y que además gusten** |
| 5 | Falta un **cuadro de mandos** con los KPI y los datos importantes | Y accesible **no solo a Antonio**, sino también a la dietista, los cocineros y administración |

> [!important] Fíjate en el punto 5, que es el que más se olvida
> Emma **no monta el cuadro de mandos solo para el jefe**. Lo abre a quien trabaja con los datos.
>
> Eso es `CE.05.d` en la práctica: **la información conecta las unidades, o no conecta nada**.

---

## Fase 3 · Qué tecnología, y por qué esa · `CE.05.c`

> [!success] La decisión, y es más interesante de lo que parece
> Emma **investiga los ERP del mercado** y concluye que, **al ser un sistema tan específico**, la solución óptima es que su consultora **desarrolle una solución web a medida**.
>
> Es decir: **descarta el producto estándar y lo justifica**. Eso es una decisión de plan, no una preferencia.

**Qué hará ese programa:**

| Función | Quién la usa |
|---|---|
| Gestionar el **almacén centralizado** y permitir **trasvasar productos entre comedores** | **Isaac** se encarga de redistribuirlos físicamente |
| Con esa información, **crear los menús** | La **dietista** |
| **Calcular el precio de cada menú** según el comedor, los comensales y los productos utilizados | El sistema, solo |
| **Actualizar el almacén** con lo consumido y **añadir el feedback de los comensales** — si les gustan o no los platos | **Cocineros y personal de sala** |

> [!tip] 💡 El detalle que convierte un programa en un cambio de negocio
> Con el *feedback* de los comensales, la dietista puede elegir platos **más sanos, más baratos y que gusten más**.
>
> El ejemplo del libro: **si en vez de helado de postre pone fruta de temporada, el precio del menú baja considerablemente y además tiene mejor aceptación.**
>
> Ahí no ha intervenido ninguna tecnología puntera. Ha intervenido **un dato que antes nadie recogía**.

**Y una pieza que no es tecnológica:** Emma propone también **una estrategia de *branding*** —nuevo logo y colores corporativos, personalidad propia— para que la empresa pueda **crecer y ampliar su servicio a otros colectivos**.

---

## Fase 4 · Medir · `CE.05.f`

> [!quote] La frase con la que Emma justifica los indicadores
> *«Lo que no se define no se puede medir. Lo que no se mide, no se puede mejorar. Lo que no se mejora, se degrada siempre.»*

Por eso su sistema **mide**. Los indicadores que salen del propio caso:

| KPI | Por qué |
|---|---|
| **Precio medio del menú** | Es el punto 3 de su auditoría: hoy no se conoce |
| **Aceptación de cada plato** | Punto 4: permite elegir qué repetir |
| **Producto desperdiciado** | Es el problema de las cebollas, ya medido |
| **Existencias por comedor y totales** | Lo que hace posible el trasvase |

---

## Fase 5 · Qué paradigma elige, y la condición que le ponen

> [!important] Un detalle fácil de pasar por alto y que vale nota
> Emma **ha pensado en el sistema por bloques** *(paradigma por componentes)*, **pero** con una condición: *«la empresa debe optimizarse lo suficiente como para empezar a ahorrar costes desde su puesta en marcha»*.
>
> Traducido: **no se puede tardar dos años en ver el primer ahorro**. Una pyme no aguanta eso.
>
> **Elegir paradigma no es elegir el que más te guste: es elegir el que la empresa puede permitirse.** Y eso hay que escribirlo en el plan.

---

> [!success] 🎯 Lo que este caso te enseña a hacer
> 1. **Entrevistar antes de proponer.** Emma se reúne con el gerente **y con otros miembros**, no solo con quien paga.
> 2. **Describir cómo trabajan de verdad**, con sus paradojas — las cebollas no salen en ningún organigrama.
> 3. **Elegir tecnología con criterio**, incluso descartando lo estándar, y decir por qué.
> 4. **Repartir el sistema entre quienes lo van a usar**: cocineros, dietista, Isaac, administración. Cada uno mete o consulta algo.
> 5. **Medir**, y abrir el cuadro de mandos a todos.
> 6. **Ajustar el paradigma a lo que la empresa aguanta.**
>
> Ese es el guion del **análisis** que hay que hacer antes de escribir el plan — los apartados 1, 2 y 3 del tuyo. **Vuelve aquí cada vez que te atasques.**
>
> Lo que este caso **no** te enseña, porque Emma no lo desarrolla, es cómo se dibuja el diagrama del sistema digitalizado ni cómo se redacta el documento final: eso está en el fundamento.

---

| ← Anterior | 🧭 Índice | Siguiente → |
| :--- | :---: | ---: |
| [[UD5.5_Glosario_y_Quizlet]] | [[00_Indice_DASP]] | [[UD5.7_Actividades]] |
