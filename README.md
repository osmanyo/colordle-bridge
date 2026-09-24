# colordle-bridge

Tiny helper page for moving Colordle players' saved games from the old address
(`osmanyo.github.io/colordle`) to the new domain. It reads the old browser storage
(same origin as the old game), and sends the player to the new domain with the data
in the URL fragment (`#migrate=...`), which is never sent to any server.
