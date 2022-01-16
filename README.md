# tsconfig

[![npm version](https://badge.fury.io/js/%40byintera%2Ftsconfig.svg)](https://badge.fury.io/js/%40byintera%2Ftsconfig)

Intera's Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ npm install --save-dev @byintera/tsconfig
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@byintera/tsconfig",
	"compilerOptions": {
		"outDir": "build",
		"target": "es5",
	}
}
```


## License

MIT
