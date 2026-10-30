# Mercado cambiario

Datos públicos del Banco Central de Bolivia que usa la página «Mercado cambiario», actualizados una vez al día:

- [`bancos_bcb.json`](https://bohozx.github.io/Mercado-Cambiario/bancos_bcb.json): operaciones cambiarias por banco.
- [`paralelo_bcb.json`](https://bohozx.github.io/Mercado-Cambiario/paralelo_bcb.json): tipo de cambio paralelo del Informe de Política Monetaria.
- [`reservas.json`](https://bohozx.github.io/Mercado-Cambiario/reservas.json): reservas internacionales diarias, mensuales y anuales.

Las cifras salen de publicaciones del Banco Central de Bolivia. Las operaciones de los bancos se leen de [TCO-BCB](https://github.com/BohozX/TCO-BCB), que las baja del BCB a diario. Este repositorio solo contiene el workflow que actualiza los archivos; no guarda datos.
