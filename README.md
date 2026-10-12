# keepanalog-resumidor

Corre el resumidor de [Keep Analog](https://www.keepanalog.com) cuando hay pedidos de resumen pendientes.

- `resumidor.mjs` se genera en el repositorio privado (`node infra/resumidor/build.mjs`). No se edita acá.
- El workflow `Resumir` corre por pedido y cada 5 minutos. No tiene disparadores por push ni por PR.
- No hay datos ni claves en este repositorio. Las credenciales están en los secretos de Actions.
