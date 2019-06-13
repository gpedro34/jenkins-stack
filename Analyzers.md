sonarcloud.io - cloud - free for public projects -
codacy.com
codecov.io
sonarqube.org - Local

|    Service    |  IT   | Public Proj |                    Private Proj                    | Coverage | Linter | Smells | Bugs | Security |
| :-----------: | :---: | :---------: | :------------------------------------------------: | :------: | :----: | :----: | :--: | :------: |
| sonarcloud.io | Cloud |    Free     | ([from 10\$](https://sonarcloud.io/about/pricing)) |    X     |   X    |   X    |  X   |    X     |
|  codacy.com   | Cloud |    Free     |                        Free                        |    X     |   X    |        |      |          |
|  codecov.io   | Cloud |    Free     |                        Free                        |    X     |   X    |        |      |          |
| sonarqube.org | Local |      X      |                         X                          |    X     |   X    |   X    |  X   |    X     |

# Linters

| File Type  |                           VSCode                           |                                             sonarlint/sonarqube setup                                              |
| :--------: | :--------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
|     JS     |  [ESLint](https://eslint.org/docs/user-guide/configuring)  |           [ESLint](https://eslint.org/docs/user-guide/configuring),[JSHint](https://jshint.com/install/)           |
|    JSON    |                             ?                              |                                   [JSONLint](https://github.com/zaach/jsonlint)                                    |
| Dockerfile |      [hadolint](https://github.com/hadolint/hadolint)      |                                  [hadolint](https://github.com/hadolint/hadolint)                                  |
|    YML     |                             ?                              |                                [yamllint](https://github.com/adrienverge/yamllint)                                 |
|    SQL     |                          SQLTools                          |                             [sql-formatter](https://github.com/TeamSQL/sql-formatter)                              |
|     MD     | [markdownlint](https://github.com/DavidAnson/markdownlint) | [remark-lint](https://github.com/remarkjs/remark-lint), [markdownlint](https://github.com/DavidAnson/markdownlint) |
|  .ignore   |                         Not Linted                         |                                                     Not Linted                                                     |
|    TXT     |                         Not Linted                         |                                                     Not Linted                                                     |
|    LOG     |                         Not Linted                         |                                                     Not Linted                                                     |
