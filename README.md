# Showcase — Auditoría rápida con IA (Cursor)

Auditoría sencilla en **5 minutos** para probar a crear con IA usando **Cursor** y un proyecto real.

## Qué es este proyecto

Este repositorio es un **showcase** de módulos de estilo (colores, tipografía, espaciado y componentes) generado y mantenido con ayuda de Cursor. Sirve como:

- **Prueba de concepto**: ver qué se puede hacer en poco tiempo con IA + un proyecto real.
- **Documentación visual**: paleta, tipografía y espaciado del design system en una sola web.
- **Base para GitHub Pages**: todo el contenido es estático y se puede publicar en segundos.

## Contenido

| Página        | Descripción                          |
|--------------|--------------------------------------|
| [Showcase](index.html)   | Resumen: colores, botones y tarjetas |
| [Colores](colors.html)   | Paleta completa con pestañas         |
| [Tipografía](typography.html) | Estilos de texto                  |
| [Spacing](spacing.html) | Escala de espaciado                  |

## Cómo publicar en GitHub Pages

1. Sube el repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**.
4. Branch: `main`, carpeta: **/ (root)**.
5. Guarda. En unos segundos la URL será:  
   `https://<tu-usuario>.github.io/<nombre-repo>/`

La página de entrada será `index.html` (showcase principal). También existe **`pages.html`** como página de bienvenida/resumen para GitHub Pages, con enlaces al showcase y al resto de páginas.

## Tecnologías

- HTML y CSS en línea (sin build).
- Sin dependencias: solo abrir los `.html` en el navegador o servirlos en cualquier host estático.

## Uso con Cursor

Este proyecto se ha usado para probar:

- Generar y enlazar páginas de showcase a partir de reglas y convenciones.
- Mantener coherencia de estilos (variables CSS, nombres de clases).
- Crear documentación y README desde cero con instrucciones claras.

Ideal para una **auditoría rápida de 5 minutos**: ver qué puede hacer la IA con un proyecto real y publicar el resultado en GitHub Pages sin configuración extra.
