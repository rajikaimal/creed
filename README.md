# creed

YAML based task runner

```yaml
worker: Load meta data
tasks:
	- task:
			name: Install deps
			cmd: npm i
	- task:
			name: Run app
			cmd: npm start
```

MIT
