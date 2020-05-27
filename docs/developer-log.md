#### init 20200526

- monorepo research
- [lerna](https://github.com/lerna/lerna) init

```sh
$ npx lerna init --independent
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