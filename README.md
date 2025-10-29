# Opunnence Frontend

Sitio web estático para **Opunnence**, agencia de ingeniería de reputación online.

## 🛠 Estructura

Proyecto desarrollado en HTML, CSS y JS plano, sin frameworks.

```
├── index.html # Página principal
├── styles.css # Estilos principales
├── opunnence_logo_sin_fondo.png # Logotipo
```

## 🌐 Deploy

Deploy automático con **Render.com**  
URL de producción: [www.opunnence.com](https://www.opunnence.com)

### Configuración de Render

- **Tipo:** Static Site
- **Build Command:** *(vacío)*
- **Publish Directory:** `.`
- **Custom Domains:**
  - `www.opunnence.com`
  - `opunnence.com` (redirige a `www`)

### Configuración DNS (en Axarnet)

| Tipo  | Host | Valor                                  |
|-------|------|-----------------------------------------|
| A     | `@`  | `216.24.57.1`                           |
| CNAME | `www`| `opunnence-frontend.onrender.com.`      |

## 📡 API (Backend)

El backend vive en: [https://api.opunnence.com](https://api.opunnence.com)  
Toda integración con la API se hará vía fetch desde el frontend.

---

## ✍ Autor

Fernando Calderan • [linkedin.com/in/fernandocalderan](https://linkedin.com/in/fernandocalderan)

---
