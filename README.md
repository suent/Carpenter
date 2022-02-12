![Carpenter](media/Carpenter-Title_400x122.png)

[Suent](https://www.suent.net)

[![Build Status](https://dev.azure.com/suent/Carpenter/_apis/build/status/carpenter?repoName=suent%2Fcarpenter&branchName=main)](https://dev.azure.com/suent/Carpenter/_build/latest?definitionId=6&repoName=suent%2Fcarpenter&branchName=main)


# Introduction

Carpenter is a cross-platform dotnet (.NET) build process helper. Carpenter integrates into
a project to provide additional functionality as part of the build process.

## Features

Carpenter provides the following functionality:

### Developer Build Versioning

As part of the project build, consistent versioning is applied to the binaries and packages
that are created.

#### Developer Build Version

A developers build of v1.2.3, built 09/07/2019 13:34:42.346 on machine fred-pc by user fred.

Example: 1.2.3-dev.20190907-133442-346+fred-pc.fred

#### Using Developer Build Versioning

Developer build versioning is automatically applied to projects that have referenced Carpenter
and that have the value ```dev``` for the project VersionSuffix.

# Development

For details on development, please see the [Carpenter development wiki](https://dev.azure.com/suent/Carpenter/_wiki/wikis/Carpenter.wiki).

Please also take note of the Carpenter [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing guidelines](CONTRIBUTING.md).
