# Creating a DID on Veres One

This quick Developer Guide will walk you through creating a decentralized
identifier using command line tools.

## Requirements

* [Node.js v8.6+ and Node.js v10.x](https://nodejs.org/en/download/).  

### Coming Soon

Node.js v12 support will be added in the upcoming v0.5 release.

## Install did-cli
`did-cli` is a command line tool that allows the user to interact with the
Veres One ledger. See the [README](https://github.com/digitalbazaar/did-cli) for
a full list of supported command line options.

Install the Decentralized Identifier CLI tool by running the following command:

```
> mkdir did-cli
> cd did-cli
> npm install did-cli
```

## Generate a Decentralized Identifier

Generate a Decentralized Identifier on the Veres One Testnet by running the
following command:

```
> ./node_modules/did-cli/did generate --register
```

Once the command above runs, you will have a new Decentralized Identifier.
Information related to your Decentralized Identifier will be stored in the
following directory:

```
> ls $HOME/.dids/veres/test
```
