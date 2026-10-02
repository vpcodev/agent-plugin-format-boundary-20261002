# Plugin format boundary fixture

**Test-only.** This repository has one valid portable plugin and one package
with intentionally malformed manifest JSON. Neither package contains
executable files, network destinations, or real user data.

The marketplace index itself is valid. The malformed package is meant to
exercise a safe import rejection while leaving the unrelated valid package
discoverable. Do not use the malformed package as a real plugin.
