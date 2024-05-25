# Book Template

Book Template is a starter template of [Zola][zola] with [book][book] theme, including automatic publishing feature to [GitHub Pages][github-pages].

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

[zola]: https://www.getzola.org/
[book]: https://github.com/getzola/book
[github-pages]: https://pages.github.com/
[visual-studio-code]: https://code.visualstudio.com/
