# Esquema de una afirmación

Un archivo YAML por caso; una entrada por afirmación.

```yaml
- id: hb-001                     # prefijo del caso + número; nunca se reutiliza
  afirmacion: "Texto exacto, con número y unidad."
  estado: verificado             # verificado | reportado | sin-verificar | refutado | informacion-negada
  fuentes:
    - url: https://…
      tipo: primaria             # primaria (documento oficial) | secundaria (prensa, opinión)
      consultado: 2026-11-14
      archivo: https://web.archive.org/…   # copia archivada
  respuesta_institucion: null    # su versión, cuando se pidió (principio 4)
  notas: "Por qué tiene este estado; qué falta para verificarla."
```

- `verificado`: lo confirma una fuente primaria.
- `reportado`: lo publica prensa o una autoridad citando datos oficiales, pero falta el documento.
- `sin-verificar`: viene de opinión o de una sola fuente sin respaldo.
- `refutado`: una fuente primaria lo contradice. Se conserva visible.
- `informacion-negada`: se pidió por vía legal y no se entregó, o vencieron los plazos.
