# nuxt-require-bug

## Instructions

```sh
yarn
# It's necessary to get back the stubbed lib
git checkout node_modules
```

### Dev

- Run in dev mode `yarn run dev`
- Visit the website
- Server logs _i am cjs_ but client says _i am module_

### Generate

- `yarn generate` -> i am cjs
- `serve dist` -> i am module
- same with `yarn start`
