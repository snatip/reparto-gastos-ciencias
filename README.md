# Reparto de gastos · Consejo de Estudiantes de Ciencias

Herramienta web para repartir el coste de una lista de gastos (conceptos) entre varios
pagadores, según el porcentaje, fracción o peso relativo que le corresponda a cada uno.
Calcula varias alternativas de asignación y muestra la que mejor se ajusta a los
objetivos de reparto.

Creada para el Consejo de Estudiantes de la Facultad de Ciencias (antes Delegación de
Estudiantes), Universidad de Zaragoza.

## 🔗 Página en vivo

**https://snatip.github.io/reparto-gastos-ciencias/**

## 📎 Insertar como iframe

Para incrustar la herramienta en otra página (una intranet, un sitio de la delegación,
etc.):

```html
<iframe
  src="https://snatip.github.io/reparto-gastos-ciencias/"
  style="width:100%; min-height:900px; border:0"
  loading="lazy"
  title="Reparto de gastos · Consejo de Estudiantes de Ciencias">
</iframe>
```

> **Nota:** algunos navegadores restringen el `localStorage` dentro de iframes de
> distinto origen, así que los datos introducidos podrían no guardarse entre visitas
> cuando se usa embebida. La herramienta funciona igualmente; para que los datos se
> conserven de forma fiable, usa el [enlace directo](https://snatip.github.io/reparto-gastos-ciencias/).

## 🔒 Privacidad de los datos

- **Ningún dato sale del navegador.** No hay servidor ni backend: todos los cálculos se
  ejecutan localmente en el dispositivo del usuario.
- Lo que se introduce (pagadores, importes, conceptos) se guarda únicamente en el
  `localStorage` del navegador, nunca se envía a ningún sitio.
- **Funciona sin conexión a internet** y es **autocontenida**: un único archivo HTML con el
  CSS y el JavaScript incluidos, sin dependencias externas (aparte del logo y el favicon,
  que son archivos sueltos de este repositorio; sin ellos funciona igual).
- Puedes **descargar el archivo `index.html`** de este repositorio y abrirlo
  directamente en un navegador para usarlo de forma totalmente offline, sin depender de
  esta página ni de GitHub.

Dentro de la propia herramienta hay un botón **ⓘ** en la esquina superior derecha con
esta misma información y una guía rápida de uso.

## 🌙 Modo oscuro

La herramienta incluye un interruptor de tema (junto al botón ⓘ) que alterna entre modo
claro y modo oscuro. Respeta la preferencia del sistema por defecto y recuerda la
elección en `localStorage`.

## ✨ Nota

Esta herramienta está **«vibe-coded»**: creada con ayuda de IA, de forma rápida e
informal. Es útil como apoyo para repartir gastos, pero conviene revisar los resultados
antes de darlos por definitivos.

## 🛠️ Uso local

No requiere instalación ni build. Basta con abrir `index.html` en cualquier navegador
moderno (Chrome, Firefox, Edge, Safari).
