## UD3 · Apartado 4 — 🛑 Lo que NO es

> **[Módulo: Digitalización Aplicada a los Sectores Productivos]** · **Unidad 3 de 5**
> 🧭 Índice del módulo: [[00_Indice_DASP]]
>
> **📍 Cuándo se lee:** en cuanto termines el fundamento. Son los siete malentendidos que salen todos los años.

---

> [!danger] 🛑 1 · La nube **NO** es un sitio donde se guardan cosas
> Eso es un disco duro con Internet. La nube es **un modelo de contratación y de reparto de responsabilidades**: alquilas en vez de comprar, y **decides hasta qué capa te encargas tú**.
>
> Prueba de que no va de almacenamiento: **PaaS, CaaS y SaaS no se contratan para guardar ficheros**. Se contratan para no tener que administrar sistemas operativos, plataformas o aplicaciones.
>
> Si tu definición de nube empieza por «un espacio donde», reescríbela.

> [!danger] 🛑 2 · «Nube privada» **NO** es una nube más segura por definición
> Una nube privada ofrece recursos cloud de **uso exclusivo de una organización**, pero puede estar en sus instalaciones o alojada por un proveedor. **On-premise** solo indica dónde está el hardware. Son dos ejes diferentes: exclusividad y ubicación.
>
> Y lo que casi nadie espera: **la nube pública suele ser más segura**, porque el proveedor tiene **equipos de personas dedicados íntegramente a la seguridad**, y tú tienes a un técnico que además hace otras diez cosas.
>
> Se elige privada por **control y por confidencialidad**, no porque sea automáticamente más segura.

> [!danger] 🛑 3 · La nube **NO** es siempre más barata
> Es más barata **cuando se dimensiona bien**. La ventaja real es que **pagas por lo que consumes** y no haces un desembolso inicial. Pero si contratas recursos que no usas, pagas recursos que no usas — igual que comprando servidores.
>
> Además, introduce dependencias que deben analizarse: la conexión, el proveedor, la configuración, la recuperación ante incidentes y los costes variables. Para una empresa que factura online, una caída de conectividad puede paralizar una parte esencial del trabajo.

> [!danger] 🛑 4 · El edge computing **NO** es más potente que la nube
> Es **menos** potente: poca capacidad de procesamiento y poco almacenamiento. Lo que tiene es **latencia baja**.
>
> La diferencia esencial es esta: **potencia** indica cuánto puede procesar un sistema; **latencia**, cuánto tarda en responder. Hay una pregunta del test dedicada exactamente a distinguirlas.
>
> Regla: **¿hace falta pensar mucho? Cloud. ¿Hace falta contestar ya? Edge.**

> [!danger] 🛑 5 · Edge, fog y mist **NO** sustituyen a la nube
> **Son capas que la complementan.** La mayoría de los sistemas usan cloud computing; lo que pasa es que **no todos son susceptibles de usarla para todo**.
>
> Un coche autónomo procesa en el borde **y** manda al centro de datos lo que no corre prisa. No es «o una o la otra»: **es a qué distancia se procesa cada cosa**.

> [!danger] 🛑 6 · *Fog* y *mist* **NO** son sinónimos, y van en este orden
> **Mist (rocío) está más cerca que fog (niebla).** El rocío está en la flor; la niebla, por encima.
>
> | | Fog | Mist |
> |---|---|---|
> | Procesa en | un **hub** o controlador cercano | **el propio sensor** |
> | Se usa con | **varios sensores** a la vez | **un único sensor** independiente |
> | Su punto débil | si el hub cae, **cae todo** | necesita **más batería** y un sensor más inteligente |
>
> En el test, lee con cuidado qué capa está **más cerca** del sensor y cuál está **más lejos**.

> [!danger] 🛑 7 · Subir a la nube **NO** te quita la responsabilidad sobre tus datos
> Mira otra vez la escalera del apartado 3.1: la fila de **datos y configuración es tuya en los cinco modelos**, incluido SaaS.
>
> El proveedor responde del hardware, del sistema y de la aplicación. **De lo que metes dentro, de quién tiene acceso y de qué haces con los datos personales de tus clientes, respondes tú.**
>
> En una gestoría o en un departamento de administración, esto no es teoría: es la ley de protección de datos.

---

> [!question] Comprueba que lo has entendido
> Una clínica dental quiere **grabar con cámaras la sala de espera** por seguridad y, a la vez, tener su **programa de citas y su facturación** accesibles desde las tres consultas del dueño.
>
> Contesta en tres frases:
> 1. ¿Qué parte pondrías en **cloud** y qué parte en **edge**? ¿Por qué?
> 2. ¿Qué **tipo de servicio** (IaaS, PaaS o SaaS) contratarías para el programa de citas?
> 3. ¿Qué pasa **el día que se cae Internet**, en cada una de las dos partes?
>
> Esta respuesta va en tu entrada.

---

| ← Anterior | 🧭 Índice | Siguiente → |
| :--- | :---: | ---: |
| [[UD3.3_Fundamento]] | [[00_Indice_DASP]] | [[UD3.5_Glosario_y_Quizlet]] |
