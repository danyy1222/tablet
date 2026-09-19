# Arquitectura

Descripcion: Este documento explicara la arquitectura hexagonal del proyecto. El nucleo sera `TuMundoFeliz.Domain`, los casos de uso estaran en `TuMundoFeliz.Application`, los adaptadores externos en `TuMundoFeliz.Infrastructure` y la entrada HTTP REST en `TuMundoFeliz.Api`. El frontend sera externo y se comunicara con la API mediante endpoints probados con Swagger.

Orden de dependencias esperado:

`Frontend externo` -> `TuMundoFeliz.Api` -> `TuMundoFeliz.Application` -> `TuMundoFeliz.Domain`

`TuMundoFeliz.Infrastructure` -> `TuMundoFeliz.Application` y `TuMundoFeliz.Domain`

Regla central: `TuMundoFeliz.Domain` no debe depender de ningun otro proyecto.
