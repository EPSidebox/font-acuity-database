# Font Visual Acuity Database

Community-contributed database of font visual acuity measurements based on the protocol described in *About Visual Acuity and Type Design: A Protocol* by [Ernesto Peña](https://ernestopena.com).

## About

This database contains measurements of minimum visible units (1μ) and relative acuity values for various typefaces, calculated using the Font Visual Acuity Analyzer.

## Data Structure

Each font entry contains:
- **Hash**: SHA-256 identifier of the font file
- **Font metadata**: Name, style, version, designer, manufacturer
- **1μ (Minimum visible unit)**: Smallest structural measurement in font units
- **Character**: The character containing the minimum measurement
- **Source**: Type of measurement (stroke width, counter size, or geometric feature)
- **X-height**: Height of lowercase x in font units
- **Relative Acuity**: Ratio of x-height to 1μ
- **Distribution**: Statistical distribution of all measurements

## Contributing

Contributions welcome! Use the [Font Visual Acuity Analyzer](https://ernestopena.com) to analyze fonts and submit your results. Submissions create pull requests that will be reviewed before merging.

## License

[CC0 1.0 Universal](LICENSE) - Public Domain
