# Datos claros

**Cuentas claras.** Un observatorio ciudadano, abierto y sin fines de lucro, que usa datos públicos e
inteligencia artificial para que cualquier persona pueda pedir cuentas a quien ejerce poder público, por
las vías que la ley ya le da.

> «Los funcionarios públicos son simples depositarios de la autoridad. […] La Administración Pública en
> sentido amplio, estará sometida a un procedimiento de evaluación de resultados y rendición de cuentas.»
> — Constitución Política de Costa Rica, artículo 11

Sitio: https://datosclaros.org

## Qué hace

1. **Pide información** pública con las herramientas que la Constitución da a toda persona (art. 27 petición,
   art. 30 acceso a la información) y lleva la cuenta de cada plazo.
2. **Archiva** cada documento público con fecha y huella (hash), para que lo que se publica no desaparezca.
3. **Verifica** cada afirmación contra su fuente primaria y le asigna un estado (ver `afirmaciones/`).
4. **Publica** solo lo verificado, con el método y los datos para que cualquiera lo reproduzca.
5. **Mide la opacidad**: solicitudes sin respuesta, respuestas tardías, información negada, documentos retirados.

## Cómo trabaja

Todo lo rige la [carta de principios](PRINCIPIOS.md): solo vías legales, hechos y no adjetivos, derecho de
respuesta, sin partido. La IA redacta, busca y calcula; **una persona revisa, firma y envía**.

## Primer caso

**Hello Brete** (INA + Open English, 2026): qué se paga, qué se usa y qué se aprende.
Afirmaciones en [`afirmaciones/hello-brete.yaml`](afirmaciones/hello-brete.yaml); solicitudes en
[`solicitudes/`](solicitudes/).

## Estructura

| Carpeta | Contenido |
|---|---|
| `afirmaciones/` | Registro de afirmaciones: texto, fuentes, estado |
| `solicitudes/` | Plantillas de solicitudes y su seguimiento (sin datos personales) |
| `datos/` | Datos públicos y respuestas oficiales, con fuente y hash |
| `analisis/` | Cálculos reproducibles |

## Participar

Lee [CONTRIBUTING.md](CONTRIBUTING.md). Se necesitan personas de derecho, estadística, periodismo e ingeniería.

## Licencia

Código: MIT. Datos y textos: CC BY 4.0. Ver [LICENSE](LICENSE).
