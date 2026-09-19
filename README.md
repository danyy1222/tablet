# Tu Mundo Feliz Tablet

Descripcion: Este proyecto sera una API REST para pedidos de tablet construida con .NET 10, C# y LINQ usando arquitectura hexagonal. El frontend sera externo y consumira endpoints para registrar pedidos para mesa o para llevar, consultar categorias y productos, administrar cantidades, calcular totales y generar una boleta electronica.

Estado actual: solo estructura de carpetas y archivos. No contiene logica implementada.

Estructura principal:

- `src/TuMundoFeliz.Domain`: nucleo del negocio.
- `src/TuMundoFeliz.Application`: casos de uso, DTOs y puertos.
- `src/TuMundoFeliz.Infrastructure`: adaptadores de salida como persistencia y repositorios.
- `src/TuMundoFeliz.Api`: adaptador de entrada REST, controladores, requests, responses, Swagger y configuracion inicial.
- `tests/TuMundoFeliz.Tests`: pruebas del sistema.
