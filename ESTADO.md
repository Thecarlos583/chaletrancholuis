# ESTADO de chaletrancholuis
Actualizado: 16-nov-2026. Contexto del negocio: `%USERPROFILE%\agencia-carlos\AGENTS.md` y `contexto\clientes.md`.

## Qué es
La web del cliente **Chalet Rancho Luis** (Colonia Tovar). Es la mejor página de la agencia y la vara a superar en cada web nueva. Acuerdos y pagos: solo en `agencia-carlos\contexto\clientes.md` (este repo es público).

## Cómo está hecho y cómo se publica
- Una sola página estática (`index.html`, `assets/`, `robots.txt`, `sitemap.xml`), sin build.
- Repo **público**, porque usa GitHub Pages gratis. El dominio propio está en `CNAME`: https://chaletrancholuis.com/
- Publicar: `git push` a `main`.
- La dirección vieja `thecarlos583.github.io/Paginas_webs/vista-previa/rancho-luis-pmfp/` redirige aquí (vive en el repo `Paginas_webs`).

## Terminado
- Web completa y dominio propio (13-oct-2026).
- Material de noviembre (16-nov-2026, etiqueta de respaldo `antes-material-noviembre`):
  - Restaurante: foto en la carta para los 5 platos (recortes de las historias de Instagram, `assets/img/plato-*.webp`). Los 5 ya estaban con el mismo precio.
  - Jardines: 4 fotos nuevas de primeras (escaleras de piedra, estanque redondo, entrada con letrero, terrazas con flores) y 2 videos (neblina y jardines con el chalet) en el mismo mosaico.
  - Habitaciones: bloque "Conozca las habitaciones" con 2 videos, sin nombre de habitación (el dueño no dijo cuál es cuál).
  - Videos con ahorro de datos: solo la imagen de portada.
- Cómo se edita: cambiar `CONFIG` en `index.html` y correr `hornear_web.py` (skill webs-carlos) para que el contenido quede escrito en el HTML.

## Pendientes, en orden de prioridad
1. Poner el botón de reservas de **Cupo** cuando salga (es el primer piloto). Lo hace Carlos como mantenimiento.
2. Mantener las fotos y los precios al día con el Sr. Luis.
3. Preguntarle de qué habitación es cada video nuevo (pasillo con piso de madera; paredes blancas y dos camas) para ponerles nombre.

## Archivos de referencia
Prompts en `agencia-carlos\claude\`: `prompt-claude-code-rancho-luis*.md`, `prompt-claude-code-cambios-rancho-luis.md`, `prompt-claude-code-publicar-rancho-luis.md` y `prompt_redireccion_chalet.md`.
