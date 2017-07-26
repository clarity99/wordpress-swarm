# wordpress-swarm

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
TODO: Put more badges here.

> Running Wordpress in docker swarm-mode using DNS name-based discovery

TODO: Fill out this long description.

## Table of Contents

- [Security](#security)
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Maintainers](#maintainers)
- [Contribute](#contribute)
- [License](#license)

## Security

## Background

## Install

```
docker stack deploy --compose-file docker-stack.yml wordpress
```

## Usage

To see an example of scaling up MariaDB to 3 nodes (generally for databases you want an odd number of nodes), try:
```
docker service scale wordpress_dbcluster=3
```
When finished, the following command shuts everything down:
```
docker service rm wpcluster wordpress
```
```

## Maintainers

[@thomasvincent](https://github.com/thomasvincent)

## Contribute

See [the contribute file](contribute.md)!

PRs accepted.

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

Apache 2.0 License © 2017 Thomas Vincent