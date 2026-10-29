# Canal de la charte Rossini Energy

Fichiers publiés par le dépôt privé RossiniEnergyAI/rossini-erp : versions signées (Ed25519) de la charte et registre des domaines de l'ERP. Ne pas modifier à la main.

- v1/current.json : version courante du canal 1, signée.
- v1/versions/X.Y.Z.json : manifeste signé de chaque version, avec l'empreinte SHA-256 de ses fichiers.
- v1/X.Y.Z/tokens.css, v1/X.Y.Z/domains.json : fichiers immuables de chaque version.
- reference/ : page de référence de la coque.

Les applications lisent ce canal par leur relais (/_re/design/v1/), qui refuse toute version non signée par une clé connue.

