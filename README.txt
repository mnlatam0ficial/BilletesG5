# CineProps MX — Instrucciones de Despliegue

## Estructura de archivos

```
cinepropsmx/
├── index.html          ← El sitio completo
└── textures/
    ├── 50.jpg          ← Foto del billete $50  (Serie Ajolotes)
    ├── 100.jpg         ← Foto del billete $100 (Serie Sor Juana)
    ├── 200.jpg         ← Foto del billete $200 (Serie Hidalgo)
    ├── 500.jpg         ← Foto del billete $500 (Serie Juárez)
    └── 1000.jpg        ← Foto del billete $1,000 (Serie Madero)
```

## Pasos para activar las texturas

1. **Agrega tus fotos** dentro de la carpeta `textures/`
2. **Nombra cada imagen exactamente así** (minúsculas, extensión .jpg):
   - `50.jpg`
   - `100.jpg`
   - `200.jpg`
   - `500.jpg`
   - `1000.jpg`
3. El código ya apunta a esas rutas — no necesitas cambiar nada más.

> 💡 Si tus fotos son .png o .webp, también funcionan:
> cambia la extensión en el CSS buscando `url('textures/50.jpg')` etc.

## Subir a Netlify (desde móvil)

1. Selecciona la carpeta `cinepropsmx/` completa y comprime en .zip
2. Abre tu navegador → https://app.netlify.com/drop
3. Arrastra o sube el .zip
4. ¡Listo! Netlify te da una URL pública en segundos

## Funciones incluidas en el sitio

- 🛒 **Carrito de compras** — agrega varios paquetes, controla cantidades
- ⚡ **Comprar directo** — abre WhatsApp con mensaje personalizado del producto
- 📱 **Carrito → WhatsApp** — genera mensaje completo con todos los paquetes seleccionados
- 🖼 **Texturas en tarjetas** — cada denominación muestra la foto real del billete
- 📲 **Responsive** — funciona en móvil y escritorio

## Tu número de WhatsApp configurado

`+52 1 222 546 0766`

Para cambiarlo: busca `WA_NUMBER` en el JS del index.html y reemplaza el valor.
