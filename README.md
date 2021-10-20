## tsconfig
### Install:

```bash
yarn add @caisy/tsconfig -D
```

### Usage:
```json
{
	"extends": "@caisy/tsconfig/tsconfig.json",
	"include": ["src/**/*"],
	"compilerOptions": {
		"outDir": "dist",
		"rootDir": "./src",
		//"target": "ES2021",
	}
}
´´´