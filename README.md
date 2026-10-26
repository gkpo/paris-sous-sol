# Paris Sous-Sol

Le métro et le RER de Paris en 3D, à l'échelle réelle, avec les trains en direct.
Une seule page statique (`index.html`) : aucune compilation, aucune dépendance à installer.

Les trains en direct viennent de `https://paris-metro-relay.gkpo.workers.dev/live`
(un Cloudflare Worker qui interroge l'API PRIM d'Île-de-France Mobilités ; la clé reste côté Worker).

Données : Île-de-France Mobilités, RATP (open data), OpenStreetMap, Wikipédia.
