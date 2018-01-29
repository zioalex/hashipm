# [HashiCorp package manager](https://github.com/nodesocket/hashipm)

##### Get the latest version of various HashiCorp packages.

## Installation

```
git clone https://github.com/nodesocket/hashipm.git
ln -s "$PWD"/hashipm/hashipm.bash /usr/local/bin/hashipm
```

## API/Commands

### get

> get \<package\> - Download and install package

### version

> version - Display the current version

```
➜ hashipm --version
hashipm v0.1.0

```

### help

> help - Display help

```
➜ hashipm --help
Usage: hashipm [--version] [--help] command [command-specific-args]

  get <package>   Download and install package
```

## Changelog

https://github.com/nodesocket/hashipm/blob/master/CHANGELOG.md

## Support, Bugs, And Feature Requests

Create issues here in GitHub (https://github.com/nodesocket/hashipm/issues).

## Versioning

For transparency and insight into the release cycle, and for striving to maintain backward compatibility, [hashipm](https://github.com/nodesocket/hashipm) will be maintained under the semantic versioning guidelines.

Releases will be numbered with the follow format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

+ Breaking backward compatibility bumps the major (and resets the minor and patch)
+ New additions without breaking backward compatibility bumps the minor (and resets the patch)
+ Bug fixes and misc changes bumps the patch

For more information on semantic versioning, visit https://semver.org.

## License & Legal

Copyright 2018 Justin Keller

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
