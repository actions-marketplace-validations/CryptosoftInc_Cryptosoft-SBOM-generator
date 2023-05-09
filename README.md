# Cryptosoft-action.

[![Website](https://img.shields.io/badge/https://-www.cryptosoft.com-blue.svg)](https://www.cryptosoft.com/)



# GitHub action to upload SBOM to OWASP Dependency Track

This GitHub action will create a a valid Software Bill-of-Materials (SBOM) containing an aggregate of all project dependencies and then will upload to OWASP DT TRACK.

## Inputs
root directory

### `output`
Output , default is token

## Usage
```
uses: CryptosoftInc/Cryptosoft-SBOM-generator@1.0.0
```
## To use this action, add it to your workflow file like this:

```
on: push
jobs:
  myJob:
    runs-on: ubuntu-latest
    steps:
    - name:Cryptosoft-SBOM-generator
      id: Cryptosoft-SBOM-generator
      uses: CryptosoftInc/Cryptosoft-SBOM-generator@1.0.0
      with:
        dturl: '<your dt url>'

```
## Contributing

Suggestions are welcome!.
