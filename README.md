# Dev Container Features

## Content

This repository contains following features:

* [kubeswitch](https://github.com/danielfoehrKn/kubeswitch): Install kubeswitch CLI tools

## Usage

To use the features from this repository, add the desired features to devcontainer.json.

This example use kubeswitch feature on devcontainer.

```shell
{
    "image": "mcr.microsoft.com/devcontainers/base:ubuntu",
    "features": {
        "ghcr.io/gaetanars/features/kubeswitch:1": {
            "version": "latest"
        }
    }
}
```