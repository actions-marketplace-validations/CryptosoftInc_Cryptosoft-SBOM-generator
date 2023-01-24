# Cryptosoft-Nutrition-Label.

[![Website](https://img.shields.io/badge/https://-sbom.cryptosoft.com-blue.svg)](https://sbom.cryptosoft.com)



# GitHub action to generate a Nutrition label from SBOM

This GitHub action will create a a valid Software Bill-of-Materials (SBOM) containing an aggregate of all project dependencies and then its Nutrtion label.


## Inputs

### `path`

The path to a project, default is "./"

Be sure to quote paths with spaces.

### `output`

Output , default is web link

## Usage
uses: CryptosoftInc/Cryptosoft-Nutrition-label@master

## To use this action, add it to your workflow file like this:
on: push
jobs:
myJob:
runs-on: ubuntu-latest
steps:
- name: Cryptosoft-Nutrition-label
id: Cryptosoft-Nutrition-label
uses: CryptosoftInc/Cryptosoft-Nutrition-label@master
with:
<input_name_1>: <value>
<input_name_2>: <value>
## License

[MIT](LICENSE.md)

## Contributing

Suggestions are welcome!.
