# 👟 ZAPATOS.LAB | Premium Streetwear E-commerce

![Version](https://img.shields.io/badge/Version-1.0.0-ff0055?style=for-the-badge)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_Integration-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

**ZAPATOS.LAB** es un prototipo de e-commerce de alta gama diseñado para la cultura del calzado urbano. Este proyecto fusiona una estética agresiva y moderna con una funcionalidad de venta directa optimizada para mercados emergentes mediante la integración de la API de WhatsApp.

---

## ✨ Características Principales

- 🚀 **UI/UX Premium**: Diseño orientado a la conversión con animaciones de entrada (Scroll Reveal), cursores personalizados y efectos de cristal (Glassmorphism).
- 🛒 **Shopping Experience**: Sistema de carrito dinámico con selección de tallas, control de cantidades y persistencia de estado en tiempo real.
- 📱 **WhatsApp Checkout**: Generación de mensajes personalizados automáticos que incluyen detalles del producto, tallas y total para cerrar la venta directamente con el vendedor.
- ⚡ **Zero-Build Architecture**: Desarrollado para ser ligero y compatible, utilizando React y Tailwind vía CDN, eliminando la fricción de instalaciones complejas de `node_modules`.
- 🔍 **Filtrado Dinámico**: Sistema de navegación por categorías (Performance, Cyberpunk, Streetwear, Premium).

## 🛠️ Tech Stack

- **Frontend**: React.js (Hooks & Context API)
- **Styling**: Tailwind CSS (JIT Engine)
- **Icons**: Lucide Icons
- **Typography**: Space Grotesk & Plus Jakarta Sans
- **Backend/Checkout**: WhatsApp Business API Integration

## 📸 Preview Estético

El sitio maneja un lenguaje visual de "Modo Oscuro" con acentos en **Viva Magenta (#ff0055)**, inspirado en las marcas líderes de streetwear como Nike (SNKRS), Adidas (Confirmed) y StockX.

## 🚀 Instalación y Uso Local

Este proyecto ha sido estructurado para ser extremadamente fácil de desplegar sin dependencias pesadas.

1.  **Clona el repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/web_zapatos.git
    cd web_zapatos
    ```

2.  **Lanza un servidor local** (Recomendado para manejar las rutas de imágenes y scripts):
    ```bash
    # Usando Python
    python3 -m http.server 8000
    ```

3.  **Abre tu navegador**:
    Navega a `http://localhost:8000`

## 📧 Contacto e Integración

El botón de compra está vinculado actualmente al número de soporte del desarrollador. Para producción, simplemente cambia la constante `WHATSAPP_NUMBER` en el archivo `index.html`.

---
