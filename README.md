# HashiCorp package manager

#### Get the latest version of various HashiCorp packages.

Hashipm supports the following packages:

<img src="https://s3.amazonaws.com/hashicorp-marketing-web-assets/brand/Consul_VerticalLogo_FullColor.r1x9c1CS6x.svg" width="75px" alt="Consul" style="float: left" />
<img src="https://s3.amazonaws.com/hashicorp-marketing-web-assets/brand/Nomad_VerticalLogo_FullColor.r1x_p8YHag.svg" width="75px" alt="Nomad" style="float: left" />
<img src="https://s3.amazonaws.com/hashicorp-marketing-web-assets/brand/Packer_VerticalLogo_FullColor.svg" width="75px" alt="Packer" style="float: left" />
<img src="https://s3.amazonaws.com/hashicorp-marketing-web-assets/brand/Terraform_VerticalLogo_FullColor.B1rgyCrag.svg" width="75px" alt="Terraform" style="float: left" />
<img src="https://s3.amazonaws.com/hashicorp-marketing-web-assets/brand/Vault_VerticalLogo_FullColor.B1xPC0pSax.svg" width="75px" alt="Vault" style="float: left" />

A project by [Elastic Byte](https://elasticbyte.net). Built with :heart: in :guitar: Nashville.

## Installation

```
git clone https://github.com/elasticbyte/hashipm.git
ln -s "$PWD"/hashipm/hashipm.bash /usr/local/bin/hashipm
```

##### Bash shell

```
echo "HASHIPM_ROOT=$PWD/hashipm" >> "$HOME"/.profile
source "$HOME"/.profile
```

##### Zsh shell

```
echo "HASHIPM_ROOT=$PWD/hashipm" >> "$HOME"/.zshrc
source "$HOME"/.zshrc
```

## Requirements

- curl
- unzip

## API/Commands

### get

> get \<package\> - Download and install package
 
```
➜ hashipm get terraform
Downloading terraform (0.11.3) from https://releases.hashicorp.com/terraform/0.11.3/terraform_0.11.3_darwin_amd64.zip...
Installed terraform (0.11.3) into /usr/local/bin
```

### version

> version - Display the current version

```
➜ hashipm --version
hashipm v0.6.0

```

### help

> help - Display help

```
➜ hashipm --help
Usage: hashipm [--version] [--help] command [command-specific-args]

  get <package>   Download and install package
```

## Changelog

https://github.com/elasticbyte/hashipm/blob/master/CHANGELOG.md

## Support, Bugs, And Feature Requests

Create issues here in GitHub (https://github.com/elasticbyte/hashipm/issues).

## Versioning

For transparency and insight into the release cycle, and for striving to maintain backward compatibility, [hashipm](https://github.com/elasticbyte/hashipm) will be maintained under the semantic versioning guidelines.

Releases will be numbered with the follow format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

+ Breaking backward compatibility bumps the major (and resets the minor and patch)
+ New additions without breaking backward compatibility bumps the minor (and resets the patch)
+ Bug fixes and misc changes bumps the patch

For more information on semantic versioning, visit https://semver.org.

## License & Legal

Copyright 2018 [Elastic Byte](https://elasticbyte.net)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
