# XXRI Store Schema

## File
i686.json

## Root

{
  "schema_version": "...",
  "last_updated": "...",
  "applications": [...]
}

## Application Object

{
  "id": "",
  "title": "",
  "description": "",
  "category": "",
  "priority_tier": 1,
  "research_status": "",
  "homepage": "",
  "icon_url": "",
  "download_url": "",
  "checksum": "",
  "size": 0,
  "architecture": "i686",
  "package_type": "",
  "dependencies": [],
  "tags": [],
  "sources": [],
  "verified": false,
  "tested_install": false,
  "tested_launch": false
}

## Priority

1 = Official AppImage
2 = Official portable archive
3 = Official installer
4 = Tiny Core package
5 = Community package
6 = Source only

## Rules

- Never remove existing entries.
- Never fabricate URLs.
- Never use Wikipedia as evidence.
- Preserve schema compatibility.
- Only append or improve entries.
- Every source must be official whenever possible.
