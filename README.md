# Cryptosoft

[![Website](https://img.shields.io/badge/https://-www.cryptosoft.com-blue.svg)](https://www.cryptosoft.com/)



# GitHub action to upload SBOM to OWASP Dependency Track

This GitHub action will create a a valid Software Bill-of-Materials (SBOM) containing an aggregate of all project dependencies and then will upload to OWASP DT TRACK.


## Inputs
Dependency Track Url an It's API_KEY

### `output`
Output , default is token when SBOM is successfully Uploaded to OWASP DT TRACK.

## Usage
```
uses: CryptosoftInc/Cryptosoft-SBOM-generator@1.0.0
```
## To use this action, paste below file file in your project directory wirh .github/workflows/<Name of the File>.yaml:

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
        dturl: <your dt url>
        api-key: DT Instance api key
```
## Contribution

Suggestions are welcome!.
