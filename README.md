# app-downloads
Descargas públicas de las apps de escritorio de CuriaBots (Linux, Windows). Los binarios los publica `release-desktop-linux.yml` del repo [`client`](https://github.com/overmind-swarm/client) (Tauri) con nombres estables, para que la landing enlace `releases/latest/download/<nombre>`.

- Hasta octubre de 2026 publicaba aquí la app Flutter (`overmind-swarm/app`), retirada en dev#1590.
- `client` todavía no compila para Windows (dev#1586). Su release copia de la anterior los instaladores de Windows, que son de la última versión de Flutter, para que esos enlaces no den 404.
- `client` usa la última release de este repo como suelo de versión de sus builds.
