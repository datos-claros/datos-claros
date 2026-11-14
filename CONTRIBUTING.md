# Cómo participar

Toda contribución respeta la [carta de principios](PRINCIPIOS.md). Un cambio que la incumpla se rechaza,
aunque su conclusión sea correcta.

## Agregar o cambiar una afirmación

1. Edita el archivo del caso en `afirmaciones/` siguiendo `afirmaciones/ESQUEMA.md`.
2. Cada afirmación necesita al menos una fuente con URL y fecha de consulta. Para `verificado` hace falta una
   **fuente primaria** (documento oficial, SICOP, Gaceta, CGR, respuesta de la institución).
3. Archiva la fuente: guarda la página en https://web.archive.org y anota el enlace en `archivo`.
4. Abre un pull request. Una segunda persona revisa la fuente antes de fusionar.

## Escribir

- Hechos con número y fuente; sin adjetivos que acusen («estafa», «corrupto»).
- Español claro, que entienda una persona joven o adulta sin formación técnica.

## Lo que nunca entra al repositorio

Cédulas, firmas, domicilios, teléfonos o correos de particulares; documentos sin tachar; credenciales o
tokens. Las solicitudes firmadas se guardan fuera del repo (`privado/` está ignorado).

## Commits

Firma tus commits (`git commit -S`). Ninguna rama se fusiona sin revisión.
