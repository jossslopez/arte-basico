# arte-basico

[![Licencia: CC BY-NC-SA 4.0](https://img.shields.io/badge/licencia-CC%20BY--NC--SA%204.0-6C3BEF.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Skill abierta de dirección de arte publicitaria para transformar una fotografía de producto en una creatividad con decisiones explícitas de composición, luz, óptica, paleta y jerarquía.

Creada por **Joss López** ([@Jossslopez](https://www.youtube.com/@Jossslopez)).

## Qué incluye

| Comando | Resultado |
| --- | --- |
| `/exploded` | Despiece técnico en el aire, sin texto añadido |
| `/monolith` | Producto convertido en arquitectura, sin texto |
| `/typelock` | Producto y nombre real de marca compartiendo espacio |
| `/launch` | Gráfica de lanzamiento con titular y firma |
| `/analogy` | Producto convertido en una analogía de su beneficio |

El skill analiza primero la geometría, los materiales, la paleta y los códigos de marca del producto. Después define una frase creativa, un recurso visual y una tensión compositiva antes de decidir la luz, la óptica o el fondo. La revisión final bloquea resultados genéricos, productos flotantes y layouts de plantilla sin cambiar deliberadamente el diseño, el logotipo ni el texto del envase.

## Uso rápido

1. Descarga este repositorio como ZIP o conserva la carpeta completa.
2. Añade la carpeta a una aplicación compatible con skills basadas en `SKILL.md`.
3. Adjunta una fotografía del producto y escribe uno de los cinco comandos.

Ejemplo:

```text
/launch más oscuro · vertical 4:5
```

Los ajustes escritos después del comando tienen prioridad. Consulta la [guía visual](docs/guia-arte-basico.pdf) para ver la explicación completa.

## Estructura

```text
arte-basico/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── docs/
│   └── guia-arte-basico.pdf
├── ATTRIBUTION.md
├── LICENSE
├── NOTICE.md
└── README.md
```

## Alcance y límites

- Requiere una aplicación con entrada de imágenes y capacidad de generación o edición visual.
- La fidelidad de logotipos, textos de envase y detalles pequeños debe revisarse antes de publicar una pieza.
- Quien use el skill debe tener permiso para utilizar la fotografía, la marca y los demás materiales aportados.
- El repositorio contiene la versión básica de cinco comandos. La versión completa de quince comandos no está incluida.
- Este proyecto no está afiliado ni respaldado por OpenAI ni por las marcas de los productos que puedan aparecer en ejemplos o resultados.

## Licencia

Salvo indicación expresa, el contenido de este repositorio —incluidos `SKILL.md`, la documentación y el PDF— se publica bajo **Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**.

Identificador SPDX: `CC-BY-NC-SA-4.0`.

En resumen, puedes compartirlo y adaptarlo para fines no comerciales si:

- das crédito a Joss López;
- enlazas la licencia;
- indicas los cambios realizados; y
- publicas las adaptaciones bajo la misma licencia.

El resumen no sustituye al texto legal de [LICENSE](LICENSE). Para atribuir correctamente, consulta [ATTRIBUTION.md](ATTRIBUTION.md). Los nombres comerciales, logotipos y marcas de terceros no quedan licenciados por este repositorio; consulta [NOTICE.md](NOTICE.md).

Para usos comerciales o una licencia distinta, contacta con el autor a través de [jossslopez.com](https://jossslopez.com/).
