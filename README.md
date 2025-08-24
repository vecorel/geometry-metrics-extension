# Geometry Metrics Extension Specification

- **Title:** Geometry Metrics
- **Identifier:** <https://vecorel.org/geometry-metrics-extension/v0.1.0/schema.yaml>
- **Property Name Prefix:** metrics
- **Extension Maturity Classification:** Proposal
- **Owner**: @cholmes @geospatial-jeff @m-mohr

This document explains the Geometry Metrics Extension to the
[Vecorel specification](https://github.com/vecorel/specification).

The extension defines standardized properties for representing geometric measurements, such as area and perimeter.

- Examples:
  - [GeoJSON](examples/geojson/)
  - [GeoParquet](examples/geoparquet/)
- [Schema](schema/schema.yaml)
- [Changelog](./CHANGELOG.md)

## Properties

| Property Name     | Type  | Description |
| ----------------- | ----- | ----------- |
| metrics:area      | float | Area of the field, in square meters (m²). Must be > 0. |
| metrics:perimeter | float | Perimeter of the field, in meters (m). Must be > 0. |

## Contributing

See the [contributing guideline](CONTRIBUTING.md) for more details.
