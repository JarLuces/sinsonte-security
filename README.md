# Estado público de seguridad de Sinsonte

Este repositorio publica evidencias y el dashboard estático de seguridad de
Sinsonte Suite mediante GitHub Pages.

La fuente canónica del generador es
[`JarLuces/infraestructura-sinsonte`](https://github.com/JarLuces/infraestructura-sinsonte),
en `.github/workflows/security-status-page.yml`. Los ficheros generados de este
repositorio pueden ser reemplazados por ese workflow.

`backup-status.json` describe la configuración declarada de Cloud SQL y PITR.
No certifica por sí solo que se haya ejecutado con éxito una restauración.
