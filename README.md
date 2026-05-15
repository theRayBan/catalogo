# 🕶️ Catálogo de Gafas Ray-Ban

Una web moderna y responsiva para mostrar tu catálogo de gafas Ray-Ban con filtros por categoría.

## 📁 Archivos del proyecto

- **index.html** - Estructura HTML principal
- **styles.css** - Estilos y diseño responsivo
- **script.js** - Funcionalidad de filtros
- **data.js** - Base de datos de productos

## 🚀 Cómo usar

### 1. Editar productos
Abre el archivo `data.js` y modifica el array `glassesData` con tus gafas:

```javascript
{
    id: 1,
    name: "Nombre del modelo",
    category: "aviador|wayfarer|clubmaster|otro",
    price: "$XXX.XX",
    image: "URL de la imagen",
    description: "Descripción del producto"
}
```

### 2. Agregar imágenes
Puedes usar:
- **URLs externas** - Cualquier URL de imagen (ejemplo: Unsplash, tu servidor, etc.)
- **Imágenes locales** - Crea una carpeta `images/` y sube tus fotos

Ejemplo con imagen local:
```javascript
image: "images/aviator-classic.jpg"
```

### 3. Personalizar categorías
Las categorías disponibles son:
- `aviador`
- `wayfarer`
- `clubmaster`
- `otro`

Puedes agregar más categorías editando también los botones en `index.html`.

## 📱 Características

✅ Diseño responsivo (móvil, tablet, desktop)
✅ Filtros por categoría funcionales
✅ Animaciones suaves
✅ Grid automático de productos
✅ Fácil de personalizar

## 🌐 Publicar con GitHub Pages

1. Ve a **Settings** → **Pages**
2. Selecciona **main branch** como fuente
3. ¡Tu web estará en: `https://therayban.github.io/catalogo`

## 🎨 Personalización

### Cambiar colores
En `styles.css`, busca y edita:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
/* Cambia a tus colores favoritos */
```

### Cambiar fuente
Edita en `styles.css`:
```css
font-family: 'Tu fuente', sans-serif;
```

### Agregar más información
En `data.js`, agrega campos adicionales como:
```javascript
{
    id: 1,
    name: "...",
    category: "...",
    price: "...",
    image: "...",
    description: "...",
    stock: "En stock",
    material: "Metal",
    color: "Negro"
}
```

Luego actualiza `script.js` para mostrar esos campos.

## 💡 Tips

- Usa imágenes de buena calidad (al menos 400x300px)
- Mantén descripciones cortas y atractivas
- Actualiza los precios regularmente en `data.js`
- Prueba en móvil antes de publicar

## 📧 Soporte

¿Necesitas ayuda? Edita el archivo y actualiza el contenido según tus necesidades.

---

**Versión**: 1.0  
**Última actualización**: 2026-05-15
