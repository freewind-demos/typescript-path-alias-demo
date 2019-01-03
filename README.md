TypeScript Paths Alias Demo
===========================

It's very tricky that typescript supports `paths` in `tsconfig.json`,
and will check the path alias correctly when compiling,
but the generate code with these path alias are not handled by node.

We have to use another plugin `tsconfig-paths` to handle the path aliases for running.

```
npm install
npm run test
```

