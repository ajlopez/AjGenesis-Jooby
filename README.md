# AjGenesisNode Jooby

AjGenesisNode Jooby tasks and templates. WIP.

## Installation

Install [AjGenesis for Node](https://github.com/ajlopez/AjGenesisNode) globally using:
```
npm install -g ajgenesis
```
On Linux, you should use `sudo` to install a module globally.

## Usage

In your project directory, run:
```
ajgenesis install jooby
```
in order to have this module available.

To generate client-side artifacts consuming the server API
```
ajgenesis jooby:generate
```

## Development

```
npm install -g ajgenesis
git clone git://github.com/ajlopez/AjGenesisNode-Jooby.git
cd AjGenesisNode-Jooby
npm link ajgenesis
npm install
npm test
```

## Versions

TBD

## Contribution

Feel free to [file issues](https://github.com/ajlopez/AjGenesisNode-Jooby) and submit
[pull requests](https://github.com/ajlopez/AjGenesisNode-Jooby/pulls) — contributions are
welcome.

If you submit a pull request, please be sure to add or update corresponding
test cases, and ensure that `npm test` continues to pass.
