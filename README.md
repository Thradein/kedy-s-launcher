# kedy-s-launcher
Kedy's Launcher v2.2.0 Release Notes

[Security] Implemented strict post-download SHA-1 hash verification against remote Cloudflare R2 manifests to prevent corrupted payload injection.

[Security] Added Path Traversal prevention filters to secure local instance directories.

[Security] Local persistent session tokens (settings.json) are now obfuscated using machine-bound hardware identifiers (uuid.getnode()).

[UI/UX] Upgraded download progress interface with real-time transfer speed (MB/s) and accurate percentage indicators.

[Performance] Integrated optimized JVM garbage collection flags (G1GC tuning) to stabilize TPS and frame rates on heavy NeoForge modpacks.

[Quality of Life] Added direct log access (latest.log) and enhanced the automated repair routine for failed cache downloads.

Download link;
[Kedy's discord server](https://discord.gg/jq7rD7G4hc)
