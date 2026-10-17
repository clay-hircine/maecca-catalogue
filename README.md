# Maecca catalogue shards

Static, content-addressed catalogue files for the Maecca app, published as release assets
(`music-<version>.tar`, `media-<version>.tar`). The app's server image downloads them at build
time and serves them at `/catalogue/<set>/`; nothing else uses this repository.

Each tar holds `manifest.json`, `core.json.gz` and `files/**` (format `maecca-shards/1`).

Licences:
- Genres from English Wikipedia infoboxes and categories (CC BY-SA 4.0, https://en.wikipedia.org).
- Items, links and ids from Wikidata (CC0 1.0) and MusicBrainz (CC0 1.0).
- Popularity from ListenBrainz (CC0 1.0) and Wikimedia page views (CC0 1.0).
