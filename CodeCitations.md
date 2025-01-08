# Code Citations

## License: 未知
https://github.com/Looterro/Movie_Tinder/tree/e34ee6922df3a9b2b64e82bc0c0ba7d8c2f85ace/.github/workflows/main.yml

```
CI

    on:
      push:
        branches:
          - master
      pull_request:
        branches:
          - master

    jobs:
      build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
          uses: actions/checkout@v2

        - name: Set up Node.js
          uses: actions/setup-node
```


## License: 未知
https://github.com/perlak99/filmReviewWeb/tree/7fcebbcedf908821cfe11aad5506da7613cd83de/.github/workflows/main.yml

```
:
      push:
        branches:
          - master
      pull_request:
        branches:
          - master

    jobs:
      build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
          uses: actions/checkout@v2

        - name: Set up Node.js
          uses: actions/setup-node@v2
```


## License: 未知
https://github.com/tomeshnet/mesh-packages/tree/5257f434cfefdf90d78382eef9d039f196447a42/.github/workflows/main.yml

```
:
        branches:
          - master

    jobs:
      build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
          uses: actions/checkout@v2

        - name: Set up Node.js
          uses: actions/setup-node@v2
          with:
            node-version: '14
```


## License: 未知
https://github.com/soloveiiko/bubu-store/tree/061babd1e674b8264a1071fd1c3afb8e98f16c3c/.github/workflows/build-css.yml

```
:
      build:
        runs-on: ubuntu-latest

        steps:
        - name: Checkout code
          uses: actions/checkout@v2

        - name: Set up Node.js
          uses: actions/setup-node@v2
          with:
            node-version: '14'

        - name: Install dependencies
```


## License: 未知
https://github.com/TcharlesDaviLassen/exemplo_CI_CD/tree/054e081754bfef72f6dddbe4ceed342b03c56e1c/readme.md

```
Checkout code
          uses: actions/checkout@v2

        - name: Set up Node.js
          uses: actions/setup-node@v2
          with:
            node-version: '14'

        - name: Install dependencies
          run: npm install

        - name: Run tests
          run: npm test
    ``
```

