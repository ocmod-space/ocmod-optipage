# Change log

## [1.0.5] - 2024-02-28:
### Changed
- If the `alt` attribute is missing or empty, it will be assigned the name of the image file. If the `title` attribute is missing or empty, it will be assigned the `alt` attribute value.

## [1.0.4] - 2024-02-25:
### Changed
- If the `alt` attribute is missing, it will be assigned the name of the image file. If the `title` attribute is missing, it will be assigned the `alt` attribute value.

## [1.0.3] - 2024-01-31:
### Fixed
- `width` and `height` attributes will no add if appropriate style properties exist.
- Some image were not replaced with webp after converting image source paths to the relative type.

## [1.0.2] - 2024-01-17:
### Fixed
- Checking the availability of image files. while converting to webp.

## [1.0.1] - 2024-01-17:
### Internal
- Minor code improvements.

## [1.0.0] - 2024-01-14:
- First release.
