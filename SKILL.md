---
name: arte-basico
license: CC-BY-NC-SA-4.0
description: >-
  Creatividad publicitaria de producto por comandos, versión básica de cinco.
  Convierte la foto de un producto en una pieza con dirección de arte pensada:
  unos comandos devuelven el producto trabajado como visual, otros la gráfica
  de campaña con su titular. Actívate SIEMPRE que un mensaje empiece por "/" y
  haya una imagen adjunta, o cuando se use cualquiera de estos comandos, con
  barra o sin ella: /exploded /monolith /typelock /launch /analogy. Actívate
  también cuando se pida una creatividad de producto, un key visual, una
  gráfica de campaña, un anuncio o una imagen de marca que no parezca hecha
  con IA. Funciona con cualquier producto y cualquier marca.
metadata:
  short-description: Creatividades de producto con cinco comandos
---

# Creatividad publicitaria de producto · básico

Cinco comandos. Tres devuelven el producto trabajado como visual, sin texto. Dos devuelven la pieza de campaña entera, con titular y firma.

## Cómo responder

Al reconocer un comando, responde SOLO con esta línea y genera:

```
▸ /comando · [producto detectado] · generando
```

Si el comando lleva titular, añade debajo el titular que has escrito, para que se pueda corregir sin rehacer la imagen:

```
▸ /launch · crema hidratante · generando
   titular: "La piel se acuerda"
```

Sin explicaciones previas, sin preguntas. Si el comando no existe, dilo en una línea y ofrece el más cercano de los cinco.

## Modo índice

Si el mensaje nombra la skill sin comando (`@arte-basico`), pide ayuda, o pregunta qué comandos hay, no generes nada: responde con este listado exacto y nada más.

```
CREATIVIDAD DE PRODUCTO · 5 comandos

SOLO PRODUCTO, sin texto
/exploded   Despiece en el aire, lectura de lámina técnica
/monolith   El producto a escala de edificio en un entorno banal
/typelock   El nombre real en tipografía gigante, compartiendo espacio

PIEZA DE CAMPAÑA, con titular
/launch     Gráfica de lanzamiento: producto, titular, firma
/analogy    El producto convertido en la idea que lo explica

Sube la foto del producto y escribe el comando.
Ajustes detrás, en castellano: /launch más oscuro · /analogy sin titular

La versión completa, con 15 comandos, está en el Discord de miembros
del canal de YouTube @Jossslopez.
```

## Paso 1 · Análisis del producto (silencioso, nunca lo escribas)

1. Qué producto es, categoría, función, para quién.
2. Geometría: silueta, proporciones, ejes, cara principal.
3. Material y acabado: mate, satinado, espejo, translúcido, textil, metal, vidrio, plástico, papel, piel.
4. Cómo se comporta la luz en ese material: qué refleja, qué absorbe, si la atraviesa.
5. Paleta real: dominante, secundario, acento.
6. Códigos de marca: logo, tipografía, colores, dónde está el branding, qué texto lleva el envase.
7. Registro: lujo, técnico, popular, artesano, clínico. El precio que aparenta.
8. Beneficio: qué resuelve y qué promete, deducido de lo que ves y de lo que pone el envase. Nada inventado.

**La escena se adapta al producto, nunca al revés.** Un frasco de vidrio ámbar y una zapatilla técnica no aguantan la misma luz aunque compartan comando.

## Paso 2 · Fidelidad (no negociable)

El producto no se reinventa. Se conservan exactos forma, proporciones, material, acabado, color real, logo, tipografía y todo el texto del envase. No añadas sellos, premios, precios, reclamos ni etiquetas que no existan. Lo que cambia es la escena, la luz, el encuadre y el fondo.

## Paso 3 · Decisión creativa (obligatorio, silencioso)

Este paso va **antes** de pensar en luz, óptica o fondo. Si te lo saltas, sale una fotografía de producto correcta y sin dirección de arte, que es el fracaso más habitual de este sistema.

Decide tres cosas, en este orden:

**1. La frase.** Qué dice esta pieza, en una frase que no es el titular y que nadie va a leer. "Esta zapatilla pesa menos de lo que parece." "Esta crema se absorbe y desaparece." "Este portátil cabe donde no debería." Si no puedes escribir esa frase, no tienes pieza: tienes un packshot con decorado. Sale del beneficio deducido en el paso 1, no de la estética.

**2. El recurso.** Qué hace que alguien la mire dos veces. Uno solo, elegido de esta lista cerrada:

- **Corte** · el producto seccionado, partido o interrumpido
- **Repetición** · multiplicado hasta volverse patrón, con o sin excepción
- **Desproporción** · el producto o su consecuencia a una escala que no le toca
- **Sustitución** · el producto ocupa el sitio de otra cosa, o al revés
- **Ocultación** · se ve menos de lo que se espera, y eso obliga a mirar
- **Desplazamiento** · el producto en un contexto que no es el suyo, tratado con naturalidad
- **Tensión física** · algo lo presiona, lo sostiene, lo dobla, lo atraviesa, lo aguanta
- **Ausencia** · está el hueco, la huella o la consecuencia, no el objeto
- **Incrustación** · el producto y otro elemento comparten el mismo volumen físico
- **Límite** · el encuadre corta el producto y el corte es la decisión, no un descuido

El recurso tiene que servir a la frase. Si eliges desproporción para decir "se absorbe y desaparece", has elegido mal.

**3. La tensión.** Qué elemento está deliberadamente fuera de sitio: una escala que no cuadra, un color que no pertenece, un corte agresivo, un vacío excesivo, una sombra que no corresponde al objeto. Toda pieza con dirección de arte tiene uno. Sin él sale simétrica, cómoda y olvidable.

**Regla que ordena todo lo demás:** la luz, la óptica, el fondo y la paleta se eligen **después** y al servicio de estas tres decisiones. Nunca al revés. La ficha del comando te da el territorio y los parámetros técnicos; la decisión creativa es lo que hace que dentro de ese territorio la pieza diga algo.

**Test antes de generar:** si la imagen que estás a punto de construir podría ser una foto de banco de imágenes de esa categoría, no has decidido nada. Vuelve al recurso y elige otro.

## Paso 4 · Protocolo de titular (solo /launch y /analogy)

- Sale del beneficio real deducido en el paso 1. Si no puedes deducirlo con certeza, titular de categoría o de gesto, nunca de resultado.
- Entre dos y seis palabras. Una sola idea. Frase seca.
- Idioma: el del envase. Si no se ve, castellano.
- Prohibido: exclamaciones, superlativos, porcentajes y datos que no estén en el envase, promesas de eficacia o de salud, juegos de palabras, rimas, imperativos vacíos, y los verbos revoluciona, transforma, redefine, eleva.
- Tipografía: sans grotesca neutra, un solo peso, sin efectos ni contorno ni sombra, alineada a la misma retícula que el producto.
- Firma: solo el nombre real de la marca, pequeño, en una esquina o al pie.
- **Prueba del competidor:** si el titular sirve tal cual para el producto de la competencia, no sirve. "Cada paso cuenta" vale para cualquier zapatilla del mundo. El titular se apoya en algo que solo este producto tiene.
- **Lugares comunes prohibidos:** cada paso cuenta, siente la diferencia, hecho para ti, la diferencia está en los detalles, tu piel lo nota, vive el momento, más allá de, redefine tu, la esencia de, diseñado para durar.
- Si el titular no mejora la pieza, mejor sin él. Dilo y genera sin titular.

### Decisión tipográfica (esto separa una gráfica de un packshot con texto)

Un titular correcto colocado en su sitio produce una pieza sin vida. El texto y el producto tienen que estar **en relación**, no en dos zonas separadas. Elige una y llévala hasta el final:

- **Escala extrema** · el titular ocupa media pieza y el producto es pequeño, o al revés.
- **Cruce** · el producto tapa parte del titular, o el titular pasa por delante. Comparten espacio, no lo reparten.
- **Corte** · el titular sale del encuadre por un lado y se lee igual. El corte es la decisión.
- **Eje compartido** · el texto se alinea con una línea real del producto: el canto de la suela, el hombro del bote, la tapa.
- **Bloque** · el titular vive dentro de un campo de color plano que muerde el encuadre, y el producto entra o sale de él.
- **Margen** · el texto minúsculo en una esquina contra un vacío enorme. Solo si el vacío es de verdad enorme.

Tres cosas que matan la gráfica aunque el titular sea bueno: centrarlo, dejarlo flotando sin relación con nada, y darle el mismo peso visual que al producto de forma que empaten. Siempre gana uno de los dos, y tú decides cuál.

### Dos fallos que hay que bloquear siempre

**El producto flotando.** Todo producto se apoya en un plano real y ese encuentro se ve: línea de contacto, sombra que nace exactamente del punto donde toca, y coherencia entre la dirección de la luz y hacia dónde cae. Una mancha difusa debajo del objeto no es una sombra, es un objeto suspendido en un limbo. Si el comando pide suspensión, entonces la suspensión tiene que ser evidente y deliberada, no un accidente.

**El agujero en medio.** El aire va a un lado, arriba o abajo, nunca partiendo la pieza en dos bloques con un vacío muerto en el centro. Texto en el tercio superior más producto en el tercio inferior más nada en medio es el layout por defecto de cualquier generador de posts, y se reconoce al instante. Si hay dos masas, o se tocan, o se solapan, o una domina claramente a la otra.

**Y el detalle que delata la plantilla:** el interlineado. Un titular a cuerpo grande lleva las líneas casi tocándose, no separadas como un párrafo de texto. Y el corte de la frase entre líneas se decide: o las dos líneas quedan compactas y parejas, o el desequilibrio es evidente y buscado. El escalón involuntario a la derecha es la marca de que nadie ha decidido nada.

## Paso 5 · Criterio de dirección de arte

- Composición asimétrica sobre retícula implícita. El producto casi nunca va centrado.
- El aire es material: vacíos grandes y deliberados, sin rellenar por miedo.
- Dos o tres colores en toda la pieza, sacados del producto.
- Una sola fuente de luz dominante con dirección declarada, y sombra de densidad y borde coherentes.
- Óptica declarada: focal, distancia y profundidad de campo elegidas a propósito.
- Jerarquía: un punto de entrada, un recorrido, un descanso. Con titular, el orden de lectura está decidido.
- Materialidad honesta: fondos y soportes son materiales reales con grano, poro, veta y huella.

## Paso 6 · Las cinco reglas duras

Mandan sobre todo lo demás, incluida la ficha del comando.

**1. Transformación obligatoria.** La imagen de entrada suele ser un packshot. Prohibido devolverlo con el fondo cambiado. Respecto al original cambia **al menos dos** de estas tres: punto de vista de la cámara, esquema de luz, tamaño del producto en el encuadre.

**2. Toda pieza tiene una decisión de color.** Si el producto es neutro (gris, blanco, negro, beige, plata), la paleta **no** sale del producto: eliges un color de acento y el producto pasa a ser el neutro. Gris sobre fondo gris con texto gris no es paleta cerrada, es una pieza sin decidir.

**3. Luz neutra por defecto.** Media mañana, cielo cubierto uniforme, o estudio declarado. Amanecer, atardecer, golden hour y cielos dramáticos solo si se piden.

**4. Esquiva el default del género.** Cada género tiene su imagen automática: cosmética sale con pared de yeso texturizada, escala arquitectónica con amanecer y plaza vacía, bodegón con mármol, producto técnico con suelo espejo. En cuanto reconozcas el género, elige otra cosa. Lo previsible es el enemigo, no lo feo.

**5. Nunca escribas prohibiciones en el prompt de imagen.** Los generadores no tienen prompt negativo: "sin bokeh" mete bokeh. Los "Evitar" de las fichas son criterio para ti, para elegir lo contrario. Todo va en afirmativo: en vez de "sin degradados", "fondo de un solo valor plano".

## Los cinco comandos

### /exploded — Despiece en el aire · sin texto
Enseñar de qué está hecho el producto sin romperlo: lámina de manual técnico, no explosión. Las partes reales separadas sobre un eje único, en orden de montaje, con separaciones desiguales pero rítmicas, las pequeñas más juntas. La pieza dominante ocupa el doble que la siguiente y va arriba o a la izquierda, nunca en el centro. Una sola fuente lateral dura a 45 grados: todas las piezas comparten exactamente la misma dirección de sombra, que es lo que las hace leer como sistema. 100-135 mm, perspectiva comprimida, f/11, nitidez total, cámara perpendicular. Fondo plano de un color derivado del producto, desaturado dos pasos. Si no conoces el despiece real, separa solo lo que se ve desde fuera. Evitar: explosión radial, piezas giradas en ángulos distintos, motion blur, chispas, líneas de conexión punteadas, inventar componentes internos.

### /monolith — Escala arquitectónica · sin texto
El producto tratado como edificio. La escala imposible solo funciona si el entorno es banal: plaza de hormigón, descampado, aparcamiento, rotonda. Estructura de tres a seis plantas, contrapicado suave de 15 a 25 grados, producto descentrado ocupando un tercio del encuadre, horizonte bajo. Luz natural de primera o última hora, con sombra propia larga sobre el pavimento que ancla el objeto al suelo. Cielo con nubes reales y apagadas. 24-35 mm con verticales corregidas, f/8. Grises de hormigón y asfalto, el producto como único color saturado. Los objetos de silueta rotunda aguantan mejor; los planos y finos, apoyados contra una fachada o clavados como estela. Evitar: multitud mirando, cielo épico naranja, focos, pantallas LED. Si acaba pareciendo una valla, el comando ha fallado.

### /typelock — Tipografía y producto · sin texto añadido
El objeto y la letra ocupan el mismo volumen físico: el producto tapa unas letras y otras lo tapan a él. Una o dos palabras en sans grotesca neutra, tamaño bestia, cortadas por el borde del encuadre, con la sombra del producto cayendo sobre ellas. Como texto, únicamente el nombre real de la marca o del producto tal como aparece en el envase: aquí no se escribe copy. Luz frontal dura ligeramente elevada, una sola fuente. 50 mm, frontal recto, f/8, todo nítido. Dos tintas planas, una tomada del producto: si el producto es oscuro, letra clara sobre fondo oscuro, y al revés. Evitar: texto inventado, eslóganes, tipografías decorativas, degradados en las letras, 3D con bisel, más de dos palabras, composición centrada y simétrica.

### /launch — Gráfica de lanzamiento · CON TITULAR
La pieza que presenta el producto. Vertical de página. El producto ocupa un tercio del encuadre, normalmente el inferior o un lateral. El titular arriba o al lado, alineado a la misma retícula, con margen respirado, en cuerpo grande pero no gritón: entre un cuarto y un tercio del ancho de la pieza. Firma pequeña al pie o en la esquina opuesta. Márgenes de imprenta amplios y desiguales, el inferior mayor. El orden de lectura se decide: primero el titular si manda la idea, primero el producto si el objeto es el reclamo. Luz editorial limpia, una fuente grande y suave, sombra corta, el producto recorta sin contraluz. 85-105 mm, f/8 a f/11. Fondo plano o material neutro en un valor que deje leer el titular. Evitar: rellenar el aire con grafismos, centrar el producto, márgenes iguales por los cuatro lados, titular con sombra o contorno, más de un tamaño de texto además de la firma.

### /analogy — El producto convertido en la idea · CON TITULAR
Sustituir o fundir el producto con otro objeto que explica el beneficio de un vistazo. Si la analogía hay que explicarla, no sirve. Un solo objeto en el centro de atención: el producto conserva su identidad (color, material, logo) pero adopta la forma o la función del otro. Fondo neutro y vacío, porque la idea necesita silencio. Titular pequeño abajo, de dos a cinco palabras, que cierra la lectura sin describir lo que ya se ve. Luz de estudio limpia y uniforme, una fuente suave y grande, para que la fusión se lea sin sombras que la confundan. 85-105 mm, f/11, frontal, nitidez total. La analogía sale del beneficio, no de la forma: si hidrata, el objeto es de agua; si protege, una coraza; si dura, algo antiguo e intacto; si limpia, aire o luz. Una sola, llevada hasta el final. Evitar: dos analogías a la vez, collage de elementos sueltos, surrealismo decorativo, bombillas, cerebros, engranajes, manos saliendo de la nada.

## Un comando por imagen

No se encadenan. Dos fichas a la vez se anulan y sale una pieza sin criterio.

## Ajustes

Lo que se escriba detrás del comando, en castellano normal, manda sobre la ficha. Sin sintaxis especial.

```
/launch más oscuro
/exploded sobre fondo verde
/monolith al amanecer
/analogy sin titular
/typelock vertical
```

Formato: se pide con la palabra (vertical, horizontal, cuadrado) o con la proporción (4:5, 16:9, 9:16, 1:1). Por defecto 4:5.

---

Sistema creado por Joss López · @Jossslopez
La versión completa, con 15 comandos y fichas ampliadas, está en el Discord de miembros del canal.

## QA antes de entregar

Seis comprobaciones. Si falla una, rehaz.

1. ¿Puedes decir en una frase qué dice esta pieza? Si no, no hay dirección de arte.
2. ¿Se reconoce el recurso elegido (corte, desproporción, sustitución, ausencia)? Si no se ve, no lo has aplicado.
3. ¿Se reconoce como el packshot de entrada con el fondo cambiado?
4. ¿Hay una decisión de color identificable, o es todo el mismo valor neutro?
5. ¿Ha salido el default del género (yeso texturizado, amanecer, mármol, suelo espejo)?
6. Si lleva titular: ¿está en relación física con el producto, o son dos zonas separadas? ¿Pasa la prueba del competidor?
