RapidPro Base Images
====================

**These images are built automatically by hub.docker.com**

A base image to build RapidPro on top of, installs heavier libraries like geos and gdal so each individual build doesn't have to.

Originally this was just tagged as `:latest` and built it for v3. With RapidPro v4 being released this was no longer adequate.

For RapidPro v3 builds use: `rapidpro/rapidpro-base:v3`

For RapidPro v4 builds use: `rapidpro/rapidpro-base:v4`

`rapidpro-base:latest` still points at v3 for backwards compatibility but consider it deprecated.
