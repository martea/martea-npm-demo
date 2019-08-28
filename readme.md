# Test project for publishing to npmjs

## publishing

command below does publish the package to online repo.

```shell
npm publish
```

## versioning

```shell
npm version <patch|minor|major>
```

## configure what should be included

```json
{
  "files": ["dist", "src/common/*.js"]
}
```

### what should be excluded

implement `.npmignore` file, same semantic as .gitignore
