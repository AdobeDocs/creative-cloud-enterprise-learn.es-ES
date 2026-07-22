---
title: Biblioteca de plantillas
description: Explora las plantillas de gráficos de Firefly ya creadas que puedes abrir y adaptar a tu propio proyecto
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: aa0ae4747f081c69d8a01d3f9acdd7844cca6afe
workflow-type: tm+mt
source-wordcount: '996'
ht-degree: 2%

---

# &#x200B;5. Biblioteca de plantillas

Un índice de referencia rápida de plantillas de Gráficos de Firefly, organizado por lo que produce o hace cada una. Cada ejemplo es un punto de partida: intercambia tu propia marca, producto e indicaciones antes de usar una plantilla en producción.

## Generación y estilo de imágenes

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Introducción: generar una imagen**](/help/firefly/graph/templates/get-started-gen-image.md) | Esta plantilla es un gráfico básico: un nodo de solicitud en un nodo de generación en un resultado. Utilícelo como la primera plantilla que se abra con cualquier usuario nuevo. | Comercio minorista, salud y educación |
| [**Generación coherente de caracteres**](/help/firefly/graph/templates/character-gen.md) | En esta plantilla de gráfico se carga una imagen de referencia de un personaje y, a continuación, se intercambia la escena o el mensaje de pose para cada nueva toma. La referencia de carácter permanece bloqueada mientras cambia la escena circundante. | Viajes, comercio minorista, educación |
| [**Extracción de estilos**](/help/firefly/graph/templates/style-extraction.md) | En esta plantilla de gráfica se alimenta una imagen de referencia para extraer su color, luz y tratamiento de textura. A continuación, puede aplicar ese tratamiento a cualquier imagen nueva ejecutada a través del mismo gráfico. | Viajes, comercio minorista, bebidas |
| [**Vibraciones del atardecer**](/help/firefly/graph/templates/sunset-vibes.md) | En esta plantilla de gráfico puede crear una imagen tipográfica 3D a partir de un mensaje de texto. La plantilla gestiona la colocación y el equilibrio de color automáticamente. | Viajes, bebidas, comercio minorista |

## Segmentación y composición

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Introducción: segmentar una imagen**](/help/firefly/graph/templates/get-started-segment-image.md) | En esta plantilla de gráficos se carga cualquier imagen de origen y se ejecuta el nodo de segmentación para aislar el sujeto de su fondo. Emparejar con un nodo de reemplazo de fondo para un recorte limpio. | Salud, venta al por menor, automoción |
| [**Componer y mezclar capas**](/help/firefly/graph/templates/composite-blend-layers.md) | En esta plantilla de gráfico, se apilan un recorte de producto y una escena de fondo como entradas de capa independientes. Ajuste el modo de fusión y los nodos de iluminación hasta que la composición se muestre como una toma. | Bebidas, Comercio minorista, Viajes |
| [**Corrección selectiva del color**](/help/firefly/graph/templates/selective-color-correction.md) | En esta plantilla de gráfico enmascara una región específica que necesita corrección y establece el color de destino solo en ese nodo. El resto de la imagen pasa intacta por el gráfico. | Comunicaciones y telecomunicaciones, minoristas, finanzas |

## Vídeo y movimiento

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Introducción: generación de vídeo**](/help/firefly/graph/templates/get-started-video-gen.md) | En esta plantilla de gráfico se incluye una ilustración clave fija aprobada y un mensaje de movimiento corto. La plantilla genera un corte de vídeo creado a partir de esa misma ilustración clave en lugar de una nueva toma. | Finanzas, Bebidas, Comercio minorista |
| [**VFX de hora de viñeta**](/help/firefly/graph/templates/bullet-time-vfx.md) | En esta plantilla de gráfico, puedes alimentar una imagen de sujeto o producto principal para generar una secuencia giratoria de ángulos a su alrededor y, a continuación, unir el barrido de fotogramas congelados automáticamente. | Al aire libre, minoristas, automoción |

## Guion gráfico

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Texto en guión gráfico**](/help/firefly/graph/templates/text-to-storyboard.md) | En esta plantilla de gráfico, reemplaza los nodos de entrada de texto por elementos de su artículo. Cada línea se convierte en su propio marco de guion gráfico, generado en secuencia y presentado para su revisión como un conjunto de paneles único. | Finanzas, minoristas y tecnología |
| [**Generador de guiones gráficos**](/help/firefly/graph/templates/storyboard-builder.md) | En esta plantilla de gráficos se crea un guion gráfico escena por escena, añadiendo un nodo por pulsación de la narrativa. Reordene los nodos para probar una secuencia diferente antes de bloquear el orden final de los paneles. | Comunicaciones y telecomunicaciones, Bebidas, Viajes |

## 3D y carácter

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Sombreadores en tiempo real**](/help/firefly/graph/templates/real-time-shaders.md) | En esta plantilla de gráfico, se empieza con una imagen y se aplican tres sombreadores personalizados diferentes y se previsualiza el resultado en tiempo real. Ajuste los parámetros del sombreado directamente en el nodo en lugar de volver a procesar desde cero. | Tecnología, automoción y venta al por menor |
| [**Generación de modelos de caracteres**](/help/firefly/graph/templates/character-model-generation.md) | En esta plantilla de gráfico se crea un estilo animado 3D de una ilustración. La plantilla genera un pase de modelo 3D base listo para entregarlo a un modelador para su limpieza, en lugar de comenzar a partir de una escena en blanco. | Exterior, Tecnología, Educación |
| [**Diseño de juguetes de vinilo**](/help/firefly/graph/templates/vinyl-toy-design.md) | En esta plantilla de gráfico, se introduce una referencia de carácter o mascota y se procesa en un formulario de juguete de vinilo estilizado. Hay ángulos de respuesta para una plataforma de revisión de licencias o productos. | Venta al por menor, Bebidas, Entretenimiento |
| [**Cambio de boceto a 3D**](/help/firefly/graph/templates/sketch-to-3d.md) | En esta plantilla de gráfico, convierte un boceto en un personaje 3D. El gráfico genera un cambio de rumbo en 3D a partir de él, listo para una revisión de diseño interno antes de cualquier prototipo físico. | Tecnología, Automoción, Entretenimiento |

## Maquetas de productos y marcas

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Visualización de marca**](/help/firefly/graph/templates/branding-visualization.md) | En esta plantilla de gráfico, aprende a visualizar el logotipo o la marca en las escenas de los productos. Incorpora directrices de marca para un logotipo y una paleta de colores, y el gráfico genera tanto ilustraciones clave estáticas como una pasada de movimiento corto en una sola ejecución, para que ambos formatos permanezcan visualmente alineados. | Tecnología, Bebidas, Finanzas |
| [**Modelo de producto de marca**](/help/firefly/graph/templates/brand-product-mockup.md) | En esta plantilla de gráfico aprenderás a visualizar tu producto en diferentes escenas. Se coloca un renderizado de producto o una foto en el nodo de boceto y el gráfico lo coloca dentro de una escena totalmente de marca, con la iluminación y la sombra coincidentes con esa escena automáticamente. | Comercio minorista, bebidas, tecnología |
| [**Sesión de fotos editorial**](/help/firefly/graph/templates/editorial-photoshoot.md) | En esta plantilla de gráfica se carga una referencia de modelo y se intercambia la entrada de prenda para cada nuevo look. Los nodos de pose e iluminación permanecen bloqueados en todo el conjunto para una sensación editorial coherente. | Comercio minorista, belleza, al aire libre |
| [**Estudio fotográfico**](/help/firefly/graph/templates/photography-studio.md) | En esta plantilla de gráfico, se coloca un renderizado de producto en el fondo del estudio y se ajusta la iluminación hasta que el resultado se vea como una captura de estudio real. | Bebidas, tecnología, comercio minorista |
| [**Aplicar pegatina a las superficies**](/help/firefly/graph/templates/decal-to-surfaces.md) | En esta plantilla de gráfico se carga el boceto del producto base y la pegatina o el activo del logotipo como entradas independientes. La plantilla envuelve la pegatina en la geometría de superficie para que siga los contornos correctamente. | Al aire libre, Automoción, Comercio minorista |

## Operaciones por lotes y coherencia

| Plantilla de gráficos | Descripción | [!BADGE Casos prácticos]{type=Informative tooltip="Casos prácticos"} |
|---|---|---|
| [**Diseñar generador de sistemas**](/help/firefly/graph/templates/design-system-generator.md) | En esta plantilla de gráficos se genera un sistema de diseño basado en una captura de pantalla de un sitio web. El gráfico produce un conjunto coincidente de iconos, patrones y componentes de diseño en una sola ejecución por lotes. | Tecnología, finanzas, comunicaciones y telecomunicaciones |
| [**Generación de primeros planos**](/help/firefly/graph/templates/headshots-generation.md) | En esta plantilla de gráficos armonizas un lote de retratos corporativos. Carga las fotos de origen, una por persona, y el gráfico normaliza la iluminación, el fondo y el recorte en todo el conjunto de una sola ejecución. | Tecnología, finanzas y salud |

Vuelva a [Introducción al gráfico de Firefly](https://experienceleague.adobe.com/en/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph).