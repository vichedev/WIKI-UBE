# Wiki · Medios de Diagnóstico

Sitio web tipo wiki hecho con **HTML + Tailwind CSS (vía CDN)**. No necesita instalación ni internet para el diseño base más allá de cargar el CDN.

## ▶️ Cómo ver la web
Haz doble clic en **`index.html`** y se abrirá en tu navegador. Desde ahí navegas con la barra lateral.
> Nota: necesitas conexión a internet para que cargue el estilo (Tailwind se carga desde su CDN).

## 📄 Páginas actuales
| Archivo | Contenido |
|---|---|
| `index.html` | Carátula (universidad, integrantes, curso, docente) |
| `introduccion.html` | Introducción a los medios de diagnóstico |
| `examenes.html` | Listado/esquema de los exámenes |
| `hemograma.html` | Hemograma con diferencial |
| `frotis.html` | Frotis |
| `neurograma.html` | Neurograma |
| `enlaces.html` | Enlaces y referencias |
| `_plantilla.html` | Plantilla para crear nuevas páginas |

## ➕ Cómo agregar una página nueva (a futuro)
1. **Copia** el archivo `_plantilla.html` y renómbralo, por ejemplo `glucosa.html`.
2. Abre el nuevo archivo y cambia el `<title>` y el contenido dentro de `<main>`.
3. Para que aparezca en el menú, **agrega una línea de enlace** dentro de la barra lateral
   (`<nav>`). Copia este formato:
   ```html
   <a href="glucosa.html" class="block rounded-lg px-3 py-2 text-slate-600 hover:bg-slate-100">🧫 Glucosa</a>
   ```
   Pégala en las páginas donde quieras que aparezca el menú actualizado (lo ideal es en todas,
   para mantener la navegación igual).

## 🎨 Personalizar
- **Colores:** cambia las clases de Tailwind, por ejemplo `bg-indigo-600` por `bg-emerald-600`.
- **Texto:** edita directamente el contenido entre las etiquetas HTML.
- **Imágenes/mapas:** dentro de `<main>` puedes agregar `<img src="mi-imagen.png" class="rounded-xl">`.
  Coloca la imagen en esta misma carpeta.

---
Proyecto académico · Universidad Bolivariana del Ecuador · Materia: Medios de Diagnóstico · Curso UEPD-04
