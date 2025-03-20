# Geometry Metrics Extension Specification

- **Title:** Geometry Metrics
- **Identifier:** <https://vecorel.github.io/geometry-metrics/v0.1.0/schema.yaml>
- **Property Name Prefix:** metrics:
- **Extension Maturity Classification:** Proposal/Candidate/Stable
- **Owner**: @cholmes @geospatial-jeff

This document explains the Geometry Metrics Extension to the
[Vecorel Specification](https://github.com/vecorel/specification).

This is the place to add a short introduction.

- Examples:
  - [GeoJSON](examples/geojson/)
  - [GeoParquet](examples/geoparquet/)
- [Schema](schema/schema.yaml)
- [Changelog](./CHANGELOG.md)

## Properties

The properties in the table below can be used in these parts of Vecorel documents:

- [ ] Collection
- [x] Feature Properties

| Property Name   | Type   | Description |
| --------------- | ------ | ----------- |
| metrics:area    | float  | Area of the polygon |
| metrics:perimeter | float | Perimeter of the polygon |
| metrics:width | float |  |
| metrics:height | float | |
| metrics:micd | float | The Circumference-Area ratio (CA ratio) is calculated by dividing the circumference of a given polygon by the square root of its area. This ratio is then adjusted so that a circle corresponds to 0, and scaled so that a square corresponds to 1 | 
| metrics:ca_ratio | float | | 

## Contributing

See the [contributing guideline](CONTRIBUTING.md) for more details.
