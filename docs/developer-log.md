#### init 20200526

- monorepo research
- lerna init

```sh
$ npx lerna init
# https://github.com/lerna/lerna#lernajson
```

- test publishing
```js
// packages/palette/package.json
{
  "name": "@dand/palette",
  "version": "0.0.3",
  "publishConfig": {
    "access": "public"
  }
}
```
```sh
$ lerna publish
```