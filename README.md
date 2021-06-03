<p align="center">
  <h3 align="center">Template for typescript applications</h3>

  <p align="center">
     ⚙ Template repository for typescript applications meant to run in node ⚙
    <br />
    <a href="https://github.com/gagoar/ts-node-template#table-of-contents"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://github.com/gagoar/ts-node-template/issues">Report Bug</a>
    ·
    <a href="https://github.com/gagoar/ts-node-template/issues">Request Feature</a>
  </p>
</p>

## Table of Contents

- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

<!-- CONTRIBUTING -->

### Built With

- [ncc](https://github.com/vercel/ncc/)
- [jest](https://github.com/facebook/jest)
- [ora](https://github.com/sindresorhus/ora)
- [commander](https://github.com/tj/commander.js/)
- [cosmiconfig](https://github.com/davidtheclark/cosmiconfig)

## Getting Started

### Builds / Releases

#### Github Tokens

This template utilizes [github-app-installation-token-action](https://github.com/jnwng/github-app-installation-token-action) in order to interact with Github. As per the documentation, the following secrets are needed for proper operation:

```
  appId: ${{ secrets.GITHUB_APP_ID }}
  installationId: ${{ secrets.GITHUB_APP_INSTALLATION_ID }}
  privateKey: ${{ secrets.ORG_PRIVATE_KEY }}
```

#### NPM Tokens

In order for the artifacts to be published, this template requires an NPM token exposed as:

```
  NPM_TOKEN: ${{ secrets.NPM_TOKEN }}
```

If you wish to publish to a registry other than the default (`https://registry.npmjs.org`), such a change can be made in `.github/workflows/release.yml`.

## Contributing

Contributions are what makes the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.
