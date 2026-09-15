Proyecto grupal - Landing Page "PulseFit Gym"
Sesion 06 - LESS: variables, funciones, operaciones, mixins y anidamiento

Integrantes:
- [Nombre integrante 1] - Estructura HTML
- [Nombre integrante 2] - Diseño LESS (variables, funciones, mixins)
- [Nombre integrante 3] - Responsive 
- [Nombre integrante 4] - Documentación (README y capturas)

Descripcion del proyecto
-------------------------
Landing page responsiva para un gimnasio ficticio llamado "PulseFit Gym".
La pagina presenta una seccion de bienvenida (hero), los servicios del
gimnasio en formato de tarjetas (Grid), los planes de membresia
(Flexbox) y una seccion de contacto, todo dentro de un header con
navegacion y un footer.

Que implemento cada integrante (completar con los nombres reales)
-------------------------------------------------------------------
- [Nombre integrante 1]: maquetacion del HTML semantico (header, nav,
  main con 4 secciones, footer) y contenido textual de la pagina.
- [Nombre integrante 2]: definicion de variables globales en styles.less,
  mixin simple ".sombra()", mixin parametrico ".boton()" y aplicacion de
  las funciones lighten(), darken() y saturate().
- [Nombre integrante 3]: anidamiento del navbar y de los planes, media
  query para pantallas de 768px o menos, pruebas en escritorio y movil.
- [Nombre integrante 4]: README, capturas de pantalla y preparacion de
  la exposicion.

Requisitos cumplidos (ver punto 11.3 de la guia)
--------------------------------------------------
1. HTML semantico: header, nav, main, 4 secciones (hero, servicios,
   planes, contacto) y footer.
2. Variables LESS (8 en total): @primario, @secundario, @acento (colores),
   @espaciado (espaciado), @radio (radio de borde), @fuente-base y
   @ancho-maximo (tipografia/ancho).
3. Funciones LESS: lighten(), darken() y saturate() (mas de 2).
4. Mixin simple: ".sombra()" reutilizado en ".tarjeta" y ".plan".
5. Mixin parametrico: ".boton(@fondo, @texto, @padding)" con 3
   parametros, usado 4 veces con valores distintos (boton-principal,
   btn-plan-basico, btn-plan-premium, btn-plan-familiar).
6. Anidamiento: en ".encabezado" (marca, menu, enlaces y &:hover) y en
   ".lista-planes .plan" (precio, modificador &.plan--destacado).
7. Operaciones matematicas: @espaciado * 2, @espaciado * 1.5,
   @fuente-base * 1.4, @espaciado - 4px, entre otras.
8. Diseño responsivo: media query @media (max-width: 768px) que ajusta
   el header, el grid de servicios y la lista de planes.
9. Flexbox/Grid: Grid en ".grid-servicios" (3 columnas) y Flexbox en
   ".encabezado" y ".lista-planes".
10. Codigo generado: se incluyen "styles.less" (codigo fuente) y
    "styles.css" (resultado de la transpilacion).

Como visualizar el proyecto
-----------------------------
1. Abrir la carpeta "proyecto_grupal_less" en Visual Studio Code.
2. Abrir "index.html" con Live Server o directamente en el navegador.
3. Si se desea modificar estilos, editar "styles.less" y recompilar con
   Easy LESS (al guardar se regenera "styles.css").

Capturas
--------
Agregar en esta carpeta las imagenes:
- captura-escritorio.png
- captura-movil.png
