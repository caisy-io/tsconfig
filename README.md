## tsconfig
### Install:

```bash
yarn add @caisy/tsconfig -D
```

### Usage:
Add "target": "ES2021" in compilerOptions, if you want to target a different ES version.
```json
{
	"extends": "@caisy/tsconfig/tsconfig.json",
	"include": ["src/**/*"],
	"compilerOptions": {
		"outDir": "dist",
		"rootDir": "./src",
	}
}
