# Lingora CLI GitHub Action

This action downloads the **appropriate prebuilt `lingora-cli` binary** for the current GitHub Actions runner (Linux, macOS, or Windows) and executes it.

Site [lingora](https://nigeleke.github.io/lingora) 
Site [github](https://github.com/nigeleke/lingora) 

```yml
jobs:
  lingora:
    runs-on: ubuntu-latest
    steps:
      - uses: nigeleke/github/.github/actions/lingora-cli@latest
        with:
          args: "--config=./Lingora.toml"
```
