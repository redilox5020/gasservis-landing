# Logos de Clientes - GASSERVIS

Esta carpeta contiene los logos de las empresas aliadas que aparecen en la sección "Confían en Nosotros".

## Cómo reemplazar los logos placeholder

Cada archivo SVG actual es un placeholder que muestra el nombre de la empresa. Para reemplazarlo con el logo real:

### Paso 1: Obtener el logo
Busca el logo oficial de cada empresa. Los mejores formatos son:
- **SVG** (recomendado - mejor calidad y escalabilidad)
- **PNG** con fondo transparente
- **WEBP** con fondo transparente

### Paso 2: Preparar el logo
- Tamaño recomendado: **200x80 píxeles** o proporcional
- Asegúrate de que el fondo sea **transparente**
- Nombres de archivo deben ser exactamente como se indican abajo

### Paso 3: Reemplazar el archivo
Simplemente reemplaza el archivo en esta carpeta con el logo real, manteniendo el mismo nombre.

## Lista de archivos a reemplazar

| Archivo | Empresa |
|---------|---------|
| `ecopetrol.svg` | ECOPETROL |
| `perenco.svg` | PERENCO |
| `hocol.svg` | HOCOL |
| `geopark.svg` | GEOPARK |
| `parex.svg` | PAREX |
| `gases-occidente.svg` | Gases de Occidente |
| `alcanos.svg` | ALCANOS |
| `drummond.svg` | DRUMMOND |
| `llanogas.svg` | LLANOGAS |

## Notas importantes

1. Si usas un formato diferente a SVG (por ejemplo PNG), cambia la extensión en el archivo `src/App.tsx` en la sección `ClientsSection`:

```javascript
const clients = [
  { name: "ECOPETROL", logo: "/logos/ecopetrol.png" }, // Cambiar .svg por .png
  // ... resto de logos
];
```

2. Para agregar más empresas, simplemente:
   - Añade el archivo del logo a esta carpeta
   - Agrega un nuevo objeto al array `clients` en `src/App.tsx`

## Recursos para encontrar logos

- [Brandsoftheworld.com](https://www.brandsoftheworld.com/) - Logos vectoriales
- [Worldvectorlogo.com](https://worldvectorlogo.com/) - Logos SVG
- [Seeklogo.com](https://seeklogo.com/) - Base de datos de logos
- Páginas oficiales de las empresas (sección de prensa/recursos)
