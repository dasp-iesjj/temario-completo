## UD2 · Apartado 6 — 🧩 Caso resuelto

> **[Módulo: Digitalización Aplicada a los Sectores Productivos]** · **Unidad 2 de 5**
> 🧭 Índice del módulo: [[00_Indice_DASP]]
>
> **📍 Cuándo se lee:** después del fundamento y antes de hacer la práctica profesional. Es el modelo de cómo se resuelve un caso de migración a un entorno 4.0.

---

> [!info] 📌 El caso: una empresa familiar que empaqueta pescado
> **Emma y su familia** tienen una pequeña empresa alimentaria que **empaqueta pescado**, que llega congelado directamente del proveedor.
>
> **Su mayor problema es clasificar los trozos.** Llegan productos defectuosos: trozos de piel, espinas negras, incluso restos de las bolsas de plástico en las que se transportó.
>
> La familia acude a **Dimas**, consultor de una multinacional y experto en migración a la industria 4.0, para que diseñe un sistema que resuelva el problema y aumente la productividad.
>
> **Los tres objetivos del encargo:** reducir la presencia de productos defectuosos · disminuir los costes · **tener un control total de la producción**.
>
> *Caso adaptado de la práctica profesional resuelta del capítulo 2 del libro de referencia.*

> [!tip] Por qué te enseño este caso y no otro
> Porque es una **empresa pequeña y familiar**, no una multinacional. Aquí se ve que la industria 4.0 no es cosa de fábricas gigantes: **es cosa de quien tiene un problema que solo se resuelve sabiendo lo que pasa**.
>
> Y porque el tercer objetivo —«control total de la producción»— **no es tecnológico**. Es de gestión. La tecnología viene después, a servirlo.

> [!warning] ⚠️ Cuidado con los nombres
> En el caso resuelto, **Dimas es el consultor** que resuelve. En la práctica profesional del apartado 7, **Dimas es el cliente** que tiene el problema: es el dueño de una ferretería. **Son dos supuestos distintos**, y el libro reutiliza el nombre. No los mezcles.

---

## Fase 1 · Analizar el problema, no la tecnología

Dimas **no empieza mirando catálogos**. Empieza mirando dónde falla el proceso.

El problema no es «el pescado viene mal». El problema, descompuesto, son **tres cosas distintas**:

| El síntoma | Lo que hay detrás |
|---|---|
| Se cuelan piezas defectuosas | La inspección la hace una persona, ocho horas, a ojo |
| No se puede reclamar al proveedor | **Nadie registra** de qué lote y de qué proveedor venía cada defecto |
| No se sabe si se mejora | No hay ningún número que medir antes y después |

**Solo entonces** elige una tecnología: la **visión artificial**.

> [!example] 📖 Visión artificial
> Sistemas que **capturan imágenes y las interpretan automáticamente** para tomar una decisión sobre lo que ven: si una pieza está bien o mal, de qué tamaño es, de qué color.
>
> Es el ojo de la máquina. Y no se cansa a las siete horas.

> [!important] Fíjate en el orden, porque es el del módulo entero
> **Problema → dato que falta → tecnología que lo consigue.** Nunca al revés.
>
> Si empiezas por la tecnología, acabas con un sistema caro que resuelve algo que no dolía.

## Fase 2 · La segunda pieza: la trazabilidad

Dimas añade un segundo sistema: **trazabilidad por lotes** según el proveedor que envía el producto, usando tecnología **blockchain** —la misma que viste en la UD1 con Emma y los residuos—.

Por cada lote, los sensores y el sistema de clasificación registran:

- el **número de productos totales**,
- **cuántos se han descartado**,
- y **el motivo del descarte**.

Todo eso va **a la nube**.

> [!success] Y aquí está el verdadero cambio del caso
> Con esos tres datos, Emma puede por fin **sentarse delante de su proveedor con números**: *«de sus últimos diez lotes he descartado el 12 %, y en ocho de cada diez casos por espinas negras»*.
>
> **Antes de esto, esa conversación era imposible.** Y no la ha hecho posible un robot: la ha hecho posible un registro.

## Fase 3 · El sistema completo que propone

| # | Qué propone | Para qué sirve |
|---:|---|---|
| 1 | **Cámaras de visión artificial** en la línea de clasificación | Inspeccionar y catalogar los productos defectuosos |
| 2 | Un algoritmo de **deep learning** *(aprendizaje profundo: la IA que aprende a reconocer a base de ejemplos)* | Que el sistema distinga una espina de una sombra |
| 3 | **Barras de iluminación** | Que la cámara vea siempre en las mismas condiciones. Sin esto, lo anterior no funciona |
| 4 | **Trazabilidad por lotes** con blockchain, guardada en la nube | Saber qué proveedor manda qué, y poder demostrarlo |
| 5 | **Inspección también del producto ya empaquetado** | Control total de la producción y un **estándar de calidad** |
| 6 | **Clasificación en la propia cinta transportadora** | El sistema reconoce formatos, tamaños y colores, y **desvía lo defectuoso a una zona de recuperación** |
| 7 | **Visión hiperespectral** *(analiza las características químicas del producto, no solo su aspecto)* | Detectar imperfecciones y anomalías que no se ven |
| 8 | **Recuperar en vez de tirar**: quitar plásticos, piel y espinas y clasificar ese producto **como de segunda** | Procesar, si es posible, **el 100 % del producto recibido** |

> [!tip] 💡 El punto 8 es de la UD1, no de esta
> Fíjate en lo que hace: **lo que antes era merma —basura— ahora es un producto de segunda categoría**, más barato, para otro tipo de cliente.
>
> Eso es economía circular pura, y la ha hecho posible la tecnología de esta unidad. **Así encajan las dos unidades**: la UD1 dice qué hay que conseguir; la UD2, con qué se consigue.

## Fase 4 · Qué gana cada uno · `CE.02.e` `CE.02.f`

Dimas no cierra con «el sistema es muy moderno». Cierra diciendo **quién gana qué**:

| Quién | Qué gana |
|---|---|
| 🏢 **La empresa** | Control total de la producción · un estándar de calidad · menos coste · más productos en venta (primera y segunda categoría) |
| 🙋 **El cliente** | **Muchas menos devoluciones** por productos que no cumplen la calidad esperada · más satisfacción · un producto de segunda a menor precio si le encaja |
| 👷 **Los trabajadores** | Dedican menos tiempo a clasificar y más a tareas de mayor valor —verificar el empaquetado, el peso, el embolsado— · **tareas menos repetitivas y de mayor componente intelectual** · **menos bajas laborales**, porque el trabajo repetitivo provoca contracturas y otros problemas osteoarticulares |

> [!important] La tercera columna es la que casi nadie escribe
> `CE.02.f` pide las ventajas **para clientes y empresas**. Los trabajadores no están en el criterio… y sin embargo son el argumento más sólido del caso, porque **es medible**: las bajas laborales se cuentan.
>
> Si en tu informe metes una ventaja que se puede contar, tu informe vale más que uno lleno de adjetivos.

---

> [!success] 🎯 Lo que este caso te enseña a hacer
> 1. **Descomponer el problema** antes de elegir tecnología: síntoma → dato que falta → herramienta.
> 2. **Justificar cada pieza** por lo que resuelve. Hasta las barras de iluminación tienen su porqué.
> 3. **Registrar para poder negociar**: el dato no es el fin, es el argumento.
> 4. **Cerrar diciendo quién gana qué**, separando empresa, cliente y trabajadores.
>
> Ese es exactamente el guion del informe que tienes que escribirle a Dimas en el apartado 7. Vuelve aquí cuando lo estés haciendo.

---

| ← Anterior | 🧭 Índice | Siguiente → |
| :--- | :---: | ---: |
| [[UD2.5_Glosario_y_Quizlet]] | [[00_Indice_DASP]] | [[UD2.7_Actividades]] |
