# Repro


## Seeing a lint error as expected:

```
yarn eslint src/DEMO.mdx README.md
```

## No lint error if an .md file is linted first

```
yarn eslint README.md src/DEMO.mdx
```

