# tsconfig

[![GitHub version](https://badge.fury.io/gh/joaovcoliveira%2Ftsconfig.svg)](https://badge.fury.io/gh/joaovcoliveira%2Ftsconfig)

Intera's Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```
$ npm install --save-dev @joaovcoliveira/tsconfig
```

## Usage

`tsconfig.json`

```json
{
	"extends": "@joaovcoliveira/tsconfig",
	"compilerOptions": {
		"outDir": "build",
		"target": "es5",
	}
}
```


## License

MIT
