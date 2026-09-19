# Flujo de Pedido

Descripcion: Este documento describira el flujo de pedido desde un frontend externo hacia la API: el frontend envia peticiones HTTP, `TuMundoFeliz.Api` recibe los requests, `TuMundoFeliz.Application` ejecuta el caso de uso, `TuMundoFeliz.Domain` aplica las reglas del pedido y `TuMundoFeliz.Infrastructure` guarda o consulta los datos necesarios.

Flujo general:

`Frontend` -> `Endpoints REST` -> `UseCases` -> `Domain` -> `Ports` -> `Infrastructure` -> `Responses` -> `Frontend`

Swagger se usara para probar los endpoints antes de conectar el frontend real.
