# WPO Plugins Updates Channel

Canal de actualizaciones multi-sitio del plugin **WPO Toolkit Helper**.

Cada subcarpeta corresponde a un sitio:

```
{site-key}/
  info.json                 # metadata para WP plugin updater
  wpo-toolkit-{site}-vX.Y.Z.zip
```

Cada sitio WordPress consulta `raw.githubusercontent.com/.../{site}/info.json` cada 12h y se auto-actualiza si hay versión nueva.

Generado por wpo-toolkit (`node cli.mjs publish-plugin <site>`).
