# Sitio de Juan Camilo Espejo-Serna

Sitio estático en estilo Kandinsky: HTML y CSS, sin dependencias ni paso de compilación. El tema claro u oscuro sigue la preferencia del sistema de cada visitante.

## Estructura

```
.
├── index.html              Página principal (landing)
├── investigacion.html      Ver más: proyectos y líneas
├── publicaciones.html      Ver más: artículos, memorias y trabajos en revisión
├── ponencias.html          Ver más: ponencias 2016–2026
├── docencia.html           Ver más: trabajos de grado dirigidos
├── proyeccion-social.html  Ver más: talleres, conferencias y servicio
├── trayectoria.html        Ver más: formación, cargos, becas e idiomas
├── css/
│   └── style.css           Colores del tema claro y oscuro
├── images/
│   ├── me.jpeg             Foto
│   └── favicon.svg         Ícono del anillo con punto
├── .nojekyll               Evita que GitHub Pages procese el sitio con Jekyll
└── README.md
```

## Publicar en GitHub Pages

1. Copia todos los archivos a la raíz del repositorio `jcunisabana.github.io`. Si ya tienes un `index.html`, este lo reemplaza; guarda una copia antes si lo necesitas.
2. Haz commit y push a la rama principal:
   ```
   git add .
   git commit -m "Nuevo sitio en estilo Kandinsky"
   git push
   ```
3. En GitHub, ve a **Settings → Pages** y confirma que la fuente sea la rama principal y la carpeta `/ (root)`.
4. En uno o dos minutos el sitio queda en `https://jcunisabana.github.io/`.

Para publicarlo en otro repositorio, la dirección será `https://<usuario>.github.io/<repositorio>/`. Los enlaces son relativos, así que funcionan igual.

## Editar

- **Textos:** se editan directamente en cada `.html`.
- **Colores:** están en `css/style.css`. Los fondos oliva y las bandas oscuras de ponencias y del pie conservan sus colores en ambos temas.
- **Correo:** el pie de `index.html` todavía dice `[TU CORREO]`. Busca ese texto y reemplázalo.
