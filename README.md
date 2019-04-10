<h1 align="center">
  📦🚀 @n4bb12/config-semantic-release
</h1>

<p align="center">
  Shareable <a href="https://semantic-release.gitbook.io">semantic-release</a> configuration
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@n4bb12/config-semantic-release">
    <img alt="Version" src="https://flat.badgen.net/npm/v/@n4bb12/config-semantic-release?icon=npm">
  </a>
  <a href="https://raw.githubusercontent.com/n4bb12/config-semantic-release/master/LICENSE">
    <img alt="License" src="https://flat.badgen.net/github/license/n4bb12/config-semantic-release?icon=github">
  </a>
  <a href="https://github.com/n4bb12/config-semantic-release/issues/new/choose">
    <img alt="Issues" src="https://flat.badgen.net/badge/github/create issue/pink?icon=github">
  </a>
</p>

## Plugins

This configuration use the following plugins:
- [@semantic-release/commit-analyzer](https://github.com/semantic-release/commit-analyzer)
- [@semantic-release/release-notes-generator](https://github.com/semantic-release/release-notes-generator)
- [@semantic-release/npm](https://github.com/semantic-release/npm)
- [@semantic-release/git](https://github.com/semantic-release/git)
- [@semantic-release/github](https://github.com/semantic-release/github)

## Install

```
yarn add --dev @n4bb12/config-semantic-release
```

## Usage

Extend the configuration in the semantic-release [config file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@n4bb12/config-semantic-release"
}
```

## Configuration

See each plugin documentation for configuration options.
