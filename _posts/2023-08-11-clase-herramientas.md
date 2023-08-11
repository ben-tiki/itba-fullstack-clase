---
layout: post
title: Clase de herramientas de desarrollo
---
# Visual Studio Code para FullStackers 

Visual Studio Code (VSCode) es un editor de código gratuito y open source desarrollado por Microsoft. Es multiplataforma, por lo que funciona en Windows, macOS y Linux, y cuenta con una enorme comunidad de desarrolladores que lo mantienen y lo extienden. VSCode es altamente configurable e incluye muchas características útiles, como autocompletado, snippets, resaltado de sintaxis, integración con Git y mucho más. En este material vas a encontrar información que espero te sea útil para empezar a codear con VSCode en tus proyectos.

# Contenido
1. [Instalación](#instalación)
2. [Temas](#temas)
3. [Extensiones](#extensiones)
4. [Emmet](#emmet)
5. [Shortcuts de teclado](#shortcuts-de-teclado)
6. [Snippets](#snippets)
7. [Terminal integrada](#terminal-integrada)
8. [Integración de control de versiones](#integración-de-control-de-versiones)

## Instalación
Para instalar VSCode, ingresá a la [página oficial](https://code.visualstudio.com/) y descarga el instalador para tu sistema operativo. Una vez que se complete la descarga, ejecuta el instalador y segui las instrucciones.

## Temas
VSCode viene con varios temas incorporados que podes cambiar según tus preferencias. Para cambiar el tema, podes seguir estos pasos:

1. Hace clic en el icono de engranaje en la esquina inferior izquierda.
2. Selecciona "Color Theme".
3. Elegí el tema que más te guste de la lista.

Además, podes buscar más temas en el Marketplace de VSCode. Acá dejo un artículo con [algunos de los mejores temas de VSCode](https://www.linkedin.com/pulse/10-best-vscode-themes-2023-zamir-khotov/). Yo personlamente uso [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl) 😊.

## Extensiones

Las extensiones son como aplicaciones para VSCode. Te permiten agregar nuevas funcionalidades y personalizar tu editor. Para instalar una extensión:

1. Hace clic en el icono de extensiones en la barra lateral izquierda.
2. Busca la extensión que querés instalar.
3. Hace clic en "Instalar".

Acá dejo una lista de extensiones que te pueden ser útiles:
 - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): te permite ejecutar un servidor local para tu proyecto y ver los cambios en tiempo real.
 - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): formatea tu código automáticamente.
 - [Github Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot): te ayuda a escribir código con sugerencias de inteligencia artificial.
 - [Vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons): agrega iconos a los archivos en el explorador de archivos.
 - [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight): resalta los colores en tu código.
 - [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter): te permite ejecutar notebooks de Jupyter en VSCode.

Esta es sólo una lista de extensiones que uso y me gustan, pero hay muchas más. Acá dejo un artículo con [algunas de las mejores extensiones de VSCode según la comunidad](https://x-team.com/blog/best-vscode-extensions/).

## Emmet

Emmet es un conjunto de plugins para editores de texto que te pueden hacer escribir HTML y CSS mucho más rápido. Con Emmet podés tipear abreviaturas que se expanden automáticamente en código HTML o CSS completo.

Por ejemplo en un documento HTML, si escribis `ul>li*5` y apretas `Tab`, Emmet va a generar:

```html
<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>
```

`Tip:` podés empezar rápidamente un documento HTML escribiendo `!` y apretando `Tab`.

## Shortcuts de teclado

VSCode tiene muchisimos atajos de teclado que te permiten navegar y editar tu código más rápido. Al principio puede ser difícil acordarse de todos, pero con el tiempo se vuelven naturales y te van a hacer ahorrar mucho tiempo.

| Combinación | Acción |
|-------|--------|
| `Ctrl + Shift + P` | Mostrar la paleta de comandos |
| `Ctrl + P` | Buscar archivos |
| `Ctrl + Space` | Sugerencias de autocompletado |
| `Alt+ ↑ / ↓ ` | Mover la línea actual hacia arriba o hacia abajo |
| `Ctrl + Shift + l ` | Seleccionar todas las ocurrencias de la selección actual |
| `Ctrl + Shift + k ` | Eliminar la línea actual |
| `Ctrl + / ` | Comentar la línea actual |

Dejo acá un cheatsheet con los atajos de teclado más comunes, para [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf), [macOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf) y [Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf).

## Snippets

Los [snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets) son templates de código que puedes reutilizar. VSCode viene con snippets incorporados para muchos lenguajes, pero también podes crear los propios. (cuando veas que estás escribiendo muchas veces el mismo código repetitivo, puede ser una buena oportunidad para crear un snippet).

Por ejemplo, si escribis `for` y apretas `Tab`, VSCode va a generar:

```javascript
for (let index = 0; index < array.length; index++) {
    const element = array[index];
    
}
```

Podes navegar entre los campos del snippet con `Tab` y `Shift + Tab`. Así vas completando los valores de cada campo con tus propios valores.

## Terminal integrada

VSCode tiene una [terminal integrada](https://code.visualstudio.com/docs/terminal/basics) que podes abrir seleccionando `View > Terminal` en el menú superior. La terminal se abre en la parte inferior de la pantalla.  Puedes ejecutar comandos de terminal directamente desde VSCode, lo que facilita la ejecución de scripts, la instalación de paquetes, el control de versiones, etc. 

## Integración de control de versiones

VSCode tiene una excelente integración con Git. Te permite hacer commit, push, pull, clonar repositorios, resolver conflictos de merge, ver el historial de commits y más, todo directamente VSCode.

Para usar Git en VSCode, primero tenes que instalar Git en tu computadora y después abrir un repositorio en VSCode. Los cambios en los archivos se van a resaltar en el explorador de archivos y vas a poder ver los detalles de los cambios en la vista de control de versiones.

## Ahora, a codear!
A medida que vayas usando VSCode, vas a ir descubriendo más funcionalidades y atajos de teclado que te van a ayudar a ser más productivo. Espero que este material te haya sido útil y que te animes a probar VSCode en tus proyectos. Si tenés un tiempo, comparto una lista de videos y canales de Youtube que me gustan y que tienen muy bueno contenido de programación:

<!-- VIDEO GRID -->
<br>
<table>
  <tr>
    <td><iframe width="100%" height="100%" src="https://www.youtube.com/embed/WPqXP_kLzpo" title="freeCodeCamp" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    <td><iframe width="100%" height="100%" src="https://www.youtube.com/embed/Ei1y51K8jQk"  title="holaMundo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
  </tr>
  <tr>
    <td><iframe width="100%" height="100%" src="https://www.youtube.com/embed/fJEbVCrEMSE" title="codeStacker" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    <td><iframe width="100%" height="100%" src="https://www.youtube.com/embed/H2gvHxC9gFY" title="forestKnight" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
  </tr>
  <tr>
    <td><iframe width="100%" height="100%" src="https://www.youtube.com/embed/-nh9rCzPJ20" title="coreySchafer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
    <td><iframe width="100%" height="100%" src="https://www.youtube.com/embed/ifTF3ags0XI" title="fireShip" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></td>
  </tr>
</table>
