# Salud Amazonas — Telemedicina Plug & Play

Landing comercial del sistema de telemedicina offline-first para las 4 RIS de Amazonas (Bagua, Chachapoyas, Condorcanqui, Utcubamba).

**Sitio en vivo:** https://enrilubo.github.io/salud-amazonas-landing/

## Qué incluye

- `index.html` — landing de una sola página (HTML5 + CSS3 + JS vanilla, sin frameworks).
- `ris_data.js` — datos reales de las 4 RIS de Amazonas (consumido por la landing).

## Características destacadas

- **Offline-first** — funciona en postas rurales sin internet; sincroniza cuando hay señal.
- **Equipos médicos Bluetooth plug-and-play** — cualquier dispositivo BLE estándar SIG (oxímetro, tensiómetro, termómetro, glucómetro, balanza, pulsómetro).
- **IA clínica + médico humano** — asistencia 24/7 con validación profesional.
- **100% Amazonas** — datos REUNIS/MINSA de las 4 RIS, 475 establecimientos.

## Servir localmente

```bash
python -m http.server 8090
# → http://localhost:8090/
```

O simplemente abre `index.html` con doble clic.

## Stack

- HTML5 + CSS3 + JavaScript vanilla (sin frameworks ni build).
- [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts).
- [Font Awesome 6](https://fontawesome.com/) (CDN).

## Contacto

Para solicitar una propuesta de inversión dirigida a GORE/DIRESA, usa el formulario de contacto en el sitio en vivo.
