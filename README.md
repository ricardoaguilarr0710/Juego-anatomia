# Simulador de Anatomía para Enfermería

Sitio web educativo e interactivo para practicar la identificación de estructuras del sistema óseo humano.

## Funciones

- Mapa interactivo del esqueleto en vista anterior.
- Niveles básico, intermedio y avanzado.
- Modo estudio con pistas y explicaciones anatómicas.
- Modo examen con cronómetro y evaluación.
- Puntuación, progreso y resultado final.
- Diseño adaptable a computadoras, tabletas y celulares.

## Verlo en tu computadora

1. Descarga o clona este repositorio.
2. Abre la carpeta en Visual Studio Code.
3. Abre `index.html` en tu navegador.

No requiere instalación de dependencias, Node.js ni servidor backend.

## Publicarlo gratis con GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `anatomia-enfermeria`.
2. Sube todos los archivos y carpetas de este proyecto, conservando esta estructura:

   ```text
   anatomia-enfermeria/
   ├── index.html
   ├── README.md
   ├── .nojekyll
   └── assets/
       └── esqueleto.png
   ```

3. En GitHub, entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Presiona **Save**. GitHub generará la dirección pública del sitio en unos minutos.

## Personalización

- La ilustración está en `assets/esqueleto.png`.
- La estructura, los estilos y la lógica del juego están en `index.html`.
- Los nombres y explicaciones anatómicas se encuentran en el objeto `bank` dentro del JavaScript.
- Los marcadores se posicionan mediante porcentajes (`left` y `top`) en los botones `.marker` de `index.html`.

## Nota académica

Los marcadores son aproximados y deben revisarse y ajustarse con un atlas anatómico confiable antes de usar el recurso como evaluación formal. Este proyecto es material educativo de apoyo y no sustituye bibliografía, enseñanza ni evaluación docente.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Revisa `LICENSE`.
