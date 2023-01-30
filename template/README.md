# GitHub Action to setup Docker

![https://github.com/zmicro-design/action-setup-docker](https://img.shields.io/github/v/release/zmicro-design/action-setup-docker)
![https://github.com/zmicro-design/action-setup-docker](https://github.com/zmicro-design/action-setup-docker/workflows//Publish/badge.svg)

### Usage

| option | required | description |
| ------ | -------- | ----------- |

### Example

```yml
name: CI

on: [push]

jobs:
  build:
    name: Test
    runs-on: ubuntu-latest
    steps:
      - name: Setup Docker
        uses: zmicro-design/action-setup-docker@v1
```

### License

[MIT](./LICENSE)
