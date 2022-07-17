<div align='center'>
  <img src=".erb/img/pangu-logo.png" width="50%" />
</div>

<br>

<div align="center">

[![Build Status][github-actions-status]][github-actions-url]
[![Github Tag][github-tag-image]][github-tag-url]

</div>

## Install

Clone the repo and install dependencies:

```bash
git clone --depth 1 --branch main https://github.com/pangu-dev/pangu-electron.git your-project-name
cd your-project-name
pnpm install
```

## Starting Development

Start the app in the `dev` environment:

```bash
pnpm start
```

## Packaging for Production

To package apps for the local platform:

```bash
pnpm package
```

## License

MIT

[github-actions-status]: https://github.com/pangu-dev/pangu-electron/workflows/Test/badge.svg
[github-actions-url]: https://github.com/pangu-dev/pangu-electron/actions
[github-tag-image]: https://img.shields.io/github/tag/pangu-dev/pangu-electron.svg?label=version
[github-tag-url]: https://github.com/pangu-dev/pangu-electron/releases/latest
