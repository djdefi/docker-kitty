# Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Quick Start](#quick-start)


# Introduction

Dockerfile to build a kitty image.

# Installation

Pull the latest version of the image from the docker index. This is the recommended method of installation as it is easier to update image in the future. These builds are performed by the **Docker Trusted Build** service.

```bash
docker pull djdefi/kitty:latest
```

Alternately you can build the image locally.

```bash
git clone https://github.com/rtrauntvein/docker-kitty.git
cd docker-kitty
docker build --tag="$USER/kitty" .
```

# Quick Start

Run the image

```bash
docker run djdefi/kitty

```
