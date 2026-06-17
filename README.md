# Mondomío Kínder

Sitio principal de [Mondomío Kínder](https://mondomio.mx) — educación constructivista para niños de 1-4 años en San Pedro Garza García.

## 🌍 Características

- **Educación Constructivista**: Rotación de 8 áreas de aprendizaje
- **Actividades Especializadas**: Huerto, yoga y música especializada
- **Diseño Responsivo**: Funciona en todos los dispositivos
- **Sin Dependencias**: HTML estático, sin necesidad de build tools

## 📂 Estructura

```
inicio/
├── index.html              ← Sitio único (SPA)
└── assets/
    ├── fonts/              ← Tipografía Uniform (woff2)
    └── img/                ← Imágenes y logos
```

## 🚀 Despliegue

El sitio está desplegado en **Vercel** con dominio personalizado.

### Desplegar cambios localmente

```bash
cd inicio
python -m http.server 8000
# Abre http://localhost:8000
```

### Desplegar a producción

```bash
git add .
git commit -m "tu mensaje"
git push origin main
# Vercel despliega automáticamente
```

## 🎨 Personalización

### Colores

Edita las variables CSS en `inicio/index.html`:

```css
:root {
  --sky: #6CC9EC;         /* Azul cielo */
  --lime: #8CC63E;        /* Verde lima */
  --pink: #C0539F;        /* Rosa */
  --navy: #322B7A;        /* Azul marino */
  /* ... más colores */
}
```

### Contenido

Todo el contenido está en `inicio/index.html`. Los cambios de HTML se reflejan inmediatamente.

## 📝 Notas

- ✅ Funciona sin JavaScript habilitado (HTML/CSS puro)
- ✅ Optimizado para móvil y escritorio
- ✅ Fuentes preload para máxima velocidad
- ✅ Sin dependencias externas

## 📞 Contacto

- **Teléfono**: 81 8259 0721
- **Ubicación**: San Pedro Garza García, Nuevo León
