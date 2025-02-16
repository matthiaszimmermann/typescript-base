# Typescript Base Repository

This repository provides a simple development environment for typescript applications using a VSCode DevContainer setup.

## Preparation

To use this repository the following software is required:

- Git
- Docker
- VSCode

## Initial Setup

1. Clone repository into directory of your choice
1. Open VSCode in this directory
1. Run Devcontainer setup

## TypeScript

There is an almost endless amount of sources for TypeScript introductions. 
Examples are [TypeScript Documentation](https://www.typescriptlang.org/docs/handbook/) and [The Concise TypeScript Book](https://github.com/abdessamadbettal/typescript-tutorial).
Even more resources for JavaScript. Example: [The Modern JavaScript Tutorial](https://javascript.info/)

## Interactive Shell

Start the interactive TypeScript shell.

```shell
npx ts-node
```

Experiment.
```typescript
const sum = (a: number, b: number): number => a + b;
sum(1, 1)
sum(1, 'a')
```

## Execute Script / Tests

```shell
npm start
npm test
```
