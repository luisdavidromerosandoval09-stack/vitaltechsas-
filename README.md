[README.md](https://github.com/user-attachments/files/34480964/README.md)
# VitalTech S.A.S. · Plataforma web

> **Seguridad médica en un solo código.**

Sitio web corporativo de **VitalTech S.A.S.**, empresa de base tecnológica ubicada en el barrio Gran Britalia, localidad de Kennedy, Bogotá D.C. VitalTech desarrolla dispositivos con códigos **QR** y **NFC** que permiten acceder de forma rápida y segura a información médica autorizada por el usuario en situaciones de emergencia.

## Productos

| Producto | Precio unitario (año 1, COP) |
|---|---|
| Manilla con código QR | $10.000 |
| Tarjeta NFC | $15.000 |
| Kit básico para adulto mayor | $20.000 |
| Manilla escolar | $15.000 |
| Implante NFC (solución complementaria) | $200.000 |

Los precios provienen del modelo financiero del proyecto y están sujetos a confirmación comercial.

## Secciones del sitio

Inicio · Nosotros · Soluciones tecnológicas · ¿Cómo funciona? · Portafolio y cotización · Investigación de mercados · Innovación · Dashboard empresarial · Portal de clientes · Centro de contenidos · Alianzas · Contacto

Además incluye chatbot de preguntas frecuentes, buscador interno, tema claro/oscuro y diseño adaptable a computador, tablet y celular.

## Estructura del repositorio

```
├── index.html     # Sitio completo (HTML, CSS y JS en un solo archivo)
├── robots.txt
├── .nojekyll
├── .gitignore
└── README.md
```

## Cómo verlo

**Local:** abra `index.html` en el navegador. No requiere instalación.

**Vercel:**
1. Entre a [vercel.com/new](https://vercel.com/new) e importe este repositorio.
2. *Framework Preset*: **Other**. Sin comando de build ni carpeta de salida.
3. Pulse **Deploy**. Cada `git push` a `main` publica automáticamente.

**GitHub Pages:** *Settings → Pages → Deploy from a branch → `main` / root*.

## ⚠️ Alcance: es una demostración

- Los formularios, el registro, el inicio de sesión y el dashboard funcionan **solo en el navegador** (`localStorage`). No hay servidor ni base de datos.
- **No ingrese información médica real.**
- Acceso demo del dashboard: `admin@vitaltech.demo` / `Demo2026!`. En producción la validación debe hacerse en el servidor.
- Las cifras financieras son **proyecciones** del modelo del proyecto, no resultados históricos.
- Las metas (2.000 usuarios, 5 alianzas, 3 ciudades) son objetivos estratégicos, no logros.
- No se muestran aliados, integrantes del equipo ni datos de contacto (correo, WhatsApp, redes, horarios, dirección exacta) porque no están en los documentos fuente.

## Pendiente para producción

- Backend y base de datos cifrada para clientes y perfiles médicos.
- Autenticación y roles en servidor, HTTPS y copias de seguridad.
- Envío de correo, CRM e integración con WhatsApp.
- Datos de contacto reales y mapa.
- Política de privacidad y términos completos, conforme a la **Ley 1581 de 2012** (datos sensibles de salud).
- Sitemap, analítica web y Search Console.

## Aviso

Los dispositivos de VitalTech facilitan el acceso a información; **no sustituyen un diagnóstico médico ni los servicios de emergencia**. En una emergencia, llame al 123.

## Fuentes

- Proyecto productivo SENA, Tecnólogo en Gestión Empresarial, Ficha 3385498 (Sergio Andrés Castro Feliciano y Luis David Romero Sandoval).
- Modelo financiero MFIN Industrial VitalTech, 4-11-2026.

© 2026 VitalTech S.A.S.
