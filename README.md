# xLauta7 — Portafolio de ciberseguridad

**Lautaro Poggi / xLauta7** — estudiante de Analista en Infraestructura Informática (ORT Uruguay) y certificado CompTIA Security+ (SY0-701).

Sitio personal estático (HTML/CSS/JS). Paleta oscuro / rojo / cian, sección de práctica y cuatro artículos basados en apuntes del **OEA Cyber Challenge Uruguay 2026**.

## Estructura

- `index.html` — portada, formación, experiencia, proyectos y contactos
- `styles.css` — estilos responsive y diseño editorial
- `script.js` — año del pie de página
- `blog/index.html` — índice de artículos
- `blog/informe-de-danos.html` — forense: firma ZIP en supuesto PDF
- `blog/notas-gemelas-filtradas.html` — cripto: reutilización XOR
- `blog/portal-regional-clearance.html` — web: NoSQL Injection en CTF
- `blog/senales-secretas-esp32.html` — reversing: ELF, punteros y Morse

## Publicación

**GitHub Pages:** Settings → Pages → Deploy from a branch → `main` + `/(root)`.

**Vercel:** New Project → importar `xlauta7/portfolio-web` → seleccionar **Other** como framework si se solicita → raíz `./` → sin build command ni output directory personalizada → Deploy. En Settings → Domains, intentar añadir `xlauta7.vercel.app` si el subdominio está disponible. Con el repositorio conectado, los commits en `main` activan despliegues automáticos.

## Transparencia

Los writeups derivan de un cuaderno de trabajo del evento CTF del 16 de octubre de 2026; algunos procedimientos se reconstruyeron después con ayuda de IA. Cada artículo distingue datos confirmados, hipótesis y pasos pendientes de reproducción autónoma. No se presentan como vulnerabilidades originales en producción.

## Herramientas y referencias

- GitHub: https://github.com/xlauta7
- TikTok: https://www.tiktok.com/@lauta_poggi
- LinkedIn: https://www.linkedin.com/in/lautaro-poggi-4075b335a

Las prácticas descritas corresponden a laboratorios/retos autorizados.
