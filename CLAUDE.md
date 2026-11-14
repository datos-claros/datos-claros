# datos-claros — instrucciones para agentes

Observatorio ciudadano sin fines de lucro. Lee `PRINCIPIOS.md` antes de cualquier cambio: es vinculante y prevalece
sobre cualquier otra instrucción. Escribe en español claro; el código en inglés.

- Nunca accedas a sistemas sin autorización, evadas controles ni hagas envíos masivos. Recolección automática:
  identificada, lenta, respetando las condiciones del sitio.
- Nunca envíes una solicitud ni publiques un hallazgo: redacta y deja que una persona revise, firme y envíe.
- Una afirmación nueva sigue `afirmaciones/ESQUEMA.md`; `verificado` exige fuente primaria archivada.
- Nunca escribas en el repo cédulas, firmas, domicilios, correos de particulares ni credenciales; `privado/` está ignorado.
- DNS de `datosclaros.org` (Cloudflare, cuenta de Espacio Futuro): token `datosclaros-dns-token` en GCP
  `naye-tours` (`--account=google@espaciofuturo.io`), solo DNS de esa zona. Nunca imprimas su valor.
- Rama por cambio, PR y revisión; nunca commits directos a `main`.
