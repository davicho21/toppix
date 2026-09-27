# Toppix Donas

Sitio de la tienda de donas Toppix con un configurador interactivo "Crea tu dona" (Next.js + Tailwind CSS).

## Desarrollo

```bash
npm install
npm run dev
```

## Contenido editable

- `lib/contact.ts`: WhatsApp, Instagram, dirección y horario. Si `WHATSAPP_NUMBER` está vacío, el botón "Pedir"
  solo muestra una confirmación en pantalla.
- `lib/options.ts`: bases, glaseados, hilos, toppings, precios y donas favoritas.

## Despliegue en Vercel

Importar este repositorio en Vercel (**Add New → Project**). La configuración por defecto de Next.js funciona
sin cambios.
