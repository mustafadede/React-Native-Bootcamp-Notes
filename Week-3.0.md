## Path

```
npm i --save-dev babel-plugin-root-import
```

```
plugins: [['babel-plugin-root-import', { paths: [{ rootPathPrefix: '~', rootPathSuffix: 'src' }] }]],
```

- Root içerisinde olması gereken jsconfig.json dosyası

```
{
	"compilerOptions": {
		"target": "ES2021",
		"baseUrl": ".",
		"module": "commonjs",
		"paths": {
			"~/*": [
				"./src/*"
			]
		}
	},
	"exclude": [
		"./node_modules"
	]
}
```