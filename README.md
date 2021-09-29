# Compound Web3 Front-end

Palisade is the web3 front-end experience to interact with the Compound Ethereum protocol.

[![Add to Homescreen](https://img.shields.io/badge/Skynet-Add%20To%20Homescreen-00c65e?style=for-the-badge&labelColor=0d0d0d&logo=data:image/png;base64,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)](https://homescreen.hns.siasky.net/#/skylink/AQDaZYBJvT6u2CyHziBDEFbhJ_aOIQH_eEqbwwApr9_ryg)

## Contributing

We welcome contributions from the community to help keep the Compound web3 front-end working great. You can read more here about [how to contribute](CONTRIBUTING.md).

## Configuration

The web3 front-end requires several items to be configured before it can be started properly. The required format is of the form of several json files that specify config options between local development (`development.json`) and the version that is intended to be deployed (`production.json`). The local and deployment scripts automatically look for those files to exist in the path `config/env`.

```
config/
├── env
│   ├── development.json
│   ├── production.json
```

The following is an example configuration file:

```json
{
  "API_BASE_URL_MAP": {
    "goerli": "https://api.compound.finance/api/",
    "kovan": "https://api.compound.finance/api/",
    "rinkeby": "https://api.compound.finance/api/",
    "ropsten": "https://api.compound.finance/api/",
    "mainnet": "https://api.compound.finance/api/"
  },
  "DATA_PROVIDERS": {
    "development": "http://localhost:8545",
    "goerli": "https://goerli.infura.io/v3/YOUR-PROJECT-ID",
    "rinkeby": "https://rinkeby.infura.io/v3/YOUR-PROJECT-ID",
    "kovan": "https://kovan.infura.io/v3/YOUR-PROJECT-ID",
    "ropsten": "https://ropsten.infura.io/v3/YOUR-PROJECT-ID",
    "mainnet": "https://mainnet.infura.io/v3/YOUR-PROJECT-ID"
  },
  "NETWORK_MAP": {
    "mainnet": 1,
    "ropsten": 3,
    "rinkeby": 4,
    "goerli": 5,
    "kovan": 42,
    "development": 999
  },
  "DEFAULT_NETWORK": "mainnet",
  "BLOCKNATIVE_API_KEY": "YOUR_BLOCKNATIVE_KEY"
}
```

Each of the top level keys have the following functions:

- `API_BASE_URL_MAP` - Object mapping of Eth network name as key and value being the desired Compound Api host. This can be left as is.
- `DATA_PROVIDERS` - Object mapping of Eth network name as key and value being the url of a corresponding JSON RPC host. This example shows Infura as a sample JSON RPC provider and you can find more information [here](https://infura.io/docs/ethereum). Note: this can be specified by setting in the env var `DATA_PROVIDERS` as JSON (e.g. `export DATA_PROVIDERS='{"rinkeby": "https://infura.io/..."}'`).
- `NETWORK_MAP` - Object mapping of Eth network name as key and value being the corresponding NetworkId value. This can be left as is.
- `BLOCKNATIVE_API_KEY` - Blocknative API Key required to track transaction notifications. You can find more information [here](https://docs.blocknative.com/notify). Note: this can be specified by setting the env var `BLOCKNATIVE_API_KEY`. This key is not strictly required (but provides a better user experience).

## Getting Started

The Compound web3 front-end is written in [elm](http://elm-lang.org/) and was bootstrapped with [create elm app](https://github.com/halfzebra/create-elm-app). We strongly recommmend getting familiar with the Elm framework before jumping into the Compound source code.

To get started, first clone this repo:

```bash
> git clone https://github.com/compound-finance/palisade.git && cd palisade
```

Next, install yarn dependencies (note, you should not use `npm` intsead of `yarn` during `install` because `npm` does not respect `yarn.lock` but you should be able to use `npm` for the other commands.):

```bash
> yarn install --lock-file
```

Next, build and watch for string translation changes:

```bash
> yarn watch-i18n
```

Note: For more information on string translations, see [i18n.md](i18n.md)

Next, build and watch for SASS changes:

```bash
> yarn watch-css
```

or, if you prefer just to build your CSS once, run: `yarn build-css`.

And separately start your development server for the front-end:

```bash
> yarn start
```

Note: Elm may take a while to pull in dependencies when you first run the app. At this point you should be able to navigate to [http://localhost:3000](http://localhost:3000) to view your application.

## Deployment

This application is set-up for easy deployment as a static web site.

### Generic Deployment

To deploy this application, first build your static assets:

```bash
> yarn run build-css
> yarn run build
```

Now the `/build` directly should contain all of the files necessary to serve your application from whatever hosting provider you choose. This repo includes support for two options as possible deployment targets, IPFS and Google Cloud Storage.

### IPFS

To deploy the web3 front-end on IPFS, you first should be familiar with [Hosting a single-page website on IPFS](https://docs.ipfs.io/how-to/websites-on-ipfs/single-page-website/). Follow the instructions and you should be able to add all the files in the `/build` directory and obtain a IPFS hash which you can then open on any gateway provider to view the hosted web3 front-end.

Alternatively, you may wish to deploy to an IPFS hosting service like [Infura IPFS](https://infura.io/docs/ipfs#section/Getting-started). This repo includes a script to deploy the `/build` directory to an IPFS host specified by several environment variables.

To deploy a build to Infura IPFS:

```bash
IPFS_AUTH="PROJECT_ID:PROJECT_SECRET" \
  IPFS_HOST="ipfs.infura.io" \
  IPFS_PORT=5001 \
  yarn deploy-ipfs
```

Each of environment variables have the following functions:

- `IPFS_AUTH` - Basic authentication for header for using the Infura IPFS add endpoint. You can find more information [here](https://infura.io/docs/ipfs#section/Authentication).
- `IPFS_HOST` - IPFS Pinning service host.
- `IPFS_PORT` - IPFS Pinning service host port.

Note: The `deploy-ipfs` script has been tested and used with Infura IPFS. You may need a few changes to support alternative pinning services.

### Google Cloud Storage

To deploy the Compound web3 front-end to Google Cloud Storage, you should be familar with [Hosting a Static Site](https://cloud.google.com/storage/docs/hosting-static-website) on Google Cloud. Follow the instructions on creating a CNAME record with your DNS provider and creating a fully-public bucket. Also, make sure to have the [Cloud SDK](https://cloud.google.com/sdk/) tools installed, that you're logged in via `gcloud auth`, and that you have [your correct project set](https://cloud.google.com/sdk/gcloud/reference/config/set).

To deploy to a gcloud bucket:

```bash
> yarn deploy-gcloud your.bucket.name
```

## Internationalization

To learn more about internationalization, please view [i18n.md](i18n.md).

## Discussion

For any concerns with the web3 front-end, open an issue or visit us on [Discord](https://discord.com/invite/compound) to discuss.

# License

Copyright 2021, Compound Labs, Inc. and repository contributors. This repository is licensed under GPLv3 (please see [LICENSE](/LICENSE) for the full-text of the license).

All contributors to this repository must release contributed code under this GPLv3 license, free of any other encumbrance. Contributors also agree that contributions may be re-licensed under MIT or BSD-3 licenses in the future without notice. In such instances, all copyright notices will be retained.
