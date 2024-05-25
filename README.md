![book-template](https://socialify.git.ci/sakkke/book-template/image?font=Inter&name=1&theme=Light)

Book Template is a starter template of [Zola][zola] with [book][book] theme, including automatic publishing feature to [GitHub Pages][github-pages]. Contains [Dev Containers][dev-containers] battery.

## Quick Start

1. [Create a new repository with using Book Template][use-book-template].
2. Open a generated repository in Visual Studio Code.

## Requirements

Please install the following requirements.

- [Zola][zola]

### Editor

The recommended editor is [Visual Studio Code][visual-studio-code].

## Usage

Please see the `content` directory.

### Workflows

First, please update the `base_url` in `config.toml`.

```mermaid
flowchart LR
    build([Build]) --> zolabuild[Command: zola build]
    serve([Serve]) --> zolaserve[Command: zola serve]
    check([Check]) --> zolacheck[Command: zola check]
```

### Automatic Publishing

Please enable GitHub Pages in your GitHub repository settings.

## License

This template is licensed under [CC0][cc0].

[zola]: https://www.getzola.org/
[book]: https://github.com/getzola/book
[github-pages]: https://pages.github.com/
[dev-containers]: https://code.visualstudio.com/docs/devcontainers/containers
[use-book-template]: https://github.com/new?template_name=book-template&template_owner=sakkke
[visual-studio-code]: https://code.visualstudio.com/
[cc0]: https://creativecommons.org/public-domain/cc0/
